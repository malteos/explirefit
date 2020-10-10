# ExpliRefit
(Explicit() Specialization of distributional embedding spaces for semantic similarity

Detailed description coming soon. 

## Install

```bash
git clone https://github.com/malteos/explirefit
cd explirefit
conda create -n explirefit python=3.6
conda activate explirefit 
pip install -r requirements.txt
```

## Reproduce

```bash
python trainer.py /Volumes/data/repo/data/glove.6B/glove.6B.50d.txt ./data/constraints/synonyms.txt ./data/constraints/antonyms.txt ./data/model
python trainer.py /Volumes/data/repo/data/glove.6B/glove.6B.50d.1k.txt ./data/constraints/synonyms.txt ./data/constraints/antonyms.txt ./data/model
python converter.py /Volumes/data/repo/data/glove.6B/glove.6B.50d.1k.txt ./data/model ./data/converted

```