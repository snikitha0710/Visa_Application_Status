# Visa_Application_Status
This repository provides detailed information on the application status of visas, including comprehensive data analysis and the development of machine learning classification models.
# Scenario
Business communities in the United States are experiencing a high demand for human resources, with one of the ongoing challenges being the identification and attraction of suitable talent, which is crucial for maintaining competitiveness. Companies seek hardworking, skilled, and qualified individuals both domestically and internationally.

The Immigration and Nationality Act (INA) of the US allows foreign workers to come to the country on either a temporary or permanent basis. The act also safeguards US workers from negative impacts on their wages or working conditions by ensuring that employers comply with statutory requirements when hiring foreign workers to address workforce shortages. The Office of Foreign Labor Certification (OFLC) administers these immigration programs.

The OFLC processes job certification applications for employers who wish to bring foreign workers into the US and issues certifications if employers can prove that there are not enough available US workers to fill the positions at wages that meet or exceed local standards.

In FY 2016, the OFLC processed 775,979 employer applications for 1,699,957 positions, representing a nine percent increase from the previous year. With the growing number of applicants each year, reviewing every case is becoming increasingly cumbersome.

To address this, a Machine Learning-based solution is needed to assist in shortlisting candidates with a higher likelihood of visa approval. OFLC has engaged your firm, EasyVisa, to provide data-driven solutions. As a data scientist, you are tasked with analyzing the provided data and developing a classification model to:

Streamline the visa approval process.
Recommend whether to certify or deny applicants based on the factors that significantly influence the case status.
# About Dataset
The data contains the different attributes of the employee and the employer. The detailed data dictionary is given below.
case_id: ID of each visa application

continent: Information of continent the employee

education_of_employee: Information of education of the employee

has_job_experience: Does the employee has any job experience? Y= Yes; N = No

requires_job_training: Does the employee require any job training? Y = Yes; N = No

no_of_employees: Number of employees in the employer's company

yr_of_estab: Year in which the employer's company was established

region_of_employment: Information of foreign worker's intended region of employment in the US.

prevailing_wage: Average wage paid to similarly employed workers in a specific occupation in the area of intended employment. The purpose of the prevailing wage is to ensure that the foreign worker is not underpaid compared to other workers offering the same or similar service in the same area of employment.

unit_of_wage: Unit of prevailing wage. Values include Hourly, Weekly, Monthly, and Yearly.

full_time_position: Is the position of work full-time? Y = Full Time Position; N = Part Time Position

case_status: Flag indicating if the Visa was certified or denied
