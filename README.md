# IBM-Applied-Data-Science-Capstone

# Overview 
Welcome to the Data Science Capstone Project, in this capstone, we will predict if the Falcon 9 first stage will land successfully. SpaceX advertises Falcon 9 rocket launches on its website with a cost of 62 million dollars; other providers cost upward of 165 million dollars each, much of the savings is because SpaceX can reuse the first stage. Therefore if we can determine if the first stage will land, we can determine the cost of a launch. This information can be used if an alternate company wants to bid against SpaceX for a rocket launch.
# Objectives
To build a robust predictive model.

### 1. Collecting the data:
- **Request to the SpaceX API**
- **Clean the requested data.**

### 2. Web scrap Falcon 9 launch records with BeautifulSoup:
- **Extract a Falcon 9 launch records HTML table from Wikipedia**
- **Parse the table and convert it into a Pandas data frame**

### 3. Data wrangling:
- **Exploratory Data Analysis**
- **Determine Training Labels**

### 4. Database Integration:
- **Load the dataset into the corresponding table in a Db2 database**
- **Execute SQL queries**

### 5. Exploratory Data Analysis and Feature Engineering:
- **Data Analysis and Feature Engineering using Pandas and Matplotlib**

### 6. Interactive Visual Analytics with Folium:
- **Mark all launch sites on a map**
- **Mark the success/failed launches for each site on the map**
- **Calculate the distances between a launch site to its proximities**

### 7. Interactive Dashboard with Plotly Dash:
- **Add a Launch Site Drop-down Input Component**
- **Add a callback function**
- **Add a Range Slider to Select Payload**

### 8. Machine learning pipeline and Hyperparameter Tuning:
- **Standardize the data**
- **Split into training data and test data**
- **Find the method performs best using test data**

# Results
Decision Tree Classifier achieved the highest accuracy score of 0.944, whilst SVM and K-nearest Neighbors achieved 0.833 on the test set, making the Decision Tree Classifier the best performing model.
