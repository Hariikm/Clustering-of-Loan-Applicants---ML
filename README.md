# Clustering-of-Loan-Applicants---ML
This is a small project of mine were I clustered Loan applicants based on several features<br><br>

<h3>Problem Statement</h3><br><br>

You have been provided with a dataset containing information about loan applicants. Your task is to use clustering techniques to identify distinct groups or segments within the dataset based on various features. This segmentation can help in understanding different types of loan applicants and their characteristics, which can be used to develop targeted strategies and policies for loan approval.<br><br><br>

<h3>Feature Explanation:</h3> <br><br>
Loan_ID: A unique identifier for each loan applicant.<br>
Gender: The gender of the applicant (e.g., Male, Female).<br>
Married: Whether the applicant is married or not (e.g., Yes, No).<br>
Dependents: The number of dependents the applicant has (e.g., 0, 1, 2+).<br>
Education: The level of education of the applicant (e.g., Graduate, Not Graduate).<br>
Self_Employed: Whether the applicant is self-employed or not (e.g., Yes, No).<br>
ApplicantIncome: The income of the applicant.<br>
CoapplicantIncome: The income of the co-applicant, if any.<br>
LoanAmount: The amount of loan requested by the applicant.<br>
Loan_Amount_Term: The term (in months) of the loan.<br>
Credit_History: The credit history of the applicant (e.g., 1 - Good, 0 - Bad).<br>
Property_Area: The type of property area where the applicant resides (e.g., Urban, Rural, Semiurban).<br>
Loan_Status: The final status of the loan application (e.g., Approved, Not Approved).<br><br><br>

These features provide important information about the loan applicants, including their demographic details, financial information, credit history, and property area. Clustering algorithms can be applied to these features to identify groups of applicants with similar characteristics, which can aid in developing targeted loan approval strategies and understanding the factors influencing loan decisions.

<h3>Initial Data:</h3><br>

![image](https://github.com/Hariikm/Clustering-of-Loan-Applicants---ML/assets/127305068/79ec0410-1924-4c07-9e80-bb0aeb43e5f9)
<br>
This was the default data scatter plot with loan applicant Income and loan amount.<br><br>

<h3>Identifying the number of clusters</h3><br>

![image](https://github.com/Hariikm/Clustering-of-Loan-Applicants---ML/assets/127305068/357d22ea-008d-44d2-b294-43519ff0c2a8)

Now we identified the K as 3.

<br>
<h3>Final Clustered Data:</h3><br>

![image](https://github.com/Hariikm/Clustering-of-Loan-Applicants---ML/assets/127305068/9bfd72dd-94ac-4884-a439-c62537e462d2)
<br>
Here we created a new feature called total income and then made clusters with that and plotted it with loan amount.
