# **Personalizing Email for efficient advertisement in the field of marketing**

## **Overview**
*The "Personalized Marketing Campaign" project aims to target specific customers with tailored email offers based on their shopping behavior and preferences. The project utilizes Python programming language and various data processing libraries to achieve this.*

## **Visualization**
![Trend Graph](https://github.com/shabi340/Email-Personalization/assets/68024510/2babe091-9be6-4b08-9db4-10155a43df48)


## **Tools and Libraries Used**
- Python
- pandas (for data manipulation)
- matplotlib (for data visualization)
- seaborn (for statistical data visualization)
- random (for randomization)
- datetime (for date handling)

## **How to Run the Project**
- *Clone the Repository:* git clone https://github.com/your-username/Personalized-Marketing-Campaign.git
- *Navigate to the Project Directory:* cd Personalized-Marketing-Campaign
- *Install Dependencies:* Ensure you have Python installed. Then, install the required libraries:
- - pip install pandas
  - pip install matplotlib
  - pip install seaborn
- *Execute the main Python script:* python main.py

## **Brief Explanation of Each Code Section**
1. *Load and Preprocess Datasets:* item_list.csv and shopping_trends.csv are loaded and processed using the pandas library.
2. *Convert Season and Frequency:* Seasonal and frequency data are mapped to numeric values for easier analysis.
3. *Apply Filters for Eligible Customers:* Two sets of filters are applied to select eligible customers based on specific criteria.
4. *Determine Current Season:* The current month is obtained, and based on it, the current season is determined (Spring, Summer, Fall, Winter).
5. *Generate Personalized Email Content:* Personalized email content is generated for eligible customers. This includes salutation, body text, and closing, all customized with the customer's name and a randomly recommended product.
6. *Save Email Content Data:* The generated email content data is stored in a structured format (CSV) for future use in marketing campaigns.
