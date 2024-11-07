# Travel-Insurance-Prediction-Using-Binary-Logistic-Regression
This project develops a binary logistic regression model to predict customer interest in travel insurance. Using a dataset of previous customers, the model evaluates key factors influencing purchasing decisions. Statistical analyses like chi-square, Pearson correlation, and multicollinearity tests are applied to ensure model interpretability.

### Dataset
The dataset used for this project is the `TravelInsurancePrediction.csv` dataset, available on Kaggle: 
<a href="https://www.kaggle.com/datasets/tejashvi14/travel-insurance-prediction-data">Travel Insurance Prediction Dataset</a>

### Data Features
- Age: Age of the customer.
- Employment Type: The sector in which the customer is employed.
- GraduateOrNot: Whether the customer is a college graduate or not.
- AnnualIncome: The yearly income of the customer in Indian Rupees (rounded to the nearest 50 thousand Rupees).
- FamilyMembers: Number of members in the customer's family.
- ChronicDisease: Whether the customer suffers from any major disease or condition like diabetes, high BP, asthma, etc.
- FrequentFlyer: Derived data based on the customer's history of booking air tickets on at least 4 different instances in the last 2 years (2017-2019).
- EverTravelledAbroad: Whether the customer has ever traveled to a foreign country (not necessarily using the company's services).
- TravelInsurance: Did the customer buy a travel insurance package during the introductory offering held in the year 2019 (0 = Not interested, 1 = Interested).

The target variable is the TravelInsurance, which represents the insurance purchasing decision of the customer.

### Getting Started
1. Set Up Virtual Environment (Google Colab) <br>
To get started, open <a href="https://colab.research.google.com/">Google Colab</a> and open the `Travel Insurance Prediction Using Binary Logistic Regression.ipynb` notebook from this <a href="https://github.com/tjovanessa/Travel-Insurance-Prediction-Using-Binary-Logistic-Regression/blob/main/Travel%20Insurance%20Prediction%20Using%20Binary%20Logistic%20Regression.ipynb">GitHub repository</a>. Make sure the runtime type `R` is selected instead of `Python`.
2. Install Dependencies <br>
Once the notebook is uploaded, install the required dependencies by running the code embedded in the notebook.
3. Run Analysis <br>
Upload and load the `TravelInsurancePrediction.csv` dataset. To run the analysis and build the model, simply execute the code cells in the notebook.
3. Model Results <br>
The binary logistic regression model outputs Odds Ratios, which indicate the impact of each feature on the likelihood of a customer purchasing insurance.

### Requirements
This project requires the following R packages for data manipulation, statistical analysis, and model evaluation:

`lmtest`: For statistical tests and model evaluation (e.g., likelihood ratio test, Wald test). <br>
`car`: For regression analysis and checking multicollinearity (e.g., VIF - Variance Inflation Factor). <br>
`corrplot`: For visualizing correlation matrices. <br>
`dplyr`: For data manipulation and transformation (e.g., filtering, grouping, summarizing). <br>
