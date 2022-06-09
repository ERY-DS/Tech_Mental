# Tech_Mental
TECH MENTAL DATA ANALYSIS
<p> ABOUT DATASET
This dataset contains a survey about how employees see, understand and handle mental health.
In the eyes of the society, there is a conception that tech industry is a very demanding industry and there by affects mental health. Interestingly, the importance of data analytics is to be able to support or dispute some of these assumptions with data.
According to Aditi Muyle, Kaggle, Mental health affects your emotional, psychological and social well-being. It affects how we think, feel, and act. It also helps determine how we handle stress, relate to others, and make choices. In the workplace, communication and inclusion are keys skills for successful high performing teams or employees. The impact of mental health to an organization can mean an increase of absent days from work and a decrease in productivity and engagement. In the United States, approximately 70% of adults with depression are in the workforce. Employees with depression will miss an estimated 35 million workdays a year due mental illness. Those workers experiencing unresolved depression are estimated to encounter a 35% drop in their productivity, costing employers $105 billion dollars each year. 
Tailored to this analysis, I am looking at using this data to measure the most prominent factor that affects mental health.
Secondly, to determine what ways employers can help and support the cause of mental health.
This Dataset is from OSMI
Open Sourcing Mental Illness is a non-profit, corporation dedicated to raising awareness, educating, and providing resources to support mental wellness in the tech and open-source communities. OSMI began in 2013, with Ed Finkler speaking at tech conferences about his personal experiences as a web developer and open-source advocate with a mental health disorder. The response was overwhelming, and thus OSMI was born.
The survey collected in 2016 is being used in this analysis.

Acknowledgements
The original data collection and hosting has all been provided by Open-Sourcing Mental Illness (OSMI). you can find all of the datasets (including 2016, 2017 and 2018) here.



Data Preparation

Dataset Original has 63 columns and 1434 rows
Drops
Some columns that are not relevant to this particular analysis have been reduced, resulting into 28 Columns and 1433 rows
Column names
The column titles are in question format and lengthy as well. So, renaming the columns will be best advised so as to allow easy manipulations and less clumsy exercises. 
Age
We will be removing outliers and these are ages below 15 and above 74
Gender inconsistencies
There are two observations and cleaning we have to do here. First will be the typos and secondly, reducing gender types to the three major categories.
Missing values/ Nulls
Although some of the columns were blank. These shall be treated as missing and considered during analysis.
State column
The missing values in the columns are as a result of the other countries present
It looks more like this survey was based in the USA (as it has 70% of all the entries) but with other nationals in the industry
Therefore, it will not be fair to make a substantial demographic conclusion as some countries have just single or very insignificant number of entries.


