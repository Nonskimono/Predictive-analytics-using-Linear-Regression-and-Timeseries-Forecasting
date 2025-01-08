<h1>Chukwunonso - Predictive-analytics-using-Linear-Regression-and-Timeseries-Forecasting</h1>

<h2>Description</h2>
This project involved using different predictive models to predict the number of crypto-currency websites. Linear regression and timeseries forecasting were the predictive techniques employed for this project. In terms of the linear regression, the hypothesis was Bitcoin price, on its own, can be used to predict the number of crypto-currency websites created. Hence, this was examined and tested.
<br />


<h2>Languages and Utilities Used</h2>

- <b>Python</b>
- <b>SQL</b>

<h2>Environments Used </h2>

- <b>Windows 11</b> (21H2)

<h2>Project walk-through:</h2>

<p align="center">
Data collection 1 (Web-scraping): <br/>
<img src="https://imgur.com/1kL5RHa.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://imgur.com/dPUcQVR.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://imgur.com/Df8fsOx.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<br />
<br />
Data collection 2 (Using SQL to query data lake):  <br/>
<img src="https://imgur.com/l1fQYye.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />

<br />
Renaming columns so they match for join: <br/>
<img src="https://imgur.com/3XriViP.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://imgur.com/ufUECsG.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://imgur.com/5daxwj5.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://imgur.com/0A3fdAg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />

<br />
Concatenating datasets into one and dropping duplicates:  <br/>
<img src="https://imgur.com/LEu2smC.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://imgur.com/Jysxxv0.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />

<br />
Data exploration showing minimal correlation between Bitcoin and Website count:  <br/>
<img src="https://imgur.com/ElLeZyF.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />

<br />
Combining Cryptocurrency and website datasets into one:  <br/>
<img src="https://imgur.com/gbNnWN8.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://imgur.com/yxsFKdg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />

<br />
Bulding first linear regression model:  <br/>
<img src="https://imgur.com/XiGuGCe.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />

<br />
Using correlation to find useful features:  <br/>
<img src="https://imgur.com/sqRqIZJ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />

<br />
Adding features with correlation to improve linear regression model (2nd model):  <br/>
<img src="https://imgur.com/caaEFFR.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />

<br />
Removing outliers/Feature engineering to improve linear regression model:  <br/>
<img src="https://imgur.com/vdx5jHi.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
[<img src="https://imgur.com/5ucXIMZ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />

<br />
Optimised model:   <br/>
<img src="https://imgur.com/3B4whTN.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://imgur.com/DBvMuhk.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br/>

<br />
Data exploration:  <br/>
<img src="https://imgur.com/rssJe60.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />

<br />
Downsampling data to weeks for smoothening:  <br/>
<img src="https://imgur.com/nDYYoSA.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://imgur.com/GifMrfa.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<br />

<br />
Further data exploration to check for seasonality/trends:
  <br/>
<img src="https://imgur.com/sKPOPDl.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />

<br />
Timeseries model (Blue line - actual data, yellow - prediction against actual data, red - forecast:  <br/>
<img src="https://imgur.com/pNWilc3.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />

<br />
Timeseries model evaluation:  <br/>
<img src="https://imgur.com/gqYqiNS.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />

<h2>Results</h2>
This project:
A) Spearheaded a strategic initiative to enhance the efficiency of financial crime detection through the development and implementation of an semi-automated risk assessment system
B) Achieved a 75% reduction in the time required to investigate potential risks associated with postcodes
C) Demonstrated a 30% increase in the accuracy of risk identification, minimizing false positives and false negatives



<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
