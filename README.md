Airline Passenger Satisfaction Prediction
Overview

This project focuses on predicting passenger satisfaction for an airline based on various service features. The dataset contains information about passengers' experiences, including factors like flight distance, in-flight services, and customer type. The goal is to build a binary classification model to predict whether passengers are neutral/dissatisfied or satisfied.


Dataset
The dataset used in this project is divided into training and testing sets, which are combined for analysis. The dataset includes 25 features such as:

Gender

Customer Type

Age

Type of Travel

Class

Flight Distance

Inflight wifi service

Departure/Arrival time convenient

Ease of Online booking

Gate location

Food and drink

Online boarding

Seat comfort

Inflight entertainment

On-board service

Leg room service

Baggage handling

Checkin service

Inflight service

Cleanliness

Departure Delay in Minutes

Arrival Delay in Minutes

satisfaction

The target variable is satisfaction, which is a binary classification problem with two classes: neutral or dissatisfied and satisfied.



Project Structure
The project is structured as follows:



Data Preparation:

Load and combine the training and test datasets.

Handle missing values and perform data cleaning.

Transform categorical columns into numeric representations.


Exploratory Data Analysis (EDA):

Summarize the distribution of attributes for the two classes.

Visualize the distribution of the target variable.

Analyze the relationship between different features and passenger satisfaction.


Model Building:

Split the dataset into training and testing sets.

Build and evaluate machine learning models (e.g., Logistic Regression, Random Forest, Gradient Boosting).

Perform hyperparameter tuning to optimize model performance.


Model Evaluation:

Evaluate model performance using metrics such as accuracy, precision, recall, and F1-score.

Generate confusion matrices and ROC curves to assess model performance.


Conclusion:

Summarize the findings and insights from the analysis.

Discuss the best-performing model and its implications for the airline.


Requirements
To run the code in this project, you will need the following Python libraries:

pandas

numpy

matplotlib

seaborn

scikit-learn

You can install these libraries using pip:

bash
Copy
pip install pandas numpy matplotlib seaborn scikit-learn
Usage
Clone the repository:

bash
Copy
git clone https://github.com/stefanosmanios/airline-passenger-satisfaction.git
Navigate to the project directory:

bash
Copy
cd airline-passenger-satisfaction
Run the Jupyter notebook:

bash
Copy
jupyter notebook AirlinePassengerSatisfaction.ipynb
Results
The best-performing model achieved an accuracy of 20% on the test set. The model can be used by the airline to identify areas for improvement and enhance overall passenger satisfaction.

Contributing
Contributions are welcome! Please feel free to submit a pull request or open an issue if you have any suggestions or improvements.

License
This project is licensed under the MIT License. See the LICENSE file for details.

Acknowledgments
The dataset used in this project is sourced from https://www.kaggle.com/datasets/teejmahal20/airline-passenger-satisfaction/data.
