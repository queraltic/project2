
![mental](./Users/queraltiglesias/Desktop/Data/Projects/project-2/project2/images/worstemotionalhealth.png)

**1. Problem Statement**
**2. Data used**
**2.1 Cleaning the data set**
**3. Analysis and conclusions**
**4. Web Scrapping**
**5. Conclusion**

**1. Problem Statement**
In this project, I merged data from Mentall Illness Data in work Tech and GBP of countries to create a dataframe to relation the GBP to the Country

**2. Data**
 https://www.kaggle.com/datasets/osmi/mental-health-in-tech-surveyContent

self_employed: Are you self-employed?

family_history: Do you have a family history of mental illness?

treatment: Have you sought treatment for a mental health condition?

work_interfere: If you have a mental health condition, do you feel that it interferes with your work?

no_employees: How many employees does your company or organization have?

remote_work: Do you work remotely (outside of an office) at least 50% of the time?

tech_company: Is your employer primarily a tech company/organization?

benefits: Does your employer provide mental health benefits?

care_options: Do you know the options for mental health care your employer provides?

wellness_program: Has your employer ever discussed mental health as part of an employee wellness program?

seek_help: Does your employer provide resources to learn more about mental health issues and how to seek help?

anonymity: Is your anonymity protected if you choose to take advantage of mental health or substance abuse treatment resources?

leave: How easy is it for you to take medical leave for a mental health condition?

mentalhealthconsequence: Do you think that discussing a mental health issue with your employer would have negative consequences?

physhealthconsequence: Do you think that discussing a physical health issue with your employer would have negative consequences?

coworkers: Would you be willing to discuss a mental health issue with your coworkers?

supervisor: Would you be willing to discuss a mental health issue with your direct supervisor(s)?

mentalhealthinterview: Would you bring up a mental health issue with a potential employer in an interview?

physhealthinterview: Would you bring up a physical health issue with a potential employer in an interview?

mentalvsphysical: Do you feel that your employer takes mental health as seriously as physical health?

obs_consequence: Have you heard of or observed negative consequences for coworkers with mental health conditions in your workplace?

**2.1 Cleaning the dataset**

Once the columns that we will later study have been selected, we will proceed to clean the data set.
The columns to be analyzed are cleaned ['supervisor','comments', 'state','Timestamp', 'self_employed',"phys_health_consequence", 'coworkers', 'mental_health_interview',
'phys_health_interview', 'mental_health_consequence', 'mental_vs_physical',
'obs_consequence'. This step has been subdivided into 2 parts: the first corresponds to a general treatment of these data, while the second is an individual cleaning of each of them. The first process consists of deleting all those rows that lack any data(nan) in the previously mentioned columns. The second is about modifying the data, to try to group it and change its type (object) to a more consistent one for later analysis. 

**3. Analysis and conclusions**
It is important to know the definition of Mental health: includes our emotional, psychological, and social well-being. It affects how we think, feel, and act. It also helps determine how we handle stress, relate to others, and make choices. Mental health is important at every stage of life, from childhood and adolescence through adulthood.
GDP by Country: GDP measures the monetary value of final goods and services—that is, those that are bought by the final user—produced in a country in a given period of time (say a quarter or a year). It counts all of the output generated within the borders of a country.
The dataset was downloaded from Kaggle.

![country](./project-2/project2/images/country.png)

The graph that could see is that USA, is the most of mental health issues in work tech, followed by distance United Kingdom

![family](./Users/queraltiglesias/Desktop/Data/Projects/project-2/project2/images/familyhistory.png)

The graph that could see that there's more Female that has background family history(mental illness on the fan¡mily), and less male that don't has family background.

![illness](./Users/queraltiglesias/Desktop/Data/Projects/project-2/project2/images/mental_illness.png)

The graph that could see that there's Country vs GDP,
US has the best GDP in the world.

![seekforhelp](.Projects/project-2/project2/images/seekforhelp.png)

The graph that could see that there's Age VS Seek for Help,there's more young people seeking for help.

**4. Web Scrapping**
 https://www.worldometers.info/gdp/gdp-by-country/

The page it scrapped, has a table with the  35 countries and GDP (in Final document has all the code that I use).

