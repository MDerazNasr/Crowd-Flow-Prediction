## Prediction of crowd flow

Python impletmentaion of the thesis ***AdjNet: a deep learning approach for Crowd Flow Prediction*** ([Link](https://etd.adm.unipi.it/t/etd-06092021-221917/))

#### Dataset

Flow data [available online](https://www.citibikenyc.com/system-data)



# Install
At first you need to clone this repository:
```shell
$ git clone https://github.com/jonpappalord/crowd_flow_prediction
$ cd crowd_flow_prediction
```

Create a new environment:
```shell
$ python -m venv yourenvname 
$ source yourenvname/bin/activate
```


Launch the following command to install the required packages

```shell
$ pip install -r requirements.txt
```

# Usage

We have prepared an instance for running the model, that is `main.py`.

<!-- If you want to try them on the bike NYC bike dataset you can download it from the [official page](https://www.citibikenyc.com/system-data) and save them in the `data/BikeNYC` folder. Then just tune the hyperparameters as you wish in the `main.py` and launch it with -->

```shell
$ python main.py
```





