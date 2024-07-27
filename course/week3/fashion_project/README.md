# Week 3 Project: Active learning on fashion classifier

```
pip install -e .
```

This project will investigate various strategies to identify elements for relabeling.


# Results
MODEL (DEFAULT).    : 30.2%
MODEL (RANDOM)      : 40.9%
MODEL (UNCERTAINTY) : 38.2%
MODEL (MARGIN)      : 44.8%
MODEL (ENTROPY)     : XX.X%
MODEL (AUGMENT)     : XX.X%


|model version|production acc|offline acc|train acc|
|-------------|---------------|-----------|--------|
|MODEL (DEFAULT) |30.2%|85.3%|NA|
|MODEL (RANDOM)  |40.9%|53.3%|75%|
|MODEL (UNCERTAINTY)|38.2%|61.2%|85%|
|MODEL (MARGIN)|44.8%|65.3%|87.5%|
|MODEL (ENTROPY)|43.0%|67.1%|87.5%|
|MODEL (AUGMENT)|xx%|xx%|xx%|
