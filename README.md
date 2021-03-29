System requirements:
Python 3.7.1
Tensorflow 2.2.0
PyTorch 1.2.0
GPU - NVIDIA GeForce RTX 2080

JupyterNotebook: 6.0.3
===============================Data=============================================
All data initial files are in data folder.
	AirQuality-
	data->air->initial
	MIMIC-
	data->mimic->initial

===============================Data Preprocessing===============================
Run data_preporcessAir.ipynb for preprocessing AirQuality data
Run data_preporcessMimic.ipynb for preprocessing AirQuality data
	All data preprocessed files are in data folder.
	AirQuality-
	data->air->preprocess
	MIMIC-
	data->mimic->preprocess
	
===============================Bi-GAN=============================================
To run Bi-GAN for EHR dataset - 
	Run "biGan/main_ganOrig.ipynb"
	For training model-
		Set train=True

	For Imputation Testing model-
		Set evalImp=True
		Set missingRate=10 or 20 or 30 or 40 or 50

	For Prediction Testing model-
		Set evalPred=True
		Set pred_len=8 or 7 or 6 or 5

===============================BRITS-I=============================================
BRITS-I
To run BRITS-I for EHR dataset - 
	Run "britsI/main - original.ipynb"
	For training model-
		Set train=True

	For Imputation Testing model-
		Set evalImp=True
		Set missingRate=10 or 20 or 30 or 40 or 50

	For Prediction Testing model-
		Set evalPred=True
		Set pred_len=8 or 7 or 6 or 5

===============================Baseline=============================================
Baseline
To run Bi-GAN for EHR dataset - 
MICE -
Run "baseline/MICE.ipynb"
	Input Arguments to be set -
	
	For Imputation Testing model-
		Set imp=True
		Set missingRate=10 or 20 or 30 or 40 or 50
	
	For Prediction Testing model-
		Set pred=True
		Set pred_len=8 or 7 or 6 or 5

KNN-
Run "baseline/knn.ipynb"
	Input Arguments to be set -
	
	For Imputation Testing model-
		Set imp=True
		Set missingRate=10 or 20 or 30 or 40 or 50
	
	For Prediction Testing model-
		Set pred=True
		Set pred_len=8 or 7 or 6 or 5

MEAN-
Run "baseline/mean.ipynb"
	Input Arguments to be set -
	
	For Imputation Testing model-
		Set imp=True
		Set missingRate=10 or 20 or 30 or 40 or 50
	
	For Prediction Testing model-
		Set pred=True
		Set pred_len=8 or 7 or 6 or 5

===============================Bi-GAN Components=============================================
Bi-GAN without Discriminator=============================================
To run biWgan for EHR dataset - 
	Run "biWgan/main_gan.ipynb.ipynb"
	For training model-
		Set train=True

	For Imputation Testing model-
		Set evalImp=True
		Set missingRate=10 or 20 or 30 or 40 or 50

	For Prediction Testing model-
		Set evalPred=True
		Set pred_len=8 or 7 or 6 or 5

Bi-GAN without Lambda=============================================
To run lambda for EHR dataset - 
	Run "lambda/main_ganLambda.ipynb"
	For training model-
		Set train=True

	For Imputation Testing model-
		Set evalImp=True
		Set missingRate=10 or 20 or 30 or 40 or 50

	For Prediction Testing model-
		Set evalPred=True
		Set pred_len=8 or 7 or 6 or 5



NOTE: Change path of files as required
