# Tools and Analytics

The computational journey of this project required a suite of advanced tools and analytical methods tailored to the challenges and objectives of analyzing cryptocurrency awareness and adoption in Somalia. These tools were strategically chosen to handle data preprocessing, exploratory data analysis (EDA), visualization, and machine learning model development.

## Tools Utilized

### 1. Data Handling and Preprocessing
- **Pandas**  
  Used extensively for cleaning, organizing, and transforming the dataset. Its capabilities facilitated efficient handling of 211 rows and 20 columns after preprocessing.
- **NumPy**  
  Supported numerical operations and computations, such as handling missing values and standardizing data.

### 2. Visualization
- **Matplotlib**  
  Enabled the creation of detailed static visualizations, including histograms, bar charts, and box plots, to summarize the dataset visually.
- **Seaborn**  
  Provided advanced statistical plots, including correlation heatmaps and distribution plots, to uncover patterns and relationships.
- **Plotly Express**  
  Empowered interactive visualizations, making it easier to explore data trends dynamically.

### 3. Machine Learning
- **Scikit-learn**  
  - Enabled robust data splitting using train-test splits to evaluate model performance.  
  - Supported the development of two key machine learning models (Random Forest Classifier) for predicting awareness and adoption.  
  - Provided metrics such as accuracy, precision, recall, F1-score, and confusion matrices to evaluate model performance comprehensively.
- **SimpleImputer**  
  Addressed missing values by imputing the most frequent values in categorical features, ensuring the dataset’s consistency.
- **LabelEncoder**  
  Encoded categorical features into numerical representations, making the data suitable for machine learning algorithms.
- **StandardScaler**  
  Scaled numerical data where applicable to improve model performance and training stability.

## Analytical Approach

The analytical journey was structured around a series of well-defined phases to ensure the rigor and reliability of insights:

### 1. Data Understanding and Exploration
- Conducted extensive EDA to identify trends, correlations, and anomalies in the dataset.  
- Investigated demographic distributions, awareness levels, and adoption behaviors using both static and interactive visualizations.  
- Detected and addressed outliers and missing values to improve data quality.  

### 2. Feature Engineering and Selection
- Identified and retained the most relevant features, such as perceived benefits, barriers, and socioeconomic indicators, based on domain knowledge and exploratory findings.  
- Removed noisy or irrelevant columns, including email and timestamp, to streamline the analysis.  

### 3. Model Development
- Built two predictive models:  
  - **Awareness Prediction Model**: Aimed to classify individuals as aware or unaware of cryptocurrency.  
  - **Adoption Prediction Model**: Focused on identifying the likelihood of cryptocurrency adoption based on individual perceptions and barriers.  
- Random Forest Classifier was chosen for its robustness and ability to handle categorical data effectively.  

### 4. Model Evaluation and Insights Generation
- Evaluated model performance using metrics such as accuracy (91% for awareness prediction and 88% for adoption prediction), precision, recall, and F1-score.  
- Generated confusion matrices and feature importance plots to interpret model predictions and the significance of various predictors.  

### 5. Visualization and Communication of Results
- Created comprehensive visual summaries, including feature importance charts, class distribution plots, and confusion matrices, to communicate findings effectively to stakeholders.  

This combination of tools and approaches ensured a thorough analysis, enabling the derivation of actionable insights and the development of reliable predictive models tailored to the unique context of Somalia’s cryptocurrency landscape.


## Recommendations

### For Policymakers
- Develop clear regulatory frameworks to address fraud and enhance transparency, thereby building public trust in cryptocurrency systems.  
- Launch targeted awareness campaigns through social media and community-based initiatives to educate the population on the benefits and safe use of cryptocurrency.  
- Establish a regulatory sandbox for piloting cryptocurrency projects, allowing innovation under controlled conditions.  

### For Businesses
- Integrate cryptocurrency services with widely used mobile payment platforms such as EVC Plus and E-Dahab, creating seamless digital financial ecosystems.  
- Design user-friendly interfaces and localized support to increase accessibility for less tech-savvy populations.  
- Implement incentive programs, such as discounts or rewards for early adopters, to drive initial adoption and build a loyal user base.  

### For Educational Institutions
- Introduce blockchain and cryptocurrency courses in curricula to prepare students for the evolving financial technology landscape.  
- Organize workshops and seminars focusing on the technical and practical applications of cryptocurrency.  
- Partner with technology hubs to provide hands-on training and certification programs for learners.  

### General Recommendations
- Focus on developing secure, mobile-friendly platforms to address technical barriers to adoption.  
- Collaborate with international cryptocurrency stakeholders to align Somalia’s adoption strategies with global best practices.  
- Use demographic data insights to design tailored strategies for increasing awareness and adoption among specific groups, such as women and rural populations.  

### Data Collection Insights
- The limited dataset collected for this study may result in imbalanced or biased models. To improve the robustness and accuracy of predictive models, collecting a larger and more representative dataset is essential. Expanding the dataset will help ensure balanced learning and minimize model biases.

