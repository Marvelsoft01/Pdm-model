Predictive Maintenance ML model in Python for Remaining Useful Life (RUL) prediction, with an interactive Streamlit interface.

Features:
1. End-to-end predictive maintenance pipeline.
2. Streamlit dashboard for easy interaction with predictions.
3. Custom training support with your own machine sensor data.


Installation:
Clone the repository and install dependencies:


git clone https://github.com/Marvelsoft01/Pdm-model.git
cd pdm-rul
pip install -r requirements.txt



Running the App:
streamlit run app.py




Training with Your Own Data:
This project comes with a sample model for demonstration. For real-world use, you must retrain the model on your own sensor data.
Prepare your dataset in CSV format. It should include:
Sensor readings (features).
Remaining Useful Life (RUL) values or failure labels (target).



Retrain the model using the training script:
python train.py --data your_dataset.csv


          
Notes:
Model performance depends heavily on the quality and coverage of your machine data.
The sample model is only for demonstration and not intended for production.
