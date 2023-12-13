# Proposed-STGCN

This repo is part of our group project for CS7643.

**Proposed model 4,5,7 are based on the authors' STGCN repo**:
https://github.com/hazdzz/STGCN/tree/main

To run each proposed model, 

**Step 1, download datasets from** https://github.com/hazdzz/STGCN/tree/main/data/metr-la

Keep the same folder structure for each proposed model:

- data
  - metr-la
    - adj.npz
    - vel.csv
- model
  - __init__.py
  - layers.py
  - models.py
- script
  - __init__.py
  - dataloader.py
  - earlystopping.py
  - utility.py
- main.py

**Step 2, run**

```
python main.py
```


