# Predicting Student Dropout and Academic Success

## Table of context
	1 Stages
	 1.1 Data collection and preparation.
	  1.1.1 Data collection.
	  1.1.2 Data cleaning and pre-processing.
	 1.2 Splitting the data.
	 1.3 Model selection and training.
	 1.4 Model evaluation.
	 1.5 Model tuning and refinement.

## 1 Stages

### 1.1 Data collection and preparation:
	Data collection and preparation is one of the most important stages as the quality 
	of the data greatly impacts the accuracy and effectiveness of the resulting model.

#### 1.1.1 Data collection:
	At this step data is to be loaded for further analysis.
[Data Collection link](https://github.com/eugene-kbl/Predicting-Student-Dropout-and-Academic-Success/blob/6fd383e01e459a901b4119cabd03bfc159b0881f/Project%20Files/1.1.1%20Data_Collection.ipynb)

#### 1.1.2 Data cleaning and pre-processing:
	Once the data is loaded, it must be checked for any issues which can 
	potentially impact the accuracy and effectiveness of the model. 
	Moreover, the following issues must be identified: 
		a) incomplete data; 
		b) incorrect data;
		c) data imbalance; 
		d) irrelevant data; 
		e) data duplication; 
		f) data normalization.
[Data Overview link](https://github.com/eugene-kbl/Predicting-Student-Dropout-and-Academic-Success/blob/b35829321b5ad25f80af88e28937470c8dd86347/Project%20Files/1.1.2%20Data_Overview.ipynb)

##### Incomplete data
	Missing values or incomplete data can impact the accuracy of the model. 
	Several techniques can be leveraged to address incomplete data, such as data imputation or 
	removal of observations with missing values.
[Incomplete data link](https://github.com/eugene-kbl/Predicting-Student-Dropout-and-Academic-Success/blob/35d5d47c1b055fe8dd18e310c09a8fbaa90adac1/Project%20Files/Incomplete_Data.ipynb)

##### Incorrect data
	Incorrect data or inaccurate data can also impact the accuracy of the model. 
	Data accuracy refers to the consistency of data with reality. 
	The accurate data must reflect the feature information consistent with its objective. 
	Techniques such as data cleaning can be leveraged to address incorrect data.
[Incorrect data link](https://github.com/eugene-kbl/Predicting-Student-Dropout-and-Academic-Success/blob/35d5d47c1b055fe8dd18e310c09a8fbaa90adac1/Project%20Files/Incorrect_Data.ipynb)

##### Irrelevant data
	Including irrelevant data in the dataset can impact the accuracy of the model. 
	This can be addressed through techniques such as feature selection, which involves selecting only 
	the most relevant features, or removal of irrelevant data from the dataset. 
[Irrelevant data link](https://github.com/eugene-kbl/Predicting-Student-Dropout-and-Academic-Success/blob/35d5d47c1b055fe8dd18e310c09a8fbaa90adac1/Project%20Files/Irrelevant_Data.ipynb)

##### Feature selection
	Following the exclusion of irrelevant data, this step involves selecting features which are the most 
	relevant features in order to improve the performance of a machine learning model. 
[Feature selection link]()

##### Data imbalance
	Data imbalance occurs when the classes in the dataset are not represented equally, which 
	can lead to biased and inaccurate results. 
	Several techniques can be used to address data imbalance, such as:
		a) random over-sampling. 
			This technique involves randomly removing samples from the majority class to balance the dataset;
		b) random under-sampling. 
			This technique involves randomly duplicating samples from the minority class to balance the dataset;
		c) synthetic minority over-sampling technique (SMOTE). 
			This technique involves generating synthetic samples from the minority class to increase 
			its representation in the dataset;
		d) class weight adjustment. 
			This technique involves adjusting the weights of the different classes during the training of 
			the classification model to give more weight to the minority class;
		e) ensemble techniques. 
			This technique involves combining multiple classification models, each trained on a different 
			subset of the data, to create a more robust and accurate model;
[Data imbalance link](https://github.com/eugene-kbl/Predicting-Student-Dropout-and-Academic-Success/blob/35d5d47c1b055fe8dd18e310c09a8fbaa90adac1/Project%20Files/Data_Imbalance.ipynb)

##### Data duplication
	Data duplication can occur when the same data is included in the dataset multiple times, which 
	can bias the model towards certain features. 
	This can be addressed through techniques such as deduplication, which involves identifying and removing duplicated data.
[Data duplication link](https://github.com/eugene-kbl/Predicting-Student-Dropout-and-Academic-Success/blob/35d5d47c1b055fe8dd18e310c09a8fbaa90adac1/Project%20Files/Duplicated_Data.ipynb)

##### Data normalization
	Data normalization is the process of scaling numerical data to a common range. 
	Failing to normalize data can impact the accuracy of the model as features with 
	larger ranges can dominate the model. 
	The following feature scaling techniques can be leveraged to address this: 
		a) standardization;
		b) mean normalization;
		c) min-max scaling;
		d) unit vector;
[Data normalization link](https://github.com/eugene-kbl/Predicting-Student-Dropout-and-Academic-Success/blob/35d5d47c1b055fe8dd18e310c09a8fbaa90adac1/Project%20Files/Data_Normalization.ipynb)

[Combined Data collection and preparation link](https://github.com/eugene-kbl/Predicting-Student-Dropout-and-Academic-Success/blob/511500a44ab9d475851f643b4d9d81e7cc1a1275/Project%20Files/Data_Collection_and_Preparation.ipynb)

### 1.2 Splitting the data:
	This step involves splitting the data into training and testing sets. 
	The training set is used to train the model, while the testing set is used 
	to evaluate the model's performance.

[Splitting the data link]()

### 1.3 Model selection and training:
	This step involves selecting a suitable algorithm(s) based on the characteristics of 
	the data and research questions. 
	Selected algorithms are then trained on the training data.

[Model selection and training link]()

### 1.4 Model evaluation:
	This step involves computing metrics to determine model's accuracy and effectiveness. 
	Several metrics can be considered for model evaluation, such as:
		a) accuracy
		b) precision
		c) recall
		d) f1 - score
		e) ROC curve 
		f) AUC 

[Model evaluation link]()

### 1.5 Model tuning and refinement:
	This step involves analyzing the results of the model evaluation. 
	Based on the analysis, the model may need to be refined or adjusted for performance improvement. 

[Model tuning and refinement link]()



## 2 Technical Reports
### 2.1 TR1
### 2.2 TR2
### 2.3 TR3
### 2.4 TR4






