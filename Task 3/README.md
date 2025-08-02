<h1>Customer Churn Prediction – Internship Task 3</h1>

<h2>🌟 Task Objective</h2>
<p>
  The objective of this task was to build a machine learning model that predicts whether a customer will churn (i.e., stop using a service) based on various demographic, service-related, and behavioral attributes. This is a common business use case aimed at reducing customer loss and improving retention strategies.
</p>

<h2>🔍 Approach</h2>
<ol>
  <li><strong>Data Loading & Exploration</strong>
    <ul>
      <li>Imported the dataset and explored it using <code>pandas</code> and <code>matplotlib/seaborn</code> for visualization.</li>
      <li>Analyzed distributions, correlations, and identified potential predictors of churn.</li>
    </ul>
  </li>

  <li><strong>Data Preprocessing</strong>
    <ul>
      <li>Handled missing values and cleaned the dataset for consistency.</li>
      <li>Encoded categorical features using label encoding and one-hot encoding where appropriate.</li>
      <li>Scaled numerical features for better model performance.</li>
    </ul>
  </li>

  <li><strong>Model Building</strong>
    <ul>
      <li>Split the dataset into training and testing subsets.</li>
      <li>Trained multiple classification algorithms including:
        <ul>
          <li>Logistic Regression</li>
          <li>Decision Tree Classifier</li>
          <li>Random Forest Classifier</li>
          <li>XGBoost Classifier</li>
        </ul>
      </li>
    </ul>
  </li>

  <li><strong>Model Evaluation</strong>
    <ul>
      <li>Evaluated each model using metrics such as accuracy, precision, recall, F1-score, and ROC-AUC.</li>
      <li>Visualized performance using confusion matrices and ROC curves.</li>
    </ul>
  </li>
</ol>

<h2>📈 Results and Insights</h2>
<ul>
  <li>The dataset was well-structured and required minimal cleaning.</li>
  <li><strong>Random Forest</strong> and <strong>XGBoost</strong> models achieved the highest performance with balanced accuracy and recall, making them suitable for churn prediction.</li>
  <li>Feature importance analysis showed that monthly charges, tenure, and contract type were significant indicators of churn.</li>
  <li>The project highlights how predictive analytics can assist businesses in proactively managing customer relationships and reducing churn rates.</li>
</ul>
