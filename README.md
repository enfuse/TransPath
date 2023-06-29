# TransPath: Learning Heuristics For Grid-Based Pathfinding via Transformers
[This](https://github.com/AIRI-Institute/TransPath) is the code repository for the following paper published at AAAI 2023: 

Daniil Kirilenko, Anton Andreychuk, Aleksandr Panov, Konstantin Yakovlev, TransPath: Learning Heuristics for Grid-Based Pathfinding via Transformers. Proceedings of the AAAI Conference on Artificial Intelligence. 37, 10 (Jun. 2023), 12436-12443. DOI: [https://doi.org/10.1609/aaai.v37i10.26465](https://github.com/AIRI-Institute/TransPath).

![Visual abstract](images/visual_abstract.png)

## Data
Train, validation, and test maps with pre-computed values mentioned in our paper are available [here](https://disk.yandex.ru/d/xLeW_jrUpTVnCA). One can download and exctract it manually or just run `download.py`.

## Pretrained models
Directory `./weights` contains parameters for some of the pre-trained models from the paper.

Use `train.py` to train a model from scratch.

## Examples
Check `example.ipynb` for some examples of predictions and search results of our models. There are a few examples of train and out-of-distribution maps in the directory `./maps`.
