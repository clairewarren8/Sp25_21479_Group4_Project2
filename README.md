
# Hate Crimes in New York - MIST 4610 Project 2

## Team Name
Sp25_21479_Group4

## Team Members 
   1. Lauryn Stallworth 
   2. Abby Poore
   3. Claire 
   4. Nick Weir 
   5. Liam 

## Dataset Description
Our dataset tracks hate crimes that have been reported in the state of New York across various counties starting from 2010. We obtained this data set through the U.S Data Catalog (https://catalog.data.gov/dataset). Our dataset specifies different information about different hate crimes that have occurred, which includes the year it took place, the number of victims and offenders, the crime type(such as crime against persons or property crime), number of offenses, and the type of group they are targeting(such as Anti-Gay Male, Anti-Asian, Anti-Islamic, etc,). The County and Crime Type dimensions are both of string datatype. The Year dimension as well as the number of offenders, victims, and incidents are of number datatype. We decided to pivot these tables and created calculated fields for each subgroup. Pivoting the tables and creating calculated fields allowed us to be able to better analyze the data by looking at specific targeted groups and crime types. Overall, this dataset provides valuable insights into potential patterns and trends within hate crimes across New York State over time. The structure of our dataset helps to support meaningful visualizations that can be analyzed to identify a need to improve public policies, law enforcement efforts, and community support or education.

## Objective
The discussion of hate crimes is very intricate, but important for us to know and understand in order to move to a brighter future. This dataset is not the end all be all, but does serve as importance in understanding if there has been an increase, decrease, or no changes at all in the hate crimes that have been reported in the State of New York. Our goal is to utilize the issues that have been reported in the past in order to bring awareness, incorporate programs to decrease the occurrences, and offer additional protection that may be needed. Using this dataset, we will be able to briefly show some examples of where these incidents may occur, and aim to see if external factors may also pose an issue as well. 

## Data Manipulations 
For this dataset, we created several different calculated fields in order to help visualize the data into smaller categories and assist us in coming up with questions. The calculated fields are as followed: 

<img width="636" alt="Screenshot 2025-04-27 at 10 24 15" src="https://github.com/user-attachments/assets/c5571876-18fd-45d6-8703-bd878a4d1813" />


## Question 1 

Which counties in New York State have reported the highest rates of hate crimes over time, and how do the bias motivations differ across these counties?

### Q1 Importance 
To start off, it’s important to understand what bias motivation means. Bias motivation refers to the reason behind a hate crime or specifically, the offender’s prejudice against a victim because of who they are or the group they belong to. For example, this could include race, religion, ethnicity, sexual orientation, gender identity, disability, or national origin. With this information in mind, this question is relevant because it allows us to understand where and why specific hate crimes occur. This information could be used to promote safety and identify certain groups that are particularly targeted or more vulnerable. Societal changes as well as current world issues may also be contributing factors that influence bias motivations towards certain groups. Law enforcement could also utilize this data to better allocate their resources in orderto prepare and respond proactively. Creating educational and prevention programs in counties that have higher incident counts can be used to address certain biases towards different groups. Looking at this data over time can also help identify if policies, laws, or programs need improvement or if there may be a need for a change in strategy. 

### Q1 Vizualizations
![Q1_2](https://github.com/user-attachments/assets/6a0b1211-1e0b-47b6-ba6c-e89b082468d6)

We noticed that the locations with multiple colors was New York City, which has a population of 8.48 Million people. We decided to delve deeper on the specific number for New York Counties and which groups of people were targeted. 

<img width="1466" alt="Screenshot 2025-04-27 at 15 07 49" src="https://github.com/user-attachments/assets/9e9350b2-9668-4636-bc7a-2caa40a107a9" />

### Q1 Analysis 

From our initial observations of the New York counties dataset the counties Kings, Queens, New York, Bronx, Suffolk, and Nassau reported the highest numbers of hate crimes year and year again. This is likely due to New York’s population density and diversity. The data can reveal nuanced differences in bias motivation across the boroughs and how it compares to less urban or upstate counties. Given this information, we conducted a closer analysis of which bias motivations were most heavily targeted. The largest impacted group was Anti-Semitism with 3,200 plus reported incidents. Other notable targeted groups were Anti-Black, Anti-Gay Male, and Anti-Asian. Kings County, which is Brooklyn, had the greatest incident count of Anti-Semitic crimes, which also has the largest Jewish population. Additionally, the rise in Anti-Asian hate crimes is largely due to the social tensions surrounding the COVID-19 pandemic. This localized information is crucial. These insights ensure the right resources are directed to the right places. Law enforcement and community leaders can take proactive steps to protect these targeted groups to ultimately improve greater public safety and unity in communities across New York State. 


## Question 2 
Which bias motivations in New York State report the highest rates of property crimes, and during what years are there spikes?

### Q2 Importance 
This question matters because it helps uncover patterns in how and when certain communities are targeted through property-related hate crimes. Identifying which bias motivations are linked to higher rates of these incidents allows us to better understand the risks faced by specific groups. This is not just as individuals, but in the spaces they gather, organize, and build community. By analyzing when spikes occur, we can begin to anticipate periods of heightened risk and recommend proactive measures to protect these groups in shared settings like places of worship or community centers. Unlike unpredictable individual attacks, patterns in property-related crimes offer a bit clearer opportunity for strategic intervention. This kind of insight empowers local leaders, public safety officials, and advocacy organizations to take action when it matters most. They can offer protection, resources, and support during times when communities are most vulnerable.

### Q2 Visualizations 
![Q1_1](https://github.com/user-attachments/assets/b352165e-23fa-48ed-8f31-c723e5acb504)

Our data shows us that Anti-Semetic(Ant-Jewish) hate crimes had the most property-based incidents with Anti-Black property hate crimes following. We decided to dive a little deeper to see how many incidents occured. 

![Q2_2](https://github.com/user-attachments/assets/93f725f7-1b77-4d0d-862b-c1307ad3e778)

### Q2 Analysis
The data helps us understand whether or not hate crimes against Jewish people are attacked on a more property basis or if we can point to events that caused an outburst of hate. With this data we would be able to show that any time there is a major world event involving people of Jewish religion/ descent suggesting additional protection may be needed in New York as the population of Jewish people is around 1.4 Million in the state of New York. Many religious hate crimes happen in places of worship and with this data’s backing we can argue that synagogues would need added protection during these times. If an event like this happens again, we are able to provide more resources/assistance to those communities ensuring protection. We see significant spikes within Anti-Semitic crimes in 2012 and 2019, and continuous growth from 2021 to 2022, and external factors may be to blame such as the holocaust or the Israel-Palestine conflict. 


## Sources 
Dataset: https://catalog.data.gov/dataset/hate-crimes-by-county-and-bias-type-beginning-2010

NYC Population: https://www.nyc.gov/content/planning/pages/planning/population 

Jewish Population in NY: https://www.thejc.com/news/usa/jewish-population-of-new-york-reaches-14-million-rj1jw48x

External Factors of Hate Crimes: http://nytimes.com/2022/04/26/nyregion/antisemitic-attacks-new-york.html









