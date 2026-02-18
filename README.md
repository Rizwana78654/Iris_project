<!DOCTYPE html>
<html lang="en">
<head>
<h1> Iris Classification Using KNN and Gaussian Naive Bayes</h1>

<div class="section">
<h2>Project Overview</h2>
<p>
This project presents the design and implementation of an Iris Flower Classification System 
using supervised machine learning algorithms structured with Object-Oriented Programming (OOP) principles in Python.
</p>
<p>The system classifies iris flowers into three species based on four measurable features:</p>
<ul>
    <li>Sepal Length</li>
    <li>Sepal Width</li>
    <li>Petal Length</li>
    <li>Petal Width</li>
</ul>
<p>The algorithms implemented manually are:</p>
<ul>
    <li>Gaussian Naive Bayes (GNB)</li>
    <li>K-Nearest Neighbors (KNN)</li>
</ul>
</div>

<div class="section">
<h2>Introduction</h2>
<p>
Machine Learning enables systems to learn patterns from data and make predictions without explicit programming.
The Iris dataset, introduced by Ronald Fisher in 1936, is one of the most widely used datasets for classification tasks.
It contains 150 samples equally distributed across three species:
</p>
<ul>
    <li>Iris-setosa</li>
    <li>Iris-versicolor</li>
    <li>Iris-virginica</li>
</ul>
</div>

<div class="section">
<h2>Problem Statement</h2>
<p>
Design and develop a structured classification system that predicts the species of an iris flower 
using its physical measurements while applying Object-Oriented Programming principles.
</p>
</div>

<div class="section">
<h2>Objectives</h2>
<ul>
    <li>Understand supervised learning concepts</li>
    <li>Analyze the Iris dataset</li>
    <li>Implement Gaussian Naive Bayes manually</li>
    <li>Implement K-Nearest Neighbors using Euclidean distance</li>
    <li>Evaluate model performance using statistical metrics</li>
    <li>Apply OOP principles such as encapsulation and modularity</li>
</ul>
</div>

<div class="section">
<h2>Dataset Description</h2>
<p>The dataset contains:</p>
<ul>
    <li>Total Samples: 150</li>
    <li>Number of Classes: 3</li>
    <li>Features: 4 numerical attributes</li>
    <li>Balanced Distribution: Yes</li>
</ul>

<h3>Features</h3>
<table>
    <tr>
        <th>Feature</th>
        <th>Description</th>
    </tr>
    <tr>
        <td>Sepal Length</td>
        <td>Length of sepal (cm)</td>
    </tr>
    <tr>
        <td>Sepal Width</td>
        <td>Width of sepal (cm)</td>
    </tr>
    <tr>
        <td>Petal Length</td>
        <td>Length of petal (cm)</td>
    </tr>
    <tr>
        <td>Petal Width</td>
        <td>Width of petal (cm)</td>
    </tr>
</table>
</div>

<div class="section">
<h2>Data Preprocessing</h2>
<ul>
    <li>Removal of unnecessary columns (ID)</li>
    <li>Label encoding of species names</li>
    <li>Separation of features (X) and target (y)</li>
    <li>Train-test split (80% training, 20% testing)</li>
</ul>
</div>

<div class="section">
<h2>Technologies Used</h2>
<ul>
    <li>Python</li>
    <li>Supervised Machine Learning</li>
    <li>Object-Oriented Programming (OOP)</li>
    <li>Statistical & Mathematical Concepts</li>
</ul>
</div>

<div class="section">
<h2>Tools & Libraries</h2>
<ul>
    <li>NumPy</li>
    <li>Pandas</li>
    <li>Scikit-learn (for evaluation metrics and train-test split)</li>
    <li>Math Module</li>
    <li>Pickle (optional for model saving)</li>
</ul>
</div>

<div class="section">
<h2>System Architecture</h2>
<ol>
    <li>Input Layer – Accepts dataset/sample input</li>
    <li>Preprocessing Layer – Cleans and prepares data</li>
    <li>Model Layer – Implements GNB and KNN</li>
    <li>Evaluation Layer – Computes performance metrics</li>
    <li>Output Layer – Displays predictions and results</li>
</ol>
</div>

<div class="section">
<h2>Algorithms Implemented</h2>

<h3>Gaussian Naive Bayes (GNB)</h3>
<ul>
    <li>Based on Bayes’ Theorem</li>
    <li>Assumes feature independence</li>
    <li>Uses Gaussian distribution for continuous data</li>
</ul>

<h3>K-Nearest Neighbors (KNN)</h3>
<ul>
    <li>Instance-based learning</li>
    <li>Uses Euclidean distance</li>
    <li>Majority voting among K neighbors</li>
</ul>
</div>

<div class="section">
<h2>Performance Evaluation Metrics</h2>
<ul>
    <li>Accuracy</li>
    <li>Confusion Matrix</li>
    <li>Precision</li>
    <li>Recall</li>
    <li>F1-Score</li>
</ul>
</div>

<div class="section">
<h2>Advantages of Using OOP</h2>
<ul>
    <li>Organized structure</li>
    <li>Code reusability</li>
    <li>Easy debugging</li>
    <li>Scalability</li>
    <li>Maintainability</li>
</ul>
</div>

<div class="section">
<h2>Applications</h2>
<ul>
    <li>Academic demonstrations</li>
    <li>Pattern recognition systems</li>
    <li>Agricultural data analysis</li>
    <li>Educational ML projects</li>
</ul>
</div>

<div class="section">
<h2>Conclusion</h2>
<p>
The Iris Flower Classification System successfully demonstrates the implementation of 
supervised machine learning algorithms using structured OOP principles.
Both Gaussian Naive Bayes and KNN achieved high classification accuracy, 
validating the correctness of the implementation and system design.
</p>
</div>

<div class="section">
<h2>References</h2>
<ul>
    <li>Iris Dataset</li>
    <li>Scikit-learn Documentation</li>
    <li>Python Official Documentation</li>
</ul>
</div>

</body>
</html>
