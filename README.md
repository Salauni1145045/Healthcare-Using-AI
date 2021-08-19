# Healthcare-Using-AI
<p>Basically, in this project, I have developed a deep learning model which can detect Covid-19 virus of patients using their X-Rays.</p>
<h3>Description</h3><hr>
<p>Increases in technology have given rise to a myriad of new sectors, such as artificial intelligence, which has revolutionised several fields, including healthcare. The COVID-19 virus has spread throughout the world in 2019. And
as the number of Covid-19 patients rises, the capacity of the Covid-19 test kits available at the hospital decreases, requiring the use of cutting-edge technology to detect and combat the pandemic. So in this paper, deep learning model is used on covid-19 dataset along with image augmentation techniques for detecting covid-19 disease</p>
<p>
To implement this experiment I have used ImageDataGenerator function for extracting edge features. Then I have used convolutional neural networks for further feature extraction and classification. Using this model I got 78.91% training accuracy and 73.81% validation accuracy by using 10 epochs.</p>
<h3>Methodology Flowchart</h3><hr>![methodology](https://user-images.githubusercontent.com/89153990/129986847-0f85e168-1f20-42ec-9926-1afb4035fc14.png)

<h3>Getting Started</h3><hr>
<b>Dependencies</b>
 <ul>
<li>Pandas</li>
<li>Numpy</li>
<li>Keras</li>
<li>Tensorflow</li>
<li>Matplotlib</li>
</ul>
<b>Language Used</b>
 <ul>
<li>Python : version above 3.0</li>
</ul>
<h3>Dataset Description</h3><hr>
I have used dataset containing Covid-19 patients X-Rays image files and Normal patients X-Rays image files. And it can be downloaded from <a href="https://www.kaggle.com/kristiyanlaoli/detecting-covid-19-from-chest-x-ray">here</a>
<h3>Manifest</h3><hr>
Final_Project.ipynb / Final_Project.py :
<div>
  <ul>
    <li>Code for Image Augmentation</li>
    <li>Code for CNN Model</li>
    <li>Code to train and validate model</li>
    <li>Code to plot the results</li>
  </ul>
  </div>
<h3>Executing program</h3><hr>
<p>Downloaded dataset from given link.<br>
If using local machine download libraries given in dependencies.<br>
If the running environment is google colab just make a folder on the drive named "covid" and put the downloaded dataset into it.</p>
<ul><li>Method 1 (For colab):<br>Download and run Final_Project.ipynb file which will execute the program.</li>
<li>Method 2 (For local machine):<br>
Run Final_Project.ipynb to execute the whole project in the local machine. Make sure you change all the paths given in code according to your local machine.</li></ul>
<h3>Results</h3><hr>
<p>Accuracy for training and validation set and Loss for training and validation dataset can be found in Results folder.</p>
<h3>Authors</h3><hr>
Salauni Shah <br>
Feel free to contact me at <a href="mailto:sshah19@lakeheadu.ca">sshah19@lakeheadu.ca</a>
<h3>License</h3><hr>
This Project is not Licensed
<h3>Project Status</h3><hr>
Project is completed but improvements can be made in terms of accuracy.
