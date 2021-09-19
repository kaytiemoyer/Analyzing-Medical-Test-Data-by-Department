# Analyzing-Medical-Test-Data-by-Department
# MSDS 670 - Data Visualization
## Project Overview
Medical data is important on multiple fronts. To providers and practitioners, it is a means of communication across differently oriented departments of medicine to help indicate a patient’s health. The patient is often seeking the information the tests can provide in order to answer concerns or fears over their physical health and status. The same data can also be focused on a financial standpoint to help hospitals and clinics determine areas of need or productivity within their departments.  

This project analyzes the data from Exact Medical Heath System laboratories form 2005 to 2014 to answer the following questions; if the number of tests run by the health system has seen an incline or decline over nine years, which department runs the highest number of tests and if this seems to correlate with the number of providers in the department, and if there is a high positive or negative result rate to the tests completed. This will all be supporting evidence to answer the research question, “is the laboratory useful to the health system it is connected to?” 

## Data
#### Source: 
The data was taken from https://drive.google.com/drive/folders/15Rg3HhRjkT3zyMgT5WBTEtvRHpPL95a4 and sourced from John Koenig's MSDS 670: Data Visualization course, through the Course Content. The file titled Lab Results was used for this project.

#### Scope: 
One medical laboratory recorded the results of over seven thousand tests through the span of a nine-year period.  
## Process
This process was completed on a Windows 10 system, with  Microsoft Excel. 
#### 1.	Retrieving, cleaning and organizing the data. 
This involved downloading the data from the given source, removing columns with unnecessary or unrelevant data in addition to removing columns with no data. The test dates originally appeared in a YYYY-MM-DDTHH:MI:SS where YYYY is the year, MM is the month, DD is the day, T is the indication of the timestamp starting, HH references the hour in military time, MI is the minute, and SS is the second that the test results were completed and recorded. An example of this is 2005-10-07T16:15:00Z, the test being completed on October 7th 2005 at 16:15. This was changed to reflect only YYYY, or the year that each test was completed in order to summarize the nine years of data. Test results were changed to a standardized form of "Positive" or "Negative", and tests were assigned to a department dependent on the type of test performed.  These were as follows; 
•	Cardiology – tests focused on the heart and cardio system such as echocardiogram and ECG. 
•	Exams – physical or mental routine exams, physical pre-screenings to other laboratory work, and surface examination of oral, ocular, and auditory senses. 
•	Hematology and Immunology – blood and body fluid analysis, protein and lipid molecule profiles, and testing for specific molecule components (STI, pap smears, etc). 
•	Computed Tomography – mammograms, magnetic resonance imaging, X-Rays, and other computer based imagery or scanning. 
 

#### 2.	Creating visualizations for analysis. 
Once the data was cleaned and organized, a combinatin of equations were used in Microsoft Excel to determine the required data for the visualizations and then to create the specific visualization required for comparison analysis. When creating Figure 1, the data focused on the total count of tests that were completed for each year, starting with 2005 and ending with 2014. Figure 2 offered a closer look at the count for the same test numbers, categorized by department in order to provide a comparison of which departments were showing positive trends of tests completed. Figure 3 depicted the total number of tests that each department completed over the nine years of study, and Figure 4 focused on the provider numbers assigned to each test to then determine how many providers were assigned to each department. This data could feasibly be used to show which departments are over-or-understaffed, and indicate hiring or cross-training needs. Figure 5 illustrated the positive versus negative test result count for each department over the nine years of study. 

#### 3.	Comparing visualizations and analysis to the hypothesis/research goal. 
Basic analysis determined that the lab experienced a slow incline on the number of tests completed. Whether this means more tests were sent to the lab from outlying hospitals and clinics, or if more patients were being seen in a connected clinic is unclear. However, the usefulness of the lab, in particular the Hematology and Immunology department, are clearly seen to be increasing over the nine years the data was collected. 

Future research into the laboratory should analyze the positive to negative test result ratio found in the departments, and determine if this is a result of the test type completed. Surveys of employee satisfaction and workloads should also be done to determine if busier departments need to be increased in order to ease strain on employed providers. Finally, examinations of practices in departments with small numbers could be completed in order to determine if the results are a lack of needed tests, or a lack of equipment to provide the tests providers require. 

## Visualizations
- Figure 1; The Number of Tests Per Year
- Figure 2; The Number of Tests Per Year by Department 
- Figure 3; Total Number of Tests Run by Department
- Figure 4; Total Number of Providers Employed by Department
- Figure 5; Comparing Positive and Negative Tests by Department
