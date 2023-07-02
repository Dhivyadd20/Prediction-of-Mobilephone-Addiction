# Prediction-of-Mobilephone-Addiction
MOBILE PHONE ADDICTION OF LOYOLITES - USING MACHINE LEARNING MODEL AND POWERBI

**INTRODUCTION:**

Mobile phone addiction has become a widespread phenomenon, particularly among young
adults. As mobile phones have become an integral part of daily life, it is crucial to examine the extent to which mobile phone addiction affects Loyola College students' academic and social
lives. This research paper aims to explore the prevalence of mobile phone addiction among
Loyola College students and its impact on their academic performance, social relationships,
and overall well-being. The study also seeks to identify the factors that contribute to mobile
phone addiction among college students and suggest possible interventions to help them
manage their phone usage. Understanding the nature and consequences of mobile phone
addiction at Loyola College can shed light on the larger issue of mobile phone addiction among
college students worldwide and inform policies and programs that promote responsible mobile
phone usage. Mobile phone addiction, also known as problematic mobile phone use or mobile
phone dependence, is a behavioral addiction characterized by excessive use of mobile phones,
impaired control over phone use, and negative consequences in various domains of life, such
as social, academic, occupational, and psychological. Youngsters, particularly those in their
adolescence and emerging adulthood, are particularly vulnerable to mobile phone addiction
due to their developmental needs for social connection, identity formation, and autonomy.

The prevalence of mobile phone addiction among youngsters varies depending on the
definition and measurement used. Studies have reported that the prevalence of mobile phone
addiction ranges from 10% to 40% among adolescents and young adults worldwide. In India,
a survey conducted among 750 students aged 12-21 found that 32% exhibited
symptoms of mobile phone addiction.

The causes and risk factors of mobile phone addiction among youngsters are multifaceted and
interrelated. Some of the common factors associated with mobile phone addiction include:

**Social media use:** Social media platforms like Facebook, Instagram, and Snapchat are
popular among youngsters for socializing, sharing, and seeking validation. However, excessive
use of social media can lead to FOMO (fear of missing out), social comparison, and self-esteem
issues, which can fuel mobile phone addiction.

**Instant gratification:** Mobile phones offer instant access to information, entertainment, and communication, which can be rewarding and reinforcing for youngsters who seek immediately
pleasure and distraction from boredom or stress.

**Peer pressure:** Youngsters may feel pressure to conform to their peers' norms and expectations regarding mobile phone use, such as responding to messages promptly, staying updated on social media, or playing mobile games.

**Psychological factors:** Youngsters who experience anxiety, depression, loneliness, or low
self-esteem may use mobile phones as a coping mechanism or a way to escape from negative
emotions, which can lead to addiction over time.

The consequences of mobile phone addiction among youngsters can be significant and long-
lasting. Some of the negative consequences of mobile phone addiction include:

**Impaired academic performance**: Excessive phone use can lead to distractions,
procrastination, and poor time management, which can affect students' academic performance
and achievement.

**Social isolation:** Although mobile phones can facilitate social connections, excessive phone
use can also lead to social withdrawal, reduced face-to-face interactions, and alienation from
peers and family members.

**Physical health problems:** Prolonged phone use can lead to physical health problems, such as
eye strain, neck and back pain, sleep disturbance, and poor posture.

**Mental health problems:** Mobile phone addiction has been associated with various mental
health problems, such as anxiety, depression, stress, and addiction to other substances or
behaviors.

**METHODS:**

**Data Collection:** The survey will be conducted using a self-administered online questionnaire that will be distributed to a random sample of students from Loyola College. The questionnaire will contain questions related to mobile phone usage patterns, addiction symptoms, mental health, and academic performance. Data related to mobile phone usage patterns
and addiction symptoms will also be collected through the survey.

**Data Analysis:** The collected data will be analyzed using machine learning techniques,
specifically k-means clustering. The collected data will be pre-processed, and relevant features will be extracted from it. Then, k-means clustering will be performed on the extracted features to group the participants into clusters based on their mobile phone usage patterns, addiction symptoms, mental health, and academic performance. This will help in identifying the subgroups of students who are at risk of mobile phone addiction.

**Visualization:** The results of the k-means clustering analysis will be visualized using PowerBI, which is a data visualization tool. The tool will be used to create interactive and informative visualizations to explore the relationships between the different variables and identify any patterns or trends.

**METHODOLOGY:**

The study will use a quantitative survey design to investigate the causes of mobile phone
addiction in students and examine its impact on mental health and academic results. The
following sections describe the research design, participants, measures, and data analysis
procedures in detail.

**Research Design:**
The research design for this study is a cross-sectional survey design, which involves collecting data at a single point in time. The survey will be conducted online, and participants will be asked to complete the questionnaire at their convenience within a specified timeframe. The survey will be anonymous, and participants will be informed about the purpose and scope of the study.

**Participants:**
The participants for this study will be students from Loyola College. The sample will be
randomly selected from different departments and academic years. The sample should be
diverse in terms of age, gender, and mobile phone usage patterns.

**Measures:**
The survey questionnaire will contain questions related to mobile phone usage patterns,
addiction symptoms, mental health, and academic performance. Additionally, data related to
mobile phone usage patterns and addiction symptoms will be collected using mobile phone
tracking apps. The collected data will be pre-processed, and relevant features will be extracted
from it.

