# Diabetes_Prediction

Install Python 3.14, then verify the installation:
    Press Windows + R, type `cmd`, and press Enter.
    In Command Prompt, run:
        python --version

Open Visual Studio Code and install the required Python extensions.

Go to File → New Window → Open Folder, then select the `Diabetes_Prediction` folder.

Open the terminal and run:
    py -m venv venv
    venv\Scripts\Activate
    pip install -r requirements.txt

Run the application:
    streamlit run Diabetes_Prediction.py

On the output page, Fill the options and run the prediction to view the result.

## ⚠️ Important Files – Large File Limitation

Some important trained model files used by this project
could not be uploaded to this GitHub repository because of GitHub's
file-size limitations.

These files are required for the complete project and are kept separately.

### Important files not included in this repository

- `Diabetes_Prediction_Model.pkl`

The trained model file is required by the Diabetes Prediction application
for making predictions.

The file is **not deleted or unnecessary**; it is excluded from GitHub
only because of its large file size.

The dataset, preprocessing code, Jupyter Notebook, Python application,
scaler, reports, and other supporting files are included in this repository.

The complete project can be reproduced using the included
`Diabetes_Prediction.ipynb` notebook and the required dataset.

> **Note:** The large trained model file can be provided separately if required.
