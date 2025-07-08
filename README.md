# Predicting-Potential-Customers-for-Travel-Insurance.

1. Business Request:

- To build a predictive model that helps travel insurance companies identify potential customers based on demographic characteristics, income, health status, and travel behavior. This model will support businesses in designing targeted marketing strategies, optimizing resource allocation, and increasing the likelihood of insurance purchases.

2. Main Idea:

- This project applies data mining techniques to build a predictive model that identifies individuals likely to purchase travel insurance. The model is trained on a dataset containing various customer attributes, including:

Age: Customer’s age (25–35), which may influence travel frequency and risk perception.

Employment Type: Whether the customer works in the private or government sector, which may reflect income stability and travel habits.

GraduateOrNot: Educational background, which can correlate with awareness of insurance benefits.

Annual Income: Annual earnings, a key factor in affordability and likelihood of purchasing insurance.

Family Members: Number of people living with the customer, possibly affecting travel decisions and insurance needs.

Chronic Disease: Health condition status, which may increase the perceived need for travel insurance.

Frequent Flyer: Whether the customer frequently books flights, indicating travel habits.

Ever Travelled Abroad: Past international travel experience, which may increase awareness and demand for insurance.

Travel Insurance (Target Variable): Indicates whether the customer purchased travel insurance in a 2019 promotional campaign.

- By analyzing these variables using machine learning models such as Logistic Regression, Neural Networks, and Decision Trees, the project aims to accurately predict potential buyers and support insurance companies in targeting the right customer segments.

3. Tools and Techniques:

Tool used: SPSS Clementine 12.0 was utilized for the entire data analysis and modeling process.

Data Preprocessing:

- Duplicate records and rows with missing values were removed to ensure data quality.

- All variables were normalized to a common scale (0–1) to minimize bias caused by differing value ranges.

- Downsampling was applied to balance the dataset and enhance model performance.

Model Development:

- Three machine learning models were built: Logistic Regression, Neural Networks, and Decision Trees.

Model Evaluation:

- The models were compared based on their accuracy on the test set.

- The Neural Network model achieved the highest accuracy at 80.61%, making it the most effective for predicting travel insurance purchases.
