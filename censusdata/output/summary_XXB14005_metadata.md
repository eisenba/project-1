# Metadata and Annotations for XXB14005 tables  
This table contains employment characteristics for enrolled 16-19 year olds in the school districts. Below you'll find descriptions for all of the fields. In this document, I use 'teen' as shorthand for '16-19 year old'. 
  
  
## Source:
US Census Bureau, American Community Survey 1 year estimates. Groups: B14005. 'SEX BY SCHOOL ENROLLMENT BY EDUCATIONAL ATTAINMENT BY EMPLOYMENT STATUS FOR THE POPULATION 16 TO 19 YEARS'. 
  
  
## Column names
These descriptions are in camel case and vary in length. For derived values, I include the formula used. In these statistics, 'not in labor force' refers to people who are not employed and not actively seeking employment. 'Unemployed' refers to people who are not employed but are seeking employment. 'In the labor force' are either people who are employed or people who are actively seeking employment.  

* TotEnrll : total count of teens enrolled in school   
* TotEnrllEmply : total count of enrolled teens that are employed
* EmplyRateEnrll : employment rate for enrolled teens 
    1. EmplyRateEnrll = TotEnrllEmply / TotEnrllLbr  
* TotEnrllUnEmply : total count of unemployed, enrolled teens  
* UnEmplyRateEnrll : unemployment rate for enrolled teens
    1. UnEmplyRateEnrll = TotEnrllUnEmply / TotEnrllLbr  
* TotEnrllLbr : total count of enrolled teens in the labor force
* LbrRateEnrll : rate of enrolled teens participating in labor force
    1. LbrRateEnrll = TotEnrllLbr / TotEnrll  
* TotEnrllNonLbr : total count of enrolled out of the labor force
* NonLbrRateEnrll :  rate of enrolled teens not participating in labor force
    1. NonLbrRateEnrll = TotEnrllNonLbr / TotEnrll
