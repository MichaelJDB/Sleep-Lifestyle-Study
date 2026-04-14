# Credit Card Churn Analysis and Data Cleaning

**Credit Card Customer Churn Analysis** is a comprehensive data analysis tool designed to streamline data exploration, analysis, and visualisation. The tool supports multiple data formats and provides an intuitive interface for both novice and expert data scientists.

## Dataset Content
* The Credit Card dataset contains just over 10,000 customers' data like Age, Gender, Income category, card category, etc. This dataset can be accessed from the following link: https://www.kaggle.com/datasets/sakshigoyal7/credit-card-customers/data


## Business Requirements
A bank manager is concerned about increasing customer churn in their credit card services. The goal is to assess which customers are likely to churn using customer data and develop strategies to improve retention.


## Hypothesis and how to validate?
## Hypothesis 1:
Old customers with higher credit limits are less likely to attrite compared to younger customers with lower credit limits.

### Result:

Attrition is more common among younger customers with lower credit limits.
Older customers with higher limits tend to remain active.

# Hypothesis 2:
Customers with higher credit limits tend to be older, reflecting a possible correlation between age and financial trustworthiness or creditworthiness.

### Result:

Older customers are more likely to have higher credit limits
Younger customers are clustered around lower credit limits, suggesting that there is a limited financial history.

# Hypothesis 3:
Lower-income customers exhibit higher total transaction amounts, suggesting greater reliance on credit card usage.

### Result: 

The customers earning less than $40k have the highest total transaction amount, even more than higher-income groups. This could mean that lower-income groups may use their credit cards more often as they may rely on them for everyday expenses. 

# Hypothesis 4:
Customers with Blue credit cards are more likely to be retained than those with Silver, Gold, or Platinum cards.

### Result:

Blue cardholders are more likely to stay with the bank than customers with Silver, Gold, or Platinum cards. The Blue card category has teh highest number of existing customers and the lowest number of attrited.

# Hypothesis 5: 
Card category affects customer retention, with Blue and Silver cards showing loyality than Platinum and Gold. 

### Result: 

Blue and Silver cardholders have the highest retention rates, while Platinum has the lowerst. This supports the idea that card types affect customer loyalty, with Blue and Silver cards being more effective at keeping customers.

## Project Plan
* Outline the high-level steps taken for the analysis.
* How was the data managed throughout the collection, processing, analysis and interpretation steps?
* Why did you choose the research methodologies you used?

## The rationale to map the business requirements to the Data Visualisations
* List your business requirements and a rationale to map them to the Data Visualisations
* The first visualisation is a scatter chart which shows the credit limit for the customer ages which helps to see how common attrited customers there are which helps the bank to work towards targetting their other customer ages.
* The second visualisation is a violin chart that shows the credit limit for customer ages which supports the bank by showing the main ages with the highest credit limits which can suggest they are have more expenses or rely on the card day-to-day.
* The third visualisation is a bar chart that shows the total transaction amount for each income category. This helps the bank  as they can see who is spending the most on their card which is the customers in the "Less than $40k" and the bank can focus on them and potentially offer them better services or benefits. 
The fourth visualisation is a double bar chart which shows the customer count for each card category. The Blue card has the most customers for this that shows the bank which card type keep the customers loyal, so it can improve retention and focus on their most succesful product (Blue card).
The fith visualisation is a bar chart that shows retention rates by card category. It helps the bank identify in more detail which card types are keeping customers loyal. 

## Analysis techniques used
Extracting, cleaning and altering data in Jupyter notebooks. 
Visualisations: bar charts, scatter plots and violin charts.

I did find myself limited to what visualisation I could use with the data as there wasn't much range to choose from that would be benefitial. I did take alternative approaches by using a the same visualisation but to produce a different outcome with one other variable in the data.


## Ethical considerations
I did complete some data privacy with column to anonymise it for the customer by removing the names as this type of data is financial which is highly sensitive and could cause complications if not obeying the rules of any data regulations like GDPR.

## Planning: 

To make sure I was on track with the work on the data I created a project board to help see what I need to complete and what I have done. https://github.com/users/MichaelJDB/projects/3 

## Development Roadmap
I did encounter a few issues when coding the analysis with getting my code to run. Some of the libaries weren't working so I had use Copilot to help me find a resolution. Also, I had encountered some issues with getting the visualisations to work but the fix was simple by making sure I was using the correct library in the code.


## Main Data Analysis Libraries
* Pandas 
* Numpy
* Seaborn
* Plotly
* Matplotlib


## Credits 
* The Code Institute LMS which provided me the knowledge on how to use the libraries necessary for this project as well teaching me to create visualisation from the data I have worked with. 
* Microsoft Copilot which has supported with me fixing errors along the way and teaching me to get my visualisations to work.
* Kaggle which provided me with the dataset to create the project.

## Acknowledgements (optional)
* Special Thanks to my work coaches: Emma Lamont, Spencer Barriball and Mark Briscoe for the support and knowledge they have given me so far! 
* Honourable mention of my friends and family that supported me with my well being and encouraging me to keep going. 