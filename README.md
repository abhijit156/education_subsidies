# Targeted subsidies for public school students
In this project, I identified students at high risk of dropping out due to socio-economic conditions using Government of India's National Sample Survey data. To achieve this, I implemented a Naive Bayes classifier on current public school students data. After identifying target students (above a certain threshold of dropout probability), I used k-nearest neighbors regression to compute a subsidy amount for these students.

# Datasets used (And corresponding block in NSS data dictionary)
* Household_identification_input (Block 1)
  * Contains identification data for ~7000 households
* Household_characteristics_input (Block 3)
  * Contains socio economic variables of each household such as religion, household size, social group, distance from  nearest school, household consumer expenditure 
* Household_members_input (Block 4)
  * Contains particulars of all members within each household such as sex, age, relation to head, marital status, education level
* Particulars_of_dropouts_input (Block 7)
  * Contains particulars of all students who have dropped out from education
* Current_students_input (Block 5)
  * Contains educational expenditure and other details of all students currently in the education system 
  
 # Further scope
 Although this project currently only considers primary and secondary levels of education, it can easily be extended to consider higher and technical education based on the definitions provided in the data dictionary
