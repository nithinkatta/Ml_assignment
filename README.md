# Ml_assignment
<p>The Machine Learning project which is assigned by the GDSC(Gooogle Developers Student Club) of VNRVJIET.</p>
<p>The main aim of the project is to find</p>
<ul>
  <li>Accuracy</li>
  <li>Precision</li>
  <li>Sensitivity</li>
  <li>Specificity</li>
  <li>F-Score</li>
  <li>Balanced Score</li>
</ul>
<h1>Importing the packages</h1>
<p>Some of the important packages used to modify the dataset are</p> 
<ol>
  <li>numpy</li>
  <li>pandas</li>
  <li>sklearn</li>
</ol>
<br>
<h1> Performing EDA </h1>
<p> It is the process of modifying the dataset by performing data cleaning and data transformation </p>

<ul>
  <li>The unwanted columns are been removed from the dataset</li>
  <li>Null values are present in the columns are been removed</li>
  <li>The string and other type of data column also has be removed which are unnecessay for the data model and to make sure increase the accuracy</li>
  <li>Infinite data in the dataset are also been removed</li>
</ul>

<h1>Building Model</h1>
<p>Here comes the main machine learing model which produces the output based on the given input. The output of the input is generated based on the several training of ml model by giving instructions of input and ouput data
The Model trains and produces the output as user expected


Building a model is the main component in machine learning. The model used is a supervised machine learning model whose aim is to classify whether the flow is benign or type of attack if malacious. Machine learning model used is (2 sentences about xgb). The model is trained with 80% of the dataset and evaluated withthe remaining unseen 20% test data and achieved 81% accuracy.</p>


<h4>XGBoost</h4>
<p> It is one of the machine learing model used for scalable and highly accurate implementation of gradient boosting that pushes the limits of computing power for boosted tree algorithm</p>

<h3>Finding Accuracy,Precision,Recall,F1-Score,Balanced Accuracy</h3>
The calucation is done by using the sklearn.metrics packages. Where all the methods are available to calculate the above tasks. By considering the test case and the prediction given by the Ml model the calculations is done by passing parameters to the methods available in the package
<h1>Conclusion</h1>
<p> The overall project is done by inferring the youtube and some formulaes from the google. After gaining the perfect knowledge on correct modification of dataset I started modifying the dataset and accomplished all the tasks mentioned. </p>
