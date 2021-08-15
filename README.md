# Bearing_RUL_Prediction

Academic project on 
**Remaining Useful Life prediction of bearing using Self Organizing Map and Support Vector Regression**


#

##### PROBLEM STATEMENT: 
Bearings are critical components of rotating machines since the failure of these may cease the functioning of the entire equipment. The damages observed due to bearing failures are huge and thus there is a need to develop an effective prognostic methodology to prevent the sudden machinery breakdown.
Accurate determination of remaining useful life of bearing is an important issue and a methodology needs to be created to address this issue that accurately predicts the Remaining Useful Life of the bearing so that when it passes a certain level, the corresponding bearings can be replaced so as to avoid failure of equipment.

#

##### DATASET:

The dataset used for this project is *‘IEEE PHM 2012 Dataset’* which contains the datasets for bearings experimented under 3 conditions. 
Some datasets contain the observations for the bearings until failure occurs and thus these are used as the training sets for our project. Some datasets contains the observations for the bearings which are truncated before the failure occurs and for these datasets, the remaining useful life is given which is needed to be predicted and thus these are used as the test sets for our project.
The experiments were performed on the *PRONOSTIA* platform which gave these datasets.

#

##### METHODOLOGY:

This project is based on the research paper *‘Intelligent bearing performance degradation assessment and remaining useful life prediction based on self-organising map and support vector regression’* by *Akhand Rai* and *Sanjay H Upadhyay*. 
The paper has made use of the Self Organizing Map and Support Vector Regression for the learning and prediction of Remaining Useful Life of the bearings.

The steps carried out in this project to perform the Remaining Useful Life Predictions as proposed in the research paper are:
1. Feature Extraction
2. Self Organizing Map
3. Minimum Quantization Error (MQE)
4. Life Percentage
5. BHI (Bearing Health Index)
6. Support Vector Regression (SVR)
7. Predicting RUL


*(Refer to the Project Report for in-depth understanding of these steps)*

#

##### COLAB JUPYTER NOTEBOOK
[Project Source and Results (Jupyter Notebook)](https://colab.research.google.com/drive/1dW-QcywTNAsUpzcT8kWNRxrd4eF3vmNY?usp=sharing)

#

##### REFERENCES

1.	[Research Paper](https://journals.sagepub.com/doi/10.1177/0954406217700180)
2.	[PHM-IEEE-Challenge Dataset Description](https://github.com/wkzs111/phm-ieee-2012-data-challenge-dataset)
3.	[PHM-IEEE-Challenge Dataset](https://github.com/wkzs111/phm-ieee-2012-data-challenge-dataset)
3.	[SOMPY - Self Organizing Map Python Library](https://github.com/sevamoo/SOMPY)
4.	[Scipy - Fourier Transforms](https://docs.scipy.org/doc/scipy/reference/generated/scipy.fft.fft.html)
5.	[Scipy - Hilbert Curve (Signal Envelope)](https://docs.scipy.org/doc/scipy/reference/generated/scipy.signal.hilbert.html)

