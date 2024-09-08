# IPL Win Predictor

This project is an IPL (Indian Premier League) win predictor app built using **Streamlit**. The app takes into account various match conditions such as the batting team, bowling team, host city, target, current score, overs completed, and wickets out, and predicts the probability of the batting team's victory using a pre-trained machine learning model.

## Table of Contents
- [Overview](#overview)
- [How It Works](#how-it-works)
- [Installation](#installation)
- [Usage](#usage)
- [Model](#model)
- [Contributing](#contributing)


## Overview
The IPL Win Predictor app helps predict the outcome of an IPL match in real-time by calculating the probability of the batting team winning the game. It leverages a pre-trained machine learning model that is trained on historical IPL match data. 

## How It Works
1. The user selects the batting and bowling teams.
2. The user selects the host city of the match.
3. The user inputs the target, current score, overs completed, and wickets out.
4. The app calculates various factors such as runs required, balls remaining, current run rate (CRR), and required run rate (RRR).
5. The app uses these inputs to predict the winning probability for both the batting and bowling teams.

## Installation
To run the IPL Win Predictor locally, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/Aayush-1803/IPL-Match-Prediction.git
   ```

2. Install the required Python packages:

   ```bash
   pip install -r requirements.txt
   ```

3. Run the Streamlit app:

   ```bash
   streamlit run app.py
   ```

## Usage
Once the app is running, follow these steps:
1. Select the batting and bowling teams.
2. Select the city where the match is being played.
3. Enter the target score, current score, overs completed, and wickets lost.
4. Click on the "Predict Probability" button to get the winning probabilities of both teams.

## Model
The model is trained using historical IPL match data. It uses features such as the batting team, bowling team, match location, runs left, balls left, wickets in hand, current run rate, and required run rate to predict the probability of winning for the batting team.

The model is stored as a pickle file (`pipe.pkl`) and is loaded into the app to make predictions.

## Contributing
Contributions are welcome! Feel free to open issues, submit pull requests, or suggest features to enhance the IPL Win Predictor app.

