# Travel-Insurance-Prediction-Using-Binary-Logistic-Regression
This project develops a binary logistic regression model to predict customer interest in travel insurance. Using a dataset of previous customers, the model evaluates key factors influencing purchasing decisions. Statistical analyses like chi-square, Pearson correlation, and multicollinearity tests are applied to ensure model interpretability.

### Dataset
Dataset yang digunakan dalam proyek ini adalah TravelInsurancePrediction.csv, yang dapat diunduh dari Kaggle:
<a href="https://www.kaggle.com/datasets/tejashvi14/travel-insurance-prediction-data">Travel Insurance Prediction Dataset</a>

### Data Features
- Age: Age Of The Customer
- Employment Type: The Sector In Which Customer Is Employed
- GraduateOrNot: Whether The Customer Is College Graduate Or Not
- AnnualIncome: The Yearly Income Of The Customer In Indian Rupees (Rounded To Nearest 50 Thousand Rupees)
- FamilyMembers: Number Of Members In Customer's Family
- ChronicDisease: Whether The Customer Suffers From Any Major Disease Or Conditions Like Diabetes/High BP or Asthama, etc
- FrequentFlyer: Derived Data Based On Customer's History Of Booking Air Tickets On Atleast 4 Different Instances In The Last 2 Years (2017-2019)
- EverTravelledAbroad: Has The Customer Ever Travelled To A Foreign Country (Not Necessarily Using The Company's Services)
- TravelInsurance (Target): Did The Customer Buy Travel Insurance Package During Introductory Offering Held In The Year 2019 (0 = Not tertarik, 1 = Interested)

### Getting Started
1. Install Dependencies <br>
Make sure you have Python installed. Then, create a virtual environment and install the necessary dependencies.
2. Running the Script <br>
To run the analysis and build the model, simply execute the `python travel_insurance_prediction.py` script.
3. Model Results <br>
The binary logistic regression model outputs Odds Ratios, which indicate the impact of each feature on the likelihood of a customer purchasing insurance.

### Requirements
This project requires the following R packages for data manipulation, statistical analysis, and model evaluation:

`lmtest`: For statistical tests and model evaluation (e.g., likelihood ratio test, Wald test). <br>
`car`: For regression analysis and checking multicollinearity (e.g., VIF - Variance Inflation Factor). <br>
`corrplot`: For visualizing correlation matrices. <br>
`dplyr`: For data manipulation and transformation (e.g., filtering, grouping, summarizing). <br>
