# JupyterNotebook_NorthEndConnect
Data analysis work for research report

NorthEnd Internet Connectivity Project 2023

NorthEnd Internet Speed Data Analysis
Robertson College Practicum
Authors: Olubunmi Adebiyi, Joel Templeman
Last Updated: 03/25/2023 

Problem Statement
How much meaningful Internet connectivity is available to residents of low income communities like the North End community of Winnipeg Manitoba is unknown. 

We do not know if the median internet speeds which we deem a measure of “Meaningful connectivity” has grown in tandem with the increased use and access to internet that these communities have experienced since the onset of the pandemic. 

Ensuring meaningful connectivity in these communities which is defined as better quality internet connection requires understanding where they are at in terms of internet access quality and any associated factors that might contribute to the present state. Furthermore, an understanding of currently available data can help in designing actionable steps that can be recommended to policy makers to improve meaningful internet connectivity in these communities.

Our goal in this North End community project is to dissect available data on internet connectivity and access to determine how much meaningful internet data is available to the residents and businesses in this community from the R2W area of the North End community of Winnipeg.

In order to achieve our goal, we will explore the dataset to identify how much meaningful connectivity is available in the North End Community, specifically the R2W area, by how much meaningful connectivity has grown or declined, and draw insight from the data to draw up recommendations for relevant stakeholders.
Background 
The Alliance for Affordable Internet (A4AI) has developed “Meaningful Connectivity” as a new global standard that measures not only if someone has accessed the internet, but the quality of connection they have (ref). 

The quality of connection an internet user has depends on many factors such as having the right speed. Right speed refers to downloads speeds sufficient enough to allow access to multimedia and other applications that make up the full internet experience.

A second factor on which meaningful Internet connection is dependent is the use of an adequate device. Internet connection can be accomplished via different kinds of devices. Through the use of an adequate device, users can produce and consume content online. Adequate connection can be accomplished via mobile internet access or via more robust connections via Computers which may be a desktop or a Laptop.

The level of meaningful connectivity in low income communities such as the R2W area of the North End community is unknown. In this study, we hope to explore if there is meaningful connectivity in the North End  community, if this has grown or declined over time, how the measures of meaningful connectivity in the R2W area are influenced by other factors among others.

This work is a portion of a larger research project looking at internet connectivity in low-income urban populations. The North End of Winnipeg (specifically the R2W postal code prefix) is one of those areas. 



















Terminology:

https://a4ai.org/meaningful-connectivity/ - The Alliance for Affordable Internet (A4AI) has developed “Meaningful Connectivity” as a new global standard that measures not only if someone has accessed the internet, but the quality of connection they have.  


The right speed: Users need sufficient download speeds to access multimedia and other applications that make up a full internet experience.  

An adequate device: Users must be able to both produce and consume content online. Mobile only access is not the same as access via a laptop or desktop, because a full physical keyboard is better suited to content creation and productivity. 

Enough data: Lack of data should not stand in the way of individuals fully using the internet-based applications they consider important. 

Frequent connection: If a user can only connect to the internet every so often, it is less likely to be a meaningful tool for them. 

https://www.digitalinclusion.org/definitions/ 


The digital divide is the gap between those who have affordable access, skills, and support to effectively engage online and those who do not. As technology constantly evolves, the digital divide prevents equal participation and opportunity in all parts of life, disproportionately affecting people of color, Indigenous peoples, households with low incomes, people with disabilities, people in rural areas, and older adults.


Digital equity is a condition in which all individuals and communities have the information technology capacity needed for full participation in our society, democracy, and economy. Digital equity is necessary for civic and cultural participation, employment, lifelong learning, and access to essential services.
It is important to note here the use of “equity” vs. “equality.” When we use the word equity, we accurately acknowledge the systemic barriers that must be dismantled before achieving equality for all.
Digital Inclusion refers to the activities necessary to ensure that all individuals and communities, including the most disadvantaged, have access to and use of Information and Communication Technologies (ICTs). This includes five elements:
1. Affordable, robust broadband internet service;
2. Internet-enabled devices that meet the needs of the user;
3. Access to digital literacy training;
4. Quality technical support; and
5. Applications and online content designed to enable and encourage self-sufficiency, participation and collaboration.
Digital Inclusion must evolve as technology advances. Digital Inclusion requires intentional strategies and investments to reduce and eliminate historical, institutional and structural barriers to access and use technology.
Possible Research Questions to explore:
What the average, maximum, minimum and Variability of Internet speeds in the NorthEnd community
What has been the picture of internet speed growth or decline since 2015/2019 till date- has there been an increase or has there been a decline? Are there factors shown in the data that might have caused this?
What is the variability of Internet speeds over months and years? Are they faster/slower at certain times of the year, if yes why? Can data support these questions
How comparable are the internet speeds with other geolocation within Winnipeg?
What are the relationships between internet speed and internet cost in the NorthEnd community from 2015/2019 till Date
Which providers have better internet speeds and penetration in the NorthEnd community?
Which providers are customers most satisfied with in terms of their services, cost and internet speed?
Does the Internet speed test time variability have any impact on correctness of  data? Is there a difference between using shorter time tests or Longer time testing?
Has median internet speeds grown in tandem with growth in increased use of the internet since pandemic?




Deliverables

A report that will answer the following questions chosen by stakeholders to explore from those highlighted above and any other that may be added. 

