# ARC_Basics
Starter code for Abstraction and Reasoning Corpus

# Requirements
numpy, matplotlib, tqdm

# Folder Structure
```
├── ARCLOADER.py
├── data # original ARC dataset
│   ├── evaluation
│   └── training
├── settings.json # color RGB values (with additional 3 colors)
├── thumbnail_generator.py # visualized image sets
└── VISUALIZATION.py # visualization code
```
# Initial Execution
```
python thumbnail_generator.py
```
Using original ARC dataset, this will generate image sets. It takes around 10 minutes to generate all.

It will generate three folders of thumbnails in the data folder.
```
├── ARCLOADER.py
├── data
│   ├── evaluation     # original ARC evaluation set (.json)
│   ├── training       # original ARC training set   (.json)
│   ├── full           # full task including answer  (.png)
│   ├── thumbnails     # only example pairs          (.png)
│   └── without_answer # task without answer         (.png)
```
