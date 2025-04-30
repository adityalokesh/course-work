# CSE-511  
# 👋 Hey there!  

Looks like you found me, **detective** 🕵️‍♂️!  
Are you on the hunt for a **Data Scientist**? Well, I’m excellent at **hunting data** 📊 and **chasing deadlines** ⏰.  

I’m **Aditya**, a 2nd-year Master’s student at **ASU** pursuing **Data Science** 🎓. I’m passionate about **Machine Learning** 🤖, **AI** 🧠, and turning messy data into meaningful insights ✨.  

---

## 🚀 What I Do  

- **Data Analysis & Visualization** 📈  
- **Machine Learning & AI** 🤖  
- **Optimization & Modeling** 🧩  
- **Deep Learning & Neural Networks** 🧠💻  


---

## Year 1  
## Fall(2024)

### CSE-569 – Statistical Machine Learning (Instructor: Boxin Li)  
This course was both challenging and intellectually stimulating. I gained a strong understanding of Bayesian mathematics, d-separation, Principal Component Analysis (PCA), kernel density estimation, and decision boundaries for Bayesian classifiers. Additionally, I learned both parametric and non-parametric density estimation methods.  

**Projects:**  

#### Project 1 – PCA, Density Estimation, and Bayesian Classification  
[project-1.pdf](./project-1.pdf)  
- Downloaded, cleaned, and transformed the dataset (including normalization).  
- Applied **PCA**, identifying ~200 eigenvectors; 8 were significant.  
- Selected **2 principal components** capturing the most variance for dimensionality reduction.  
- Visualized the data in the principal vector space.  
- Implemented **Bayesian estimation** in 2D space and applied **minimum-error-rate classification**.  

#### Project 2 – Convolutional Neural Network (CNN) Implementation  
[project-2.pdf](./project-2.pdf)  
- Collected, cleaned, and preprocessed the dataset.  
- Designed and built the **CNN model layer by layer**.  
- Trained and tested the model; reported **accuracy metrics** and analysis.  

---

### CSE-543 – Information Assurance and Security (Instructor: Stefan Yua)  
This course provided a comprehensive overview of **data protection**, **privacy**, and **security**, covering various levels of protection and how different modules address specific aspects of securing data.  

**Projects & Assignments:**  
- **Weekly Reports** ([Weekly_Reports.zip](./Weekly_Reports.zip)) – Compiled a literature survey of weekly readings, summarizing key insights from academic papers.  

---

### CSE-598 – Special Topics: Data-Driven Optimization  
This mathematics-focused course emphasized **optimization techniques** for real-world problems.  
- Gained hands-on experience using solvers like **CPLEX**, **HIGS**, and **GLPK**.  
- Modeled and solved complex optimization problems efficiently.  

I learnt how to use Jump as well and to model real world problems , converting maximization problems to minimization etc. Sample work.


## SPRING (2024)

### CSE-511 Data processing at scale (Instructor: Satya parupudi)
This course deals with data processing , we learnt how large scale applications cna be broken down into smaller recursive operations, cloud storage and how virtualization for physical storage.
- Livestream processing
- geographical , spatial and other types of data to look at.

## Project work
We completed 4 projects as part of this which include comprehensive work from building a small app to loading graph data bases , perfoming algorithm analysis and also looking into building fucntion for modules that perform operations such as distance calculations, gfs, bfs with large data.

## Project 1 
SQL, loading and Database Management Assignment. Postgresql
[Project-3.pdf](./project-3.pdf)
Working on a grpah databse project with neo4j, working with the subreddits dataset which has roughly 2.2 million subreddit posts.
- First installed worked and completed the neo4j installation.
- Then loaded all the data onto the graph database , then set metrics for the database trip weights etc where we can identify the database.
- developed the logic for bfs and dfs model to count the trips etc using GLS modules.
- Then used the inbuilt pagerank graph to execute and complete the graph implementation for the pagerank algorithm.
- obtained the page rank score that match the values in the test module.


## Project 2
[project-4.pdf](./project-4.pdf)
[load-balance.png](./load-balance.png)

This is the part 2 of the same project where we are required to maintain a fullyload balanced deployment for the gfs and bfs problem to run and scale automatically when the load is higher in kubernetes.

The cluster were created and code was loaded into kubernetes ,the apps were deployed and health of the apps monitored for good health.
I first created the overall load balancer then the created and deployed clusters , after which the data  and all required packages were installed directly into the clusters.
Then github and other main packages were installed via the requirements.txt file launch the app and load the data.
The data is then prepared and setup to be processed within the app the kafka pods which were deployed.
The installation of the setup images and so on was done post which I run the BFS and DFS algorithm within the app.

## Assignments

A deep dive into the data analysis for Statistical inference , model building and data inference