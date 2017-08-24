# gas-db-experiments
Experiments for [niklele/gas-db](https://github.com/niklele/gas-db)

## Usage

1. Start virtualenv environment
```
virtualenv env
source env/bin/activate
```

2. Install packages
```
brew install geos
sudo -H pip3 install https://github.com/matplotlib/basemap/archive/v1.1.0.tar.gz
pip3 install -r requirements.txt
```

3. Open jupyter notebook
```
jupyter notebook
```

## Packages Used
- jupyter
- numpy
- pandas
- matplotlib
- seaborn
- basemap


### Adding new packages
```
pip3 install [something]
pip3 freeze > requirements.txt
```