# S2DS NLP project  

_The NLP project that was created to assess timeliness of the media content created by the Client._


The project was created as part of an Science2DataScience internship by the group of 5 scientists.


The directory structure of the project looks like this: 

```
├── README.md          <- The top-level README for developers using this project.
├── data
│   ├── external       <- Data from third party sources.
│   ├── interim        <- Intermediate data that has been transformed.
│   ├── processed      <- The final, canonical data sets for modeling.
│   └── raw            <- The original, immutable data dump.
│
├── models             <- Trained and serialized models, model predictions, or model summaries
│
├── notebooks          <- pipeline1_main and pipeline2_main are the main Jupyter notebooks that contain the working model
│   ├── outdated       <- draft notebooks of team members
│   └── supplementary  <- Additional 'clean' notebooks for the project.                  
│
├── references         <- Data dictionaries, manuals, and all other explanatory materials.
│
├── reports            
│   ├── illustrations  <- .jpg files that are used in main notebooks 
│   └── figures        <- Generated graphics and figures that are used in notebook
│
├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
│                         generated with `pip freeze > requirements.txt`
│
├── src                <- Source code for use in this project.
    ├── data           <- Scripts to download or generate data
    │   ├── make_datasets_allpytrends.py
    │   ├── preprocess_keywords.py
    │   └── make_dataset.py
    │
    ├── features       <- Scripts to turn raw data into features for modeling
    │   └── build_features.py
    │
    ├── models         <- Scripts to train models and then use trained models to make
    │   │                 predictions
    │   ├── predict_model.py
    │   └── train_model.py
    │
    └── visualization  <- Scripts to create exploratory and results oriented visualizations
        └── visualize.py

```

## Contributing

by Anna Makushkina, Magda Dubois, Marios Akritas, Wojciech Lason, Ferdinand Torron

### Installing development requirements
------------

    pip3 install -r requirements.txt


