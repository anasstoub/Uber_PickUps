# Uber Pickups in NYC

This is a Streamlit app that visualizes Uber pickups in New York City. The data is from September 2014 and is available [here](https://s3-us-west-2.amazonaws.com/streamlit-demo-data/uber-raw-data-sep14.csv.gz).

## How to Run the App

1. Clone this repository
2. Install the required packages: `pip install -r requirements.txt`
3. Run the app: `streamlit run uber_pickups.py`

## About the App

The app allows you to visualize the number of Uber pickups by hour and to view the location of pickups on a map for a selected hour. You can also filter the data by hour using a slider.

## Packages Used

- streamlit
- pandas
- numpy

## File Structure

- `uber_pickups.py`: the main Python file containing the Streamlit app
- `README.md`: this file
- `requirements.txt`: the list of required Python packages

## Note
- streamlit app tutorial for practice
- This app was created for educational purposes only.
