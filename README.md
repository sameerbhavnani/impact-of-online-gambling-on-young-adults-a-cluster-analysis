# Impact of Online Gambling on Young Adults: A Cluster Analysis

This repository contains the data analysis, visualization, and research findings regarding the socio-economic and psychological impacts of online gambling on individuals aged 18–26.

The rapid digitalization of gambling through platforms like Dream11, Bet365, and Stake has made betting more accessible than ever, attracting a vulnerable demographic of tech-savvy young adults. This research analyzes the behavior patterns, financial strain, and mental health outcomes of 252 respondents (aged 18–26). By applying K-Means Clustering, we segment this demographic into four unique profiles: High Risk Gamblers, Occasional Gamblers, Older Controlled Gamblers, and Financially Affected Gamblers. Our findings highlight a critical correlation between digital gambling accessibility and the erosion of socio-economic stability.
## 📊 Project Overview
Using primary survey data from 252 respondents, this project employs **K-Means Clustering** to segment young adult gamblers into four distinct behavioral profiles. The goal is to identify high-risk patterns and the correlation between gambling frequency and psychological distress.

## 🧩 The Four Clusters
Based on our analysis, we identified:
1. **High Risk Gamblers:** Characterized by high urge intensity and significant lifestyle disruption.
2. **Financially Affected Gamblers:** High impact on savings and overall financial stability.
3. **Older Controlled Gamblers:** Typically aged 23-26, showing more regulated gambling habits.
4. **Occasional Gamblers:** Low frequency with minimal psychological or economic impact.

Choosing the Optimal Number of Clusters
Two methods of choosing the optimal number of clusters (K) were used to find. 
> Elbow Method: This method looks at which sum of squared distance (the inertia) within clusters, when more clusters are added, does not significantly decrease the clustering. The value of the 'elbow' marks the optimum number of clusters.

> Silhouette Score: This metric measures how well separated the clusters are, the higher the score, the better the clusters are defined. With multiple values tested (K=2, 3, 4, 5), we chose K=4 since it divided the data into good segments.

<img width="864" height="293" alt="image" src="https://github.com/user-attachments/assets/21012bc8-925b-46b3-af13-5bd707e946bb" />

**The ANOVA and Chi-Square tests provide strong statistical support for the validity of these clusters, demonstrating that the segmentation accurately represents distinct gambling behaviours among young adults.**

The clustering analysis revealed four distinct groups of gamblers, each with unique behavioural patterns and socio-economic impacts. These findings provide valuable insights for developing targeted interventions and policies to address the negative consequences of online gambling, particularly among high-risk and financially affected individuals. The objective of the research is met in this study through the clustering analysis that fits well in addressing the key objectives of the research by explaining the online gambling behaviours among young adults. 
> Firstly, the data set is analysed by segmenting it into four different groups of high-risk gamblers, occasional gamblers, older controlled gamblers and financially affected gamblers. Moreover, the degree of engagement into gambling behaviours is segmented with high-risk gamblers (Cluster 1) significant and substantial proportion of the sample.
<img width="602" height="394" alt="image" src="https://github.com/user-attachments/assets/0a1a617c-b5a9-4c9c-9b9c-15e6f651b792" />

> Secondly, the clustering process is performed by including socio-economic factors (such as monthly income, financial strain, and occupational status), which enables the study to examine the factors which influence gambling behaviour. Cluster 4, who are also more prone to taking leave or selling possessions, do experience a lot of financial strain; this identifies this group of financially affected gamblers as socio-economically vulnerable. 
<img width="566" height="415" alt="image" src="https://github.com/user-attachments/assets/7c0f8d34-cbb5-45fe-9300-bf9a32721e5b" />

> Thirdly, the analysis evaluates the psychological impact of online gambling on the factors such as the anxiety, depression, guilt, confidence in the self-control of their gambling behaviour. Cluster 1 (high risk gamblers) is characterized with severe psychological distress including low confidence to control one’s gambling while Cluster 2 (occasional gamblers) gambling report no psychological impact at all. 
<img width="791" height="362" alt="image" src="https://github.com/user-attachments/assets/25d0e934-307b-4b92-8224-0a0cf949b73f" />

> Lastly, the clustering analysis does not directly assess awareness or the efficacy of regulations, but it does provide the fundamental knowledge is to focus interventions in specific places. As the study points out high risk and financially affected gamblers as the most vulnerable groups to such challenges it emphasizes the need for increasing the awareness of campaign and the support services to those suffering from socio-economic and psychological problems. Taken as a whole, the clustering analysis presents a comprehensive structure to understand how online gambling is prevalent, how its prevalence is influenced by socio-economic factors, and what are its effects on psychological aspects, while also providing the basis for further research on regulation of the distance gambling and support systems.
<img width="615" height="957" alt="image" src="https://github.com/user-attachments/assets/c9c37bd3-b5eb-4a4a-b1ef-b71f0dc36ff1" />

## 🛠️ Tech Stack
- **Python 3.x**
- **Pandas** (Data Manipulation)
- **Scikit-Learn** (K-Means Clustering & Scaling)
- **Seaborn/Matplotlib** (Statistical Visualization)
- **PCA** (Dimensionality Reduction for Cluster Visualization)

## 📈 Key Findings
- **Psychological Correlation:** High frequency of gambling showed a direct 0.82 correlation with reported anxiety and sleep interference.
- **Economic Strain:** Over 30% of "High Risk" individuals reported selling personal belongings to cover losses.
