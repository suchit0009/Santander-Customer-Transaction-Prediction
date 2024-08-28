# Santander-Customer-Transaction-Prediction

<h3>Overview</h3>
This project is part of my learning journey in machine learning. Inspired by the Kaggle competition "Santander Customer Transaction Prediction," the goal is to predict which customers will make a specific transaction in the future. The competition's challenge is a binary classification problem, providing a valuable opportunity to apply and deepen my understanding of data science techniques.

<h3>Learning Objective</h3>
The primary purpose of this project was educational. Throughout this process, I aimed to:

- <strong>Understand the end-to-end data science workflow:</strong> from data loading and exploration to preprocessing, modeling, and evaluation.
- <strong>Learn from the best:</strong> I studied and adapted techniques from publicly available notebooks and resources to ensure I followed industry best practices.
- <strong>Apply theoretical knowledge:</strong> I implemented models and techniques learned during my studies, focusing on understanding their practical applications.

<h3>Project Details</h3>

<h4>Problem Statement</h4>
Santander Bank aims to identify customers who will make a specific transaction in the future

<h4>Dataset</h4>
The dataset was provided as part of the Kaggle competition. It includes a training set with anonymous features indicating whether a transaction was made and a test set where predictions are to be made. These data can be accessed through the <a href="https://www.kaggle.com/c/santander-customer-transaction-prediction">Kaggle competition page</a>.

<h4>Approach and Workflow</h4>
<ol>
  <li><strong>Data Loading:</strong> </li>
  <li><strong>Data Preprocessing:</strong></li>
  <li><strong>Exploration:</strong></li>
  <li><strong>Data Visualization:</strong></li>
  <li><strong>Feature Engineering:</strong></li>
  <li><strong>Data Augemtation:</strong></li>
  <li><strong>Modeling:</strong></li>
</ol>

<h3>Results and Insights</h3>
Models were evaluated based on their ROC-AUC scores. We tested the LGBM model under three different conditions:
- **Simple Features**: Basic feature set without complex engineering.
- **Complex Feature Engineering**: Added "magic features" and other complex transformations.
- **Data Augmentation**: Addressed data imbalance using data augmentation techniques.

<table>
  <thead>
    <tr>
      <th>Model Configuration</th>
      <th>ROC-AUC Score</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Simple Features</td>
      <td>0.89930 </td> <!-- Replace with actual score -->
    </tr>
    <tr>
      <td>Complex Feature Engineering</td>
      <td>0.92137</td> <!-- Replace with actual score -->
    </tr>
    <tr>
      <td>Data Augmentation</td>
      <td>0.91036 </td> <!-- Replace with actual score -->
    </tr>
  </tbody>
</table>

<strong>Insights Gained:</strong> Through this project, I gained a deeper understanding of the importance of feature engineering, data augmentation, and preprocessing in improving model accuracy. The balance between model complexity and performance was also a key takeaway.

<h4>References</h4>
- <a href="https://www.kaggle.com/code/yag320/list-of-fake-samples-and-public-private-lb-split">Yag320's List of Fake Samples and Public/Private LB Split</a>
- <a href="https://www.kaggle.com/code/jiweiliu/lgb-2-leaves-augment">Jiwei Liu's LGB 2 Leaves Augment</a>
- <a href="https://medium.com/analytics-vidhya/santander-customer-transaction-prediction-an-end-to-end-machine-learning-project-2cb763172f8a">Santander Customer Transaction Prediction: An End-to-End Machine Learning Project</a>
- <a href="https://medium.com/@skshashankkumar41/santander-customer-transaction-prediction-44ab30d2236c">Santander Customer Transaction Prediction </a>