**Data Analysis:**
The collected data will be analyzed using machine learning techniques, specifically k-means
clustering. The extracted features will be clustered using the k-means algorithm, which will
group the participants into clusters based on their mobile phone usage patterns, addiction
symptoms, mental health, and academic performance. The results of the k-means clustering
analysis will be visualized using Power BI to create interactive and informative visualizations. These visualizations will help in identifying the subgroups of students who are at risk of mobile phone addiction and examining the impact of mobile phone addiction on mental health and academic performance.

**Assumption:**
Using the data collected from the survey, we will examine the causes of mobile phone addiction
in students and identify the subgroups of students who are at risk of mobile phone addiction.
Additionally, the study will examine how mobile phone addiction affects the mental health and
academic performance of students. The visualizations created using Power BI will provide
insights into the relationships between the different variables and identify any patterns or
trends.

**ALGORITHM:**

Clustering is a method of unsupervised learning and is a common technique for statistical data
analysis used in many fields. In Data Science, clustering may be applied while analysis to gain
some valuable insights from the data by seeing what groups the data points fall into when we
apply a clustering algorithm. There are different types of clustering methods.

• Hard Clustering: In hard clustering, each data point either belongs to a cluster completely or not. For example, in the above example, each customer is put into one group out of the 10
groups.

• Soft Clustering: In soft clustering, instead of putting each data point into a separate cluster, a probability or likelihood of that data point being in those clusters is assigned. For example, from the above scenario, each customer is assigned a probability to be in either of the 10 clusters of the retail store.

• Hierarchical clustering: as the name suggests is an algorithm that builds a hierarchy of clusters. This algorithm starts with all the data points assigned to a cluster of their own. Then two nearest clusters are merged into the same cluster. In the end, this algorithm terminates when there is only a single cluster left.

Four of the most used clustering algorithms:

• K-means
• Fuzzy K-means
• Hierarchical clustering
• Mixture of Gaussians

In this study, the K-means algorithm is considered for simplicity. K-means is one of the most
popular “clustering” algorithms. K-means store k centroids that it uses to define clusters. A
point is considered to be in a particular cluster if it is closer to that cluster’s centroid than any other centroid. K-Means finds the best centroids by alternating between (1) assigning data points to clusters based on the current centroids and (2) choosing centroids (points which are the center of a cluster) based on the current assignment of data points to clusters. K-means clustering algorithm computes the centroids and iterates until we find its optimal centroid. It assumes that the number of clusters is already known. It is also called a flat clustering algorithm. The number of clusters identified from data by the algorithm is represented by „K‟ in K-means. In this algorithm, the data points are assigned to a cluster in such a manner that the sum of the squared distance between the data points and the centroid would be minimum. It is to be understood that less variation within the clusters will lead to more similar data points within the same cluster. 

**RESULTS AND DISCUSSION:**

A primary objective of the present study is to find the cause of mobile phone addiction in
students and to examine whether it affects the mental health and the academic results of
students, for which 20 independent questions are considered for building the machine learning-based prediction model. We initially investigated if there is any relation between the addicted
students and the number of arrear papers, **surprisingly, it is found to be less number of arrear papers for the addicted students when compared with non-addicted students.**

![image](https://github.com/Dhivyadd20/Prediction-of-Mobilephone-Addiction/assets/129213031/c90d2b83-99c5-4363-a8b1-9b2fd21243c5)

Students with no arrear are visualized below:

![image](https://github.com/Dhivyadd20/Prediction-of-Mobilephone-Addiction/assets/129213031/10f589ef-9c7c-4654-b7ae-674e6414f787)

169 students are non-addictive with no arrears and 98 students are addictive with no arrears.

![image](https://github.com/Dhivyadd20/Prediction-of-Mobilephone-Addiction/assets/129213031/f274432b-580b-4e22-9e8b-1e7532d8d27b)

An overall visualization is shown below:

![image](https://github.com/Dhivyadd20/Prediction-of-Mobilephone-Addiction/assets/129213031/12b7739d-8e4e-4229-9e67-96db73208549)

**CONCLUSION:**

The study aimed to investigate the causes of mobile phone addiction among students and
whether it affects their mental health and academic performance. The results showed that the
mobile phone addiction among students has no big effect on the academic results of the
students. It was also found that excessive mobile phone usage has a negative impact on the
mental health of students. The findings were obtained by conducting a survey using a
questionnaire and analyzing the data with machine learning techniques such as k-means
clustering.

Furthermore, the visualization of the data using Power BI allowed for a better understanding
of the relationships between the variables, such as the correlation between mobile phone usage
and mental health. The k-means clustering helped in grouping the participants based on their
responses to the questionnaire, which provided insight into the common patterns of mobile
phone addiction among students.

In conclusion, the study highlights the need for awareness and education on responsible mobile
phone usage among students. It also emphasizes the importance of balancing mobile phone
usage with social interactions and academic activities to maintain good mental health and
academic performance. The findings of this study can be utilized by educational institutions,
policymakers, and parents to design interventions to address the issue of mobile phone
addiction among students.
