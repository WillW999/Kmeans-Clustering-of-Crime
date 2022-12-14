<h1>K-means Clustering of Crime Locations in Chicago</h1>

<h2>Description</h2>
Using a dateset of crime locations based on their latitude and longitude. Using this data I am able to cluster these data points into crime clusters, giving chicago PD some important information on to where they should be allocating personnel. 
<br />


<h2>Environment and Packages Used</h2>

- <b>DataBricks</b>
- <b>Pandas</b> 
- <b>Numpy</b>
- <b>Kmeans from Sklearn</b>

<h2>Project walk-through:</h2>

<p align="center">
Importing of packages and dataset: <br/>
<img src="https://i.imgur.com/3En8xCC.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Splitting dataset into test and train:  <br/>
<img src="https://i.imgur.com/ZSVRSZJ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Converting dataset to RDD Array: <br/>
<img src="https://i.imgur.com/qe19uqX.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Elbow method to find optimal amount of clusters:  <br/>
<img src="https://i.imgur.com/9tq4Gk8.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Cluster the datapoints:  <br/>
<img src="https://i.imgur.com/NrrF2J0.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Showing cluster assingment by point as well as cluster centers:  <br/>
<img src="https://i.imgur.com/dgPtrag.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Actual cluster locations in Chicago:  <br/>
<img src="https://i.imgur.com/486ye9G.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
