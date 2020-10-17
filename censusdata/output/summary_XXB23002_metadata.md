# Metadata and Annotations for XXB23002 tables  
This table contains employment characteristics for 16-19 year olds in the school districts. Below you'll find descriptions for all of the fields. Instead of list each field individually, the guide shows how the field names are generated and what each component of the name means. For example, 'LATTotNonLbr' refers to the total count of Latino / Hispanic 16-19 year olds that do not participate in the labor force. In this document, I use 'teen' as shorthand for '16-19 year old'. 
  
  
## Source:
US Census Bureau, American Community Survey 1 year estimates. Groups: B23002B-B23002I. 'SEX BY AGE BY EMPLOYMENT STATUS FOR THE POPULATION 16 YEARS AND OVER'. Each group covers a different race/ethnic group.  
  
  
## Column names
General column name format: 'XXXYyyYyyYyy'  
The X's are an abbreviation for the race/ethnic group. The abbreviations are all caps and 3 characters long. The groups used by the Census have some limitations, but should be usable.  
* Abbreviation : Full name
* BLK : Black OR African American alone
* IND : American Indian and Alaska Native alone
* ASN : Asian alone
* HIP : Native Hawaiian and other Pacific Islander
* OTH : some other race alone
* WHT : White alone, not Hispanic or Lation
* LAT : Hispanic or Latino  
  
The Y's are shortened descriptions of the value. These descriptions are in camel case and vary in length. Unless explicitly noted, all values are for a specific race / ethnic group. For derived values, I include the formula used. In these statistics, 'not in labor force' refers to people who are not employed and not actively seeking employment. 'Unemployed' refers to people who are not employed but are seeking employment. 'In the labor force' are either people who are employed or people who are actively seeking employment. 
* Tot : total count of teens   
* Mil : total count of teens that are in the armed forces
* Civ : total count of teens that are in the civilian population  
    1. Civ = Tot - Mil  
* CivLbr : total count of teens in the civilian labor force  
* CivLbrRate : teen rate of labor force participation  
    1. CivLbrRate = CivLbr / Civ  
* TotNonLbr : total count of teens not in the labor force
* TotNonLbrRate : teen rate of not participating in labor force
    1. TotNonLbrRate = TotNonLbr / Civ  
* TotEmply : total count of employed teens (civilian only)
* TotUnEmply : total count of unemployed teens (civilian only).
* EmplyRate : Employment rate of teens  
    1. EmplyRate = TotEmply / CivLbr
* UnEmplyRate : Unemployment rate of teens  
    1. UnEmplyRate = TotUnEmply / CivLbr
