# vasaloppet
analysis of vasaloppet

using the VasAPI 
https://github.com/basegpu/vasapi

usage examples:
```
https://vasa-api.herokuapp.com/result/<year>/<M/W>/<place.in.M/W>
https://vasa-api.herokuapp.com/result/2022/M/795
https://vasa-api.herokuapp.com/result/2020/M/414
https://vasa-api.herokuapp.com/result/1922/M/1
```

## Structure
* notebook 01 is for getting the data and saving them in data/ as pickles
* already saved data is in data/
* the other notebooks are for analysis.
* Notebook 03 has some analysis for 2022. 
* if you need examples of how to load and work with the data, check notebook 03

## To get it running do the following steps:

1. clone git
2. in your git directory: load the conda environment from environment.yml and activate it by 

```
conda activate env_vasaloppet
```
3. run jupyter notebook server with 
```
jupyter notebook
```
4. start analyzing





