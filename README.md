## Project_LC

### Loan Applicant Creditworthiness Assessment

This repository contains work on the classification problem in supervised machine learning. The goal of this machine learning project is to improve *Lending Club's* lending decision-making process. The primary goal of the project is to determine the creditworthiness of potential loan applicants and, based on this assessment, make informed decisions regarding loan disbursement. It will help the company in distinguishing between low-risk and high-risk applicants.

### Project Description

*Lending Club*, a *peer-to-peer* lending entity, acts as an intermediary linking borrowers and investors through an online platform. The platform caters to individuals in need of personal loans, ranging from $500 to $35,000. Borrowers receive the full loan amount, deducting the initial fee remitted to the company. On the other side, investors purchase promissory notes supported by personal loans and compensate the Lending Club through a service fee.

### Dataset and additional files

For this project, data related to loans facilitated by *Lending Club* in the years 2007-2011 was employed. Each loan within the dataset is tagged with an indicator of its ultimate outcome, falling into categories of either *"Fully Paid"* or *"Charged Off"* in the *"loan_status"* column. The dataset is accompanied by a comprehensive variable description file ("LCDataDictionary.csv") and a detailed explanation of one of the columns in the "FICO Score ranged.pdf" document. The core dataset itself is stored in the "LoanData.csv" file. The repository also includes data files (.csv format), which were modified at individual stages of the project, as well as a Heatmap (.png format) and a file containing geographical data (USA.xlsx). 

### Methodolegy

The project was organized into 4 scripts written in Python:

1. **Data Processing:** Data cleaning, preparation, general preprocessing and statistics.
2. **Exploratory Data Analysis:** Identifying relevant features that have the most influence on an applicant's creditworthiness.
3. **Feature Engineering:** Finding dependencies between features and creating new ones. Handling missing values and encoding categorical variables.
4. **Modeling:** Developing machine learning models, such as logistic regression, decision trees, random forests, or neural networks, to predict loan repayment probabilities. Selection of the best models and their optimization.

### Additional Information

**Project_LC** was created as part of a Data Science Bootcamp and reflects various modifications made during the learning process of Data Science. These include programming in Python, implementing various useful libraries, learning Git and GitHub, and many others.