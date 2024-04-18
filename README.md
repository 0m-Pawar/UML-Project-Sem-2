# UML-Project-Sem-2
We are using K Means Clustering to group similar data points into distinct clusters with the help of similar characteristics. In this project, we are taking ‘Mall Customer’ dataset.
Our dataset contains 200 rows and 5 columns namely CustomerID, Genre, Age, Annual Income(k$) and Spending Score(1-100). 
Customer ID – It contains customer Id from 1 to 200.
Gender – Wrongly written as Genre. It is a column which contains Male and Female.
Age -  It contains the age of the customers.
Annual Income(k$) - It gives us the annual income of the customers in thousand dollars.
Spending Score (1-100) - It is the spending score of a customer which indicates how much they tend to spend when shopping. It's a way for businesses to understand how valuable a customer is based on their purchasing habits.
The project begins with importing necessary libraries such as numpy, pandas, matplotlib, seaborn, and standardscaler along with K-Means for clustering. Data is read using pd.read_csv and then checked for outliers and null values before cleaning. Visualizations including distribution plots for 'Age Range', 'Annual Income', and 'Spending Score', countplot for gender distribution, and scatterplots for relationships between various attributes are created.
Barplots are utilized to analyze customer demographics like age groups, spending score, and income. Columns such as 'Age', 'Annual Income', and 'Spending Score' are scaled using StandardScaler to standardize the data for better algorithm performance. KMeans clustering is applied with initially 4 clusters, evaluated using an elbow curve to determine the optimal number of clusters, which turns out to be 5. Finally, the data is clustered into 5 groups and visualized using a scatterplot.
Project Contributors : Om Pawar & Reese Pereira
