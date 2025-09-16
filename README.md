Predictive Maintenance ML model in Python for Remaining Useful Life (RUL) prediction, with an interactive Streamlit interface.

Features:
1. End-to-end predictive maintenance pipeline.
2. Streamlit dashboard for easy interaction with predictions.
3. Custom training support with your own machine sensor data.

<br/><br/><br/><br/>
Installation:

1. git clone https://github.com/Marvelsoft01/Pdm-model.git
2. cd pdm-rul
3. pip install -r requirements.txt

<br/><br/><br/><br/>
Running the App:<br/>
streamlit run app.py



<br/><br/><br/><br/>
Training with Your Own Data <br/>

This project comes with a sample model for demonstration. For real-world use, you must retrain the model on your own sensor data.
Prepare your dataset in CSV format. It should include: <br/>

1. Machine/unit IDs
2. Cycle/time step
3. Sensor readings (features)


<br/><br/><br/><br/>

Compute Remaining Useful Life (RUL) labels using the provided script: <br/>
compute_rul.py

This will generate a new dataset with an extra RUL column.

<br/><br/><br/><br/>



Retrain the model on the labeled dataset with: <br/>
train.py 

The retrained model will be saved in the models/ directory and automatically loaded by the Streamlit app.


<br/><br/><br/><br/>
          
Notes: <br/>
Model performance depends heavily on the quality and coverage of your machine data. <br/>
The sample model is only for demonstration and not intended for production.
