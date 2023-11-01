# IBM Naan Mudhalvan Artificial Intelligence<br>
# Project - 10: Market Basket Analysis 

<a href="https://ibb.co/M9QS7tY"><img src="https://i.ibb.co/XVMLtKh/market.jpg" alt="market" border="0"></a>

## Problem Statement

Unveiling Customer Behaviour through Association Analysis: Utilize market basket analysis on the provided dataset to uncover hidden patterns and associations between products, aiming to understand customer purchasing behaviour and identify potential cross-selling opportunities for the retail business.<br>

Dataset for this project on [Kaggle](https://www.kaggle.com/datasets/aslanahmedov/market-basket-analysis).

## Market basket analysis with Apriori algorithm

The retailer wants to target customers with suggestions on itemset that a customer is most likely to purchase. I was given dataset contains data of a retailer; the transaction data provides data around all the transactions that have happened over a period of time. Retailer will use result to grove in his industry and provide for customer suggestions on itemset, we be able increase customer engagement and improve customer experience and identify customer behavior. I will solve this problem with use Association Rules type of unsupervised learning technique that checks for the dependency of one data item on another data item.

## Introduction
Association Rule is most used when you are planning to build association in different objects in a set. It works when you are planning to find frequent patterns in a transaction database. It can tell you what items do customers frequently buy together and it allows retailer to identify relationships between the items.

An Example of Association Rules
Assume there are 100 customers, 10 of them bought Computer Mouth, 9 bought Mat for Mouse and 8 bought both of them.

bought Computer Mouth => bought Mat for Mouse
support = P(Mouth & Mat) = 8/100 = 0.08
confidence = support/P(Mat for Mouse) = 0.08/0.09 = 0.89
lift = confidence/P(Computer Mouth) = 0.89/0.10 = 8.9
This just simple example. In practice, a rule needs the support of several hundred transactions, before it can be considered statistically significant, and datasets often contain thousands or millions of transactions.

## Strategy
- Data Import
- Data Understanding and Exploration
- Transformation of the data 
- Running association rules
- Exploring the rules generated
- Filtering the generated rules
- Visualization of Rule

## Project Team:
1) Name: J B Mugundh<br>
   Register Number: 2021503524<br>
   Email-id: mugundhjb@gmail.com<br><br>

2) Name: Priyadarshni V<br>
   Register Number: 2021503538<br>
   Email-id: darshnipriya937@gmail.com<br><br>

3) Name: Padmaja H<br>
   Register Number: 2021503034<br>
   Email-id: hapadmaja@gmail.com<br><br> 

4) Name: Latha Sri SA<br>
   Register Number: 2021503518<br>
   Email-id: lathasrisakthivel114@gmail.com<br><br>

5) Name: Sandhiya S<br>
   Register Number: 2021503552<br>
   Email-id: sandhiya.949@gmail.com<br><br>

## How to Run

1. Clone this repository to your local machine.

   ```bash
   git clone https://github.com/vijaisuria/au-sap-website.git
   ```

2. Open the project directory in your preferred code editor (Visual Studio Code / Google Colab / Jupyter Notebook).

3. Download the data set from [Kaggle](https://www.kaggle.com/datasets/aslanahmedov/market-basket-analysis).

4. Change the path for dataset.

5. Run the data cells and visualize the results.

## Contributing
1. Fork the project.
2. Create your feature branch: git checkout -b feature/your-feature
3. Commit your changes: git commit -m 'Add some feature'
4. Push to the branch: git push origin feature/your-feature
5. Submit a pull request.


## Acknowledgments
Special thanks to the open-source community for the amazing tools and libraries that make projects like this possible.<hr>

Thank you for visiting the IBM Naan Mudhalvan Artificial Intelligence Project on Market Basket Analysis! We hope you find it informative 😃<br> 
For any queries, feel free to contact [Project Team](#project-team)

