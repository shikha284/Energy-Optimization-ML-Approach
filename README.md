# Energy-Optimization-ML-Approach

Rapid rise in energy consumption is one of the major global concerns, this project aims to the optimize the energy usage in buildings by utilizing an archive dataset that has data collected from over 300 sensors for three years. This data consists of information about indoor environment, outdoor environment and Heating, Ventilation and Air Conditioning (HVAC).  The data plays an crucial role in validating the model's predictions. Machine learning models like Multiple Linear Regression, Random Forest, kNN, and Gradient Boosting algorithms were developed as part of this project.

The project aims to analyze the relationship between the energy consumption by buildings and their impact on the environment by accurately predicting the HVAC cooling and heating load. The output expected includes predicting HVAC cooling and heating load based on collected indoor and outdoor environment data.

### Data Source

'LBNL Building 59' dataset has been used, which includes building energy, HVAC control, and occupant data collected over three years [1]. The focus is on energy use data, Outdoor environmental data, and Indoor environmental data, utilizing six specific CSV files. 
Reference : [1] Luo, Na et al. (2022), A three-year dataset supporting research on building energy management and occupancy analytics, Scientific Data, Journal-article, https://doi.org/10.1038/s41597-022-01257-x . https://datadryad.org/stash/dataset/doi:10.7941/D1N33Q

### Project Deliverables

Several research papers and patents were read and analyzed to understand the scope of project and further supplement the research with our work and models. A significant reasearch paper “Optimizing Building Short-Term Load Forecasting: A Comparative Analysis of Machine Learning Models” written by Paraskevas Koukaras, Akeem Mustapha, Aristeidis Mystakidis and Christos Tjortjis was thoroughly analyzed. The article can be seen at https://www.mdpi.com/1996-1073/17/6/1450. A medium blog has been written based on our understanding and analysis of the research paper. 

Link for the medium blog post-

https://medium.com/@venkatasaisreelekha.gollu/understanding-building-energy-consumption-a-deep-dive-into-predictive-modeling-5d961c907b4e

An Argumentated Reality (AR) video was made where we have taken into consideration a commercial building. We can analyze the distribution of Heating Ventilation and Air Conditioning load HVAC for north and south wing of the building.

We can see the distribution of the load in each sensor , which zone has high load and this leads to the understanding on building energy management. The heatmap shows the correlation among all the features present in the dataset. The histogram depicts the count of the HVAC. Argumented reality AR videos can be used to show the visualizations in an appealing and interactive way. This increases the interest towards the subject , subsequently leading to work on solution for problem ahead. 

Link for Augmented Reality video-

https://youtube.com/shorts/qZ4R17LbCME

We leveraged Jira and Confluence to streamline our project activities and collaborate on tasks at hand. Confluence acted as our central repository for managing and storing files, planning sprints, conducting meetings and taking meeting notes related to the project. Jira was utilized to implement agile methodology through task creation, assignment and progress monitoring throughout the sprint.

Project deliverables include the following-

- Jupyter Notebook (ipynb files)
- Medium Blog
- Augmented Reality (AR) Video
- Pickle files
- Project Report (Overleaf)
- Project Presentation
- Elevator Pitch Video
- Jira Board

### Data Visualization

1. Top 40 features selected based on f regression score for Hvac N target variable

   ![image](https://github.com/user-attachments/assets/caeb5a8f-adde-4c1e-8c29-0d332350d1bc)

2. Top 40 features selected based on f regression score for Hvac S target variable

![image](https://github.com/user-attachments/assets/89e8c3f4-4b6d-49c8-8e15-daa36354c7eb)

3. Heatmap showing the correlation of the South sensors and HVAC

![image](https://github.com/user-attachments/assets/7b4eece8-7a91-43f6-9397-1e6b4d2400b2)

4. Box plot of North and South HVAC

![image](https://github.com/user-attachments/assets/6a2dd192-05e0-4aa6-b0d8-3012d8575a9c)

### Project Methodology

The goal of smart building lies in minimizing the energy consumption by the end user. This project aims at optimizing energy consumption by accurately predicting the HVAC cooling and heating load [9]. The proposed statistical techniques and traditional machine learning algorithms to predict HVAC cooling and heating load are based on collected indoor and outdoor environment data.

![image](https://github.com/user-attachments/assets/c2559ea1-625a-429d-8cfe-eefd152616fe)

### Model Development

1. Data is split into test and train sets. 70% of the entire dataset is used for training the model while 15% of the data is kept as test data and 15% of the data is used as validation purpose. This test data is used for model evaluation.
2. Multiple Linear Regression, K-Nearest Neighbor (K-NN), XGBoost Gradient Boosting and Random Forest algorithms were implemented to develop machine learning models.

### Results

#### A. North Wing

![North](https://github.com/user-attachments/assets/85f4e87e-4ebe-47d0-94f6-2a53806540e8)

#### A. South Wing

![South](https://github.com/user-attachments/assets/bbf68c00-2c1f-4892-88e9-7f6d0ef86de7)

### Learning Outcomes

1. Data pre-processing itself is crucial and integral for performance of the model and it takes 70 percent of the time. Effective planning according to the deadlines and understanding the importance of communication and equal work distribution among the team members through Jira and Confluence emerged as saviour for us. 
2. Exploring multiple papers and new methodologies provided the understanding of the topic. By embracing change and adjusting our strategies as needed, we were able to overcome obstacles and achieve our goals more effectively. The concepts such as dimensionality reduction, feature selection, tuning, etc. were instrumental in model building. 
3. The usage of multiple evaluation metrics ensured a thorough understanding of the model’s strengths and weaknesses, facilitating informed decision-making and improving the quality of machine learning solutions. 
4. Data robot or lazy prediction were utilized prior to implementing the models. Here we implemented a data robot after implementing the models in our project then we got to know that light gradient boosted trees regressor with early stopping performed better and achieved an accuracy of 95.8 percent for hvac N and 92.3 percent for hvac S if we had known it earlier we could have picked it initially only these little percent increase in accuracy in real time leads to lots of difference in many fields like healthcare and many more.
