# TS_RNN_Experiments
Experiments setup to evaluate the performance of the RNN forecasting with different data processing method, forecasting strategies and cross-series methods 

## Dir tree
├── experiments  
│        ├── Compare_crossseries_info.ipynb - Experiment on the influence of cross-series methods of RNN forecasting on the quality of the RNN forecast  
│        ├── Compare_data_transformers.ipynb - Experiment on the influence of data processing methods on the quality of the RNN forecast  
│        └── Compare_prediction_methods.ipynb - Experiment on the influence of forecasting strategies on the quality of the RNN forecast  
├── reports  
│        ├── data_tr_experiment_all - outputs of data transformers experiment  
│        ├── factors_experiment_all - outputs of cross-series methods experiment  
│        ├── factors_experiment_all_notdeseason - outputs of cross-series methods experiment without deseason ts processing  
│        ├── strategy_experiment_all - outputs of forecasting strategies experiment  
│        └── strategy_experiment_all_notdeseason - outputs of forecasting strategies experiment without deseason ts processing  
├── requirements.txt  
├── README.md  


## Experiments
[Compare_data_transformers](https://github.com/LevPerla/TS_RNN_Experiments/tree/master/experiments/Compare_data_transformers.ipynb)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/LevPerla/TS_RNN_Experiments/blob/master/experiments/Compare_data_transformers.ipynb)

[Compare_prediction_methods](https://github.com/LevPerla/TS_RNN_Experiments/tree/master/experiments/Compare_prediction_methods.ipynb)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/LevPerla/TS_RNN_Experiments/blob//master/experiments/Compare_prediction_methods.ipynb)

[Compare_crossseries_info](https://github.com/LevPerla/TS_RNN_Experiments/tree/master/experiments/Compare_crossseries_info.ipynb)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/LevPerla/TS_RNN_Experiments/blob/master/experiments/Compare_crossseries_info.ipynb)