Report will include:
A clear statement of the business task
A description of all data sources used  
Documentation of any additional cleaning or manipulation of data 
A summary of my analysis
Supporting visualizations and key findings
My top three recommendations based on my analysis

Stakeholders

Internet society of Manitoba  Team Lead: The executive team will decide whether to approve the recommended research focus.
Joel Templemann: Team Lead in charge of project and research focus
Provide regular inputs and may request status update periodically
Highlight potential obstacles and risks
Internet society of Manitoba  Team: Team members who will contribute to different aspects of the project including, data cleaning, visualization, coding and Report writing and presentation. 








Timeline - Milestones


Milestone
Status
Last Updated Date
Project Start
Ongoing


Project requirements
ongoing


Data Preparation
Completed


Data Analysis
Partly Completed 


Final Report
Not started


Presentation to the Executive Team
Not started




Data Processing
Dataset for the study is available at : https://github.com/InternetSocietyManitobaChapter/JupyterNotebook_NorthEndConnect
 
Data Assessment 
Data comes from the available data set about internet connectivity and penetration in the NorthEnd community of Winnipeg, Manitoba. Data has been verified by the Internet Society of manitoba.(Might need to provide source and links to the data Source for ease of verification if further needed).


Data Format.
Data is provided as a CSV file and dated between 2015 and 2022.
The data had 37,888 rows and 31 columns before data cleaning was commenced. After the blank rows were removed, there were 18,994 rows and 31 columns. 




Plan for data cleaning 
Current data has been processed and significant cleaning has been done. See the list of cleaning done below:
Removal of all blank rows-(northEndConnect.dropna(how = 'all')
Removal of duplicated 
Index column was dropped
Split Date and time columns
Dropped Test date
Correction of ISP names for uniformity and correctness
Filtered for city values that had Winnipeg
Dropped columns that had more than 50%

Data Analysis Plan and Results
The goal of the analysis will be to explore the data to find out what the measures of meaningful connectivity are like in the North End community. 
Determine the median, maximum and minimum download and upload speeds distribution in the North End communities 
Determine the median download and upload speeds distribution changes over time in the North End communities 
Determine the median, minimum and maximum download speeds by ISP providers in the NorthEnd community
Determine the Median, minimum and maximum download speeds by private homes and businesses in the north End community.
Determine the Median, minimum and maximum download speeds locations in the north End community.
What the average, maximum, minimum and Variability of Internet speeds in the NorthEnd community
What has been the picture of internet speed growth or decline since 2015/2019 till date- has there been an increase or has there been a decline? Are there factors shown in the data that might have caused this?
What is the variability of Internet speeds over months and years? Are they faster/slower at certain times of the year, if yes why? Can data support these questions
How comparable are the internet speeds with other geolocation within Winnipeg?
What are the relationships between internet speed and internet cost in the NorthEnd community from 2015/2019 till Date
Which providers have better internet speeds and penetration in the NorthEnd community?
Which providers are customers most satisfied with in terms of their services, cost and internet speed?
Does the Internet speed test time variability have any impact on correctness of  data? Is there a difference between using shorter time tests or Longer time testing?


Key findings/Conclusions
Overall, it appears the median download speeds that users have access to within the North End community varies significantly depending on what providers they use for their internet services. Shaw communications appear to have the highest median download speeds with median values over 150 mbps compared with the vast majority of the other ISPs in the NorthEnd community that have lower median download speeds of less than 100 mbps. Cipherkey and ACN are intermediate in terms of what download speeds their users have access to. They have median download speeds greater than 100 mbps but less than 150mbps. 
In terms of the proportion of addresses in the R2W area that have services with each of these providers, approximately 52% of the end users are with Shaw communications, 35% with Bell Canada and the remaining 13% is shared unequally among the remaining ISPs in the neighborhood.
Concerning the variability of the median download speeds since 2019 to date, it appears there has been fluctuations from one year to the next. The year 2019 had the highest median download speeds of 220.82 mbps that dropped significantly to just over 18 mbps in 2020 possibly owing to an increased number of people working or schooling from home at the height of the pandemic back in march 2020. The next year showed a significant bump in the median internet download speeds to just under 100 mbps  in 2021. The reason for this rise is not immediately apparent. A few speculative reasons could be that the ISPs increased their bandwidth due to increased pressures from significantly increased population of work from home. We need additional data to prove this was the cause of this increase. In 2022 and 2023, the median download speeds have not varied widely like the previous years, they have remained in the 60s for both years although with slight variations.
Overall, the median download speed has declined significantly from 2019 till date in the R2W area suggesting that meaningful internet connectivity might have declined considerably in this area of the NorthEnd community of Winnipeg.
In relation to market share, Shaw communications has declined from the initial 100% in 2019 to just under 40% in 2023. Bell Canada on the other hand with no presence in the area in 2019 has grown its market share to a few percentage shy of 50%. The reasons for Shaw’s market share decline is not immediately apparent considering they have the highest median download speed from 2019 till date. More data will be required to answer this question.
The median jitter and latency have been very low from 2019 to 2023. This is indicative of good connectivity which is essential for Video connections, gaming, etc. All of which are suggestive that meaningful internet connectivity is available in the R2W area of winnipeg. However, it is not known how comparable this data is to other areas of Winnipeg. This might require some further data dissection.
