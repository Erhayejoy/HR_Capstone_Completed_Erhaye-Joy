# HR_Capstone_Completed_Erhaye-Joy


This project delivers a dynamic, data-driven HR Analysis Dashboard designed to track workforce demographics, salary distributions, performance metrics, and departmental turnover trends.
The project transforms raw employee records into an interactive, executive-level reporting tool to enable strategic, data-backed human resource decisions.
## *Data Cleaning Methodology*
The raw data underwent a rigorous data cleaning and preparation process using specialized Excel functions,creatined new columns to ensure absolute data integrity.
### *Functions and Techniques Used*
 * *Full Name:* Flash Fill was used
 * *Dept Code :* UPPER & TRIM 
 * *Department :* VLOOKUP 
 * *Hiring Date :* Text to Columns
 * *Performance Band :* IF Function
 * *Eligibility Bonus :* IF Function
 * *Employment Status :* PROPER & TRIM
 * *Years of Service  :* DATEDIF- (DATEDIF(Hiring_Date, Today(),"Y")
  * *Salary Imputation:* Average Salary- Identified missing or null records in the salary fields and populated them using the calculated average salary metric to maintain statistical integrity without distorting overall budget trends.

  
## *Key observations & Analytical Findings*
The pivot analysis and visualization modules revealed several core business findings across the 150 total active and inactive employees for 9 years since 2015 - 2023.
 * *Financial Footprint:* n the 9 years, the organization manages a total payroll of *₦12,540,590* with an overall average employee salary of *₦83,604. Bonus payouts currently stand at *₦332,828**.
 * *Departmental Distributions:* * The *Finance* department maintains the highest average salary tier at *₦87,173.6*, while tracking the lowest overall headcount (17).
   * *Information Technology* commands the largest headcount presence (36 employees).
 * *Attrition Risk:*
   * The overall organizational workforce status sits at 77.33% Active,16.00% Left, and 6.67% Resigned.
   * The *Information Technology* department presents a critical operational vulnerability, showing a disproportionate *24.00% attrition rate*. Finance holds the lowest attrition rate at 11.33%.
 * *Performance & Compensation Alignment:*
   * The highest bonus amounts are concentrated among employees who are top-tier performers under *Outstanding* performance band while employee under *Needs improvement* performance Band do not reveive any bonus.

   
    ## *The Insight:*
   Hiring trends across the years (2015–2023) show strict stability, consistently fluctuating tightly between *15 and 19 new hires per year* (peaking at 19 in 2017 and sitting at 17 in 2023).



 * *Business Implication:* While predictable recruitment makes HR planning easier, a completely flat hiring line across nearly a decade suggests the company is hiring primarily to replace lost staff rather than expanding or scaling its operations
