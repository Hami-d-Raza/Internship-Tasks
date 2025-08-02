<h1>Credit Risk Prediction – Internship Task 2</h1>

<h2>🌟 Task Objective</h2>
<p>
  The goal of this task was to build a predictive model that can assess the creditworthiness of loan applicants and classify them as either "Low Risk" or "High Risk" based on various financial and personal attributes.
</p>

<h2>🔍 Approach</h2>
<ol>
  <li><strong>Data Loading & Exploration</strong>
    <ul>
      <li>Loaded the credit risk dataset using <code>pandas</code>.</li>
      <li>Explored the structure of the data, checked for null values, and examined feature distributions.</li>
      <li>Performed basic visualization to understand correlations and patterns.</li>
    </ul>
  </li>

  <li><strong>Data Preprocessing</strong>
    <ul>
      <li>Handled missing values by imputing with appropriate strategies.</li>
      <li>Encoded categorical variables using label encoding and one-hot encoding where necessary.</li>
      <li>Standardized numerical features to improve model performance.</li>
    </ul>
  </li>

  <li><strong>Model Building</strong>
    <ul>
      <li>Split the dataset into training and testing sets (e.g., 80/20 ratio).</li>
      <li>Trained multiple classification algorithms:
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
      <li>Evaluated models using accuracy, precision, recall, F1-score, and confusion matrices.</li>
      <li>Compared performance to select the best-performing model.</li>
    </ul>
  </li>
</ol>

<h2>📈 Results and Insights</h2>
<ul>
  <li>After data preprocessing and model tuning, the classification models performed well on the test data.</li>
  <li><strong>Random Forest</strong> and <strong>XGBoost</strong> delivered the highest accuracy and balanced precision-recall scores.</li>
  <li>Insights from feature importance analysis revealed that attributes like income, credit history, and loan amount significantly influenced predictions.</li>
  <li>The project demonstrated how ML techniques can assist in real-world financial decision-making processes.</li>
</ul>
