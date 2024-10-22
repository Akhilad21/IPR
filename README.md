INSTRUCTIONS:
We use the DEAP Dataset, a public dataset for emotion analysis using physiological signals. The dataset consists of:
•	EEG Signals: Recorded from 32 electrodes at 128 Hz.
•	EMG and EOG Signals: Recorded alongside EEG to provide additional features for emotion classification.
DEAP dataset is available at:
https://drive.google.com/file/d/1DBcROSuz5yxvtiuAgt-nfe_rXZVBRVFz/view?usp=sharing
Requirements
To run this project, you need to install the following dependencies:
•	Python 3.6+
•	TensorFlow 2.6.0+
•	NumPy
•	Pandas
•	Scikit-learn
•	SciPy
Install all the dependencies using the following command: 
pip install -r requirements.txt
Before running the model, the EEG signals need to be preprocessed to extract the Power Spectral Density (PSD), and the EMG and EOG signals need to be processed to extract statistical features.
The preprocessing script is included in the main training file and will run automatically before training.
Run Training and evaluate the model
Run the code using Google Colab, upload the dataset to your Google Drive and mount the drive.
Run Training and evaluate the model
