# CMPE-257 Transformers
# G2Net Detecting Continuous Gravitational Waves

# INTRODUCTION
Gravitational waves are ripples in space which can be associated with events such as black holes and exploding stars when cataclysmic waves are detected. Humans can’t see these gravitational waves, but with the help of antennas such as LIGO (Laser Interferometer Gravitational-Wave), it can detect vibrations in the medium of space. The medium of space is something scientists are still researching to this day and could play an important role in telling us more about what is in the universe. 
The current approaches include techniques for improving the sensitivity of Advanced Laser Interferometer GW Observatory and Advanced Virgo GW searches, methods for fast measurements of the astrophysical parameters of GW sources, and algorithms for the reduction and characterization of non-astrophysical detector noise. These applications demonstrate how machine learning techniques may be harnessed to enhance the science that is possible with current and future GW detectors.

# PROJECT DESCRIPTION
The goal of this project is to find continuous gravitational-wave signals. We will develop a model sensitive enough to detect weak yet long-lasting signals emitted by rapidly-spinning neutron stars within noisy data. Our current approach to this dataset is to clean data, do exploratory data analysis, data-preprocessing, train machine learning models, perform hyperparameter optimisation, and evaluation and compare different results of machine learning models. The approach to solving this problem is subject to change since the topic of gravitational waves is vast, and the more research we do could grant us new ways to tackle our goal.
We will be using multiple models like CNN, LSTM and many more and compare them.
We are going to do optimizations to these models like hyperparameter optimization and make comparisons with the same model but with different hyperparameters.

# EDA
The purpose of EDA is to understand the data, discover trends and patterns, and present visualizations of the data. From that information, we can find features and models that best fit the data.
- Describe the data
  - HDF5
  - id & target
- Mask the data 
  - Freq (Hz)
  - H1 (LIGO Hanford detector )
  - L1 (LIGO Livingston detector )
- Visualize frequency of waves  
![image](https://user-images.githubusercontent.com/57043103/204921723-02ea57f3-ce6d-42c1-8351-1fc04e61eaa3.png)
- Distributions

-  MODELS
We are using 3 models and compare them and choose the model which has the best accuracy.
The models we will be using are:
- CNN
- LSTM
- LGBM 
- Ensembling models (XGB, CATBOOST, LGBM, RANDOM FOREST)

# CONCLUSION
Using this project we were able to detect gravitational waves. We tried using multiple models and see which model produced the best result.
We found that the CNN model to be more accurate and efficient compared to the other models we tested on. 
We have optimized our model by changing the hyper-parameters.
