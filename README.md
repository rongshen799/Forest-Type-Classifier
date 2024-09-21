**Forest Cover Type Classifier**

This project is a web application that uses machine learning to classify forest cover types based on cartographic variables.

**Features**

Predict forest cover type based on user input
Visualize the distribution of forest cover types
Display feature importance
Show pairplot of top features

**Installation**

1. Clone this repository:
Copy
```python
git clone https://github.com/yourusername/forest-classifier.git
cd forest-classifier
```
2. Install the required packages:
Copy
```python
pip install -r requirements.txt
```
3.Run the data preparation script:
Copy
```python
python prepare_data.py
```
4.Train the model:
Copy
```python
python model.py
```

**Usage**

To run the Streamlit app locally:
Copystreamlit run app.py
To run the Docker container:
Copydocker build -t forest-classifier .
docker run -p 8501:8501 forest-classifier
Then open your web browser and go to http://localhost:8501

**Project Structure**

data/covertype_full.csv: The full Covertype dataset
data/covertype_small.csv: A smaller subset of the dataset for faster processing
prepare_data.py: Script to download and prepare the dataset
model.py: Script to train and save the machine learning model
app.py: Main Streamlit application
Dockerfile: Instructions for containerizing the app
requirements.txt: List of Python dependencies

**License**

Nothing