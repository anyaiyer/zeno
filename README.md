# Zeno - A quantum-inspired predictor of Parkinson’s disease built on a diverse, multimodal dataset

This study focuses on Parkinson's Disease (PD) detection based on 3 features - gait, demographics, and voice. 
We base the analysis on samples from mPower’s Parkinson’s research study. 
To construct a high-performing model, we consider advancements in quantum computing which have allowed for the creation of quantum support vector machine (SVM) kernels that can be represented in high-dimensional Hilbert space, capturing complex relationships between inputs.

## Data Availability 
All data used within this study can be publicly found through the [mPower Research Study database](https://www.synapse.org/Synapse:syn4993293/wiki/247859).
It is required that individuals attain proper authorization to gain full access to this publicly available data.
The data specifically contains information regarding various tests/exercises performed by the mPower Research study including vocal tests with short vowel sounds, memory tests, tapping speed, acceleration & gait movements, as well as demographic information (age, gender, health history, smoking history, etc). 

## Data Preprocessing
A normalized version of the mPower Dataset is located within this repository which was used to train the qSVM and various classical machine learning models. 
A baseline ResNet50 model was trained purely on the vocal data to better understand the impact vocal biomarkers have on PD detection. This ResNet50 model can be found on our [website](https://redevs-zeno.vercel.app/), used for solely testing/prototyping purposes. 
