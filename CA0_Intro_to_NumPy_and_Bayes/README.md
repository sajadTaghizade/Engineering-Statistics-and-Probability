<div align="center">
  <h1>
    🎲 Engineering Statistics & Probability - Computer Assignment 0  Bayes
  </h1>
  <h2>
    Introduction to NumPy and Naive Bayes Classifier
  </h2>
  <p>
    This project is the introductory assignment for the Engineering Statistics and Probability course. It is designed to provide a practical understanding of the <strong>NumPy</strong> library and to apply the <strong>Bayes' theorem</strong> for a real-world classification task.
  </p>
</div>

<hr>

## 🚀 Problems Overview

<table>
  <tr>
    <td valign="top" width="50%">
      <h3>
        Problem 1: NumPy Basics
      </h3>
      <p>
        This part serves as a hands-on introduction to the fundamental concepts and operations of the NumPy library, a cornerstone for numerical computing in Python. The task involves completing specified functions in a provided Python script (<code>numpy_basic.py</code>).
      </p>
    </td>
    <td valign="top" width="50%">
      <h3>
        Problem 2: Majority Vote Analysis
      </h3>
      <p>
        An exploration of the "majority vote" decision-making process. This problem uses simulation to analyze how the accuracy of individual voters (p) and the total number of voters (n) affect the overall accuracy of the final decision.
      </p>
      <details>
        <summary>
          <strong>Key Analyses</strong>
        </summary>
        <ul>
          <li>
            Calculating the probability of a correct majority vote under different scenarios.
          </li>
          <li>
            Plotting the relationship between individual accuracy (p) and overall accuracy.
          </li>
          <li>
            Using a heatmap to visualize the combined effect of 'p' and 'n' on decision accuracy.
          </li>
        </ul>
      </details>
    </td>
  </tr>
  <tr>
    <td valign="top" width="100%" colspan="2">
      <h3>
        Problem 3: Spam Email Detection with Naive Bayes
      </h3>
      <p>
        The main part of the assignment involves building a <strong>Naive Bayes classifier</strong> from scratch to distinguish between spam and non-spam (ham) emails. The project follows a complete machine learning pipeline from data preprocessing to model evaluation.
      </p>
      <details>
        <summary>
          <strong>Implementation Pipeline</strong>
        </summary>
        <ol>
          <li>
            <strong>Data Preprocessing</strong>: Cleaning the raw email text by lowercasing, removing punctuation, and handling stop words.
          </li>
          <li>
            <strong>Train-Test Split</strong>: Dividing the dataset to properly train and evaluate the model.
          </li>
          <li>
            <strong>Bag of Words (BoW) Model</strong>: Creating a frequency-based BoW matrix from the training data to calculate the required probabilities (P(word|class) and P(class)).
          </li>
          <li>
            <strong>Prediction</strong>: Using the calculated probabilities and Bayes' theorem to classify emails in the test set and measuring the model's accuracy.
          </li>
          <li>
            <strong>Advanced Topics</strong>: Implementing techniques like <strong>Laplace Smoothing</strong> to handle unseen words and using <strong>log probabilities</strong> to prevent underflow issues with long emails.
          </li>
        </ol>
      </details>
    </td>
  </tr>
</table>

<hr>

