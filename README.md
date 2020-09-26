# Predicting-the-product-life-cycle-of-songs-on-radio-
Predicting the product life cycle of songs on radio

This project was developed to provide the radio monitoring company WARM with a new forecasting
tool that provides a competitive advantage in the music industry. The solution is a machine
learning algorithm that can predict the future radio plays of songs in up to three months after
only using one and two months of historical data. A small dataset is used containing songs that
have different types of development in radio plays. The best results were achieved using a k-d
tree to calculate the most similar songs to the test songs, and use a Random Forest model to
forecast radio plays. An 82,78% and 83,44% accuracy is achieved for the two time periods
respectively. This explorative research lead to over 4500 test metrics to find the best combination
of models and preprocessing techniques. Other algorithms tested are KNN, SVR, MLP, CNN and
LSTM. The features only consist of performance data such as daily radio plays and uses no musical
features in the predicting. The solution is able to predict different types of songs that exists in the
product portfolio of record labels. It provides record labels with completely new information that
can be added in their decision-making process of which artists to prioritize.
