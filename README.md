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
[project-1.pdf](./PCA-analysis.pdf)  
- Downloaded, cleaned, and transformed the dataset (including normalization).  
- Applied **PCA**, identifying ~200 eigenvectors; 8 were significant.  
- Selected **2 principal components** capturing the most variance for dimensionality reduction.  
- Visualized the data in the principal vector space.  
- Implemented **Bayesian estimation** in 2D space and applied **minimum-error-rate classification**.  

#### Project 2 – Convolutional Neural Network (CNN) Implementation  
[project-2.pdf](./Deep-CNN.pdf)  
- Collected, cleaned, and preprocessed the dataset.  
- Designed and built the **CNN model layer by layer**.  
- Trained and tested the model; reported **accuracy metrics** and analysis.  

---

### CSE-543 – Information Assurance and Security (Instructor: Stefan Yua)  
This course provided a comprehensive overview of **data protection**, **privacy**, and **security**, covering various levels of protection and how different modules address specific aspects of securing data.  

**Projects & Assignments:**  
- **Weekly Reports** ([Weekly_Reports.zip](./Weekly_Reports.zip)) – Compiled a literature survey of weekly readings, summarizing key insights from academic papers.This is a combined list of academic survey's towards the project reports for the final project.

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
[Project-3.pdf](./DPS-PROJECT1-PHASE1.pdf)
Working on a grpah databse project with neo4j, working with the subreddits dataset which has roughly 2.2 million subreddit posts.
- First installed worked and completed the neo4j installation.
- Then loaded all the data onto the graph database , then set metrics for the database trip weights etc where we can identify the database.
- developed the logic for bfs and dfs model to count the trips etc using GLS modules.
- Then used the inbuilt pagerank graph to execute and complete the graph implementation for the pagerank algorithm.
- obtained the page rank score that match the values in the test module.


## Project 2
[project-4.pdf](./DPS_PROJECT1-PHASE2.pdf)
[load-balance.png](./load-balance.png)

This is the part 2 of the same project where we are required to maintain a fullyload balanced deployment for the gfs and bfs problem to run and scale automatically when the load is higher in kubernetes.

The cluster were created and code was loaded into kubernetes ,the apps were deployed and health of the apps monitored for good health.
I first created the overall load balancer then the created and deployed clusters , after which the data  and all required packages were installed directly into the clusters.
Then github and other main packages were installed via the requirements.txt file launch the app and load the data.
The data is then prepared and setup to be processed within the app the kafka pods which were deployed.
The installation of the setup images and so on was done post which I run the BFS and DFS algorithm within the app.

## Assignments

## Assignments 1 SQL
This SQl data load tasks 
- Worked on this project for close to a month started with postgres and sql setup.
- Loaded large dataset 1-3 gb into postrges , manipulated the dataset , created tables and relations as given in the diagram.
-created the queries to retrieve the data and queries based on information requested.

## Assignment 2 Spatial Query
- required the analysis of spatial relevent data for the query to identify the areas ,physical location that are closer to a given location based on the query provided.
- used scala sparksql to implement the function that impletemnt 2 main queries for the implementation.

## Assignments 3 Hot Spot Analysis & Hot cell analysis 
- Hot zone analysis for yellow taxi driving analysis this was a interesting to do the analysis of hote zone and hot cell.
-Implemented  the join function for hot zone analysis and hot cell for yellow taxi cab trips.
-Used 1 day as the timestep for analysis implemented given fucntion for coordinates.

## Assignments 4  Data Fragmentation

## DSE 501 Statistics for Data Analysts
A deep dive into the data analysis for Statistical inference , model building and data inference etc.
The coursework and projects for this course.


## Projects 

In this project, our group analyzed energy consumption and greenhouse gas (GHG) emissions across U.S. cities and counties using the NREL 2016 dataset. The main goal was to really understand how energy is being used at the subnational level and what factors influence emissions the most. Since national-level data is common but city/county-level insights are usually limited, this dataset gave us a pretty unique chance to explore localized patterns.

We started by cleaning the dataset (lots of missing values, inconsistent formats, etc.). After preprocessing, we looked at distributions, correlations, and spatial differences. We found that per-capita electricity consumption had a right-skewed distribution, and some regions showed really high values because of industrial activity or extreme climate zones.

Then we moved into statistical tests:

ANOVA showed climate zones do significantly affect energy use, which makes sense because heating/cooling loads change by region.

Correlation tests confirmed that population and total electricity consumption are strongly related, which matched our expectations.

For emissions, the industrial sector turned out to be a major contributor in many counties.

For modeling, we tried both OLS regression and Random Forest to predict total GHG emissions using population, energy consumption (electricity, natural gas), gasoline, and diesel usage. OLS actually performed slightly better for our dataset and gave useful confidence intervals, while Random Forest helped us figure out feature importance — residential electricity consumption came out as the strongest predictor.

Finally, we wrapped the project by discussing what this means for policy. Basically, because different regions use energy so differently, a “one-size-fits-all” policy won’t work. Some counties need industrial-focused interventions, others need residential efficiency improvements, and places in coal-heavy eGRID regions would benefit most from grid decarbonization.

Overall, the project gave us a good understanding of how geography, population, sectoral activity, and grid composition influence emissions, and it showed why localized data is super important when planning for sustainability.


## STP 550 - Statistical Machine Learning(Instructor: RObert Murchoch)
The course touched  on Deeper topics in Machine Learning techniques in general and data science.


## Assignments
The are 5 assignments for this course few have been detailed here.

## Assignemnt 1
[Assignment-1](./STP-assignemnt-1.pdf)
The assignment involves multi-linear and linear regression for housing prices , I used linear,quadratic and multi-linear analysis for the prices dataset.
The quadratic and non linear is a better fit for the data compared linear , but here increasing the terms overfits the data and resutlts in loss of accuracy.

The final accuracy score was around 92% the model the quadratic model does not overfit and is better at generalizing the results.

## Assignment 2 
[Assignment-2](./STP-Assignment-2.pdf)
KNN Implementation for car mileage based on year prediction.The data was first obtained, cleaned and then used KNN (n_neighbours) the neighbour count was elbow graph method the k=8 was chosen after which the graphs were plotted.

## Assignemnt 3
[Assignment-3](./STP-assignment-3.pdf)
The lasso and polynomial regression for used cars dataset, this was more challenge  and interesting to do.
I Experimented with Lasso using L1 and L2 penalty , the model performed better with L1 penalty the polynomial regression give a close fit but the model can be bogged down with larger parameters.


## Year 2 

