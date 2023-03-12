# <h1>Real-time Control</h1>


<h2>Description</h2>
This project dealt with the development of an application that would display data collected from the machines on the shop floor in Real-time. 

The organization for which I performed this project  had a lot of valuable information on the shop floor that it couldn't collect and analyze in an efficient manner.

<h4>Project Goals:</h4>
1. Creating visualizations with high frequency collection of data from the shop floor.<br />
2. Improving the control of production processes,Early detection of problems,Preventing    problems before they occur.<br />
3. Provide a convenient way for displaying and analyzing the data: The data will be properly collected and transformed with an ETL process. 
Before the project was carried out it was required to manually connect a large amount of raw data located in separate excel files. It was very difficult to do every time and perform the required analysis effectively. This project should help with this problem.
<br />

<h3></h3>
<br />
<h3></h3>
The first machine included in this project performs a coating of liquid silicone on paper which then goes through a cutting process (according to the width of paper that required in the order).

<br />
First, we would like to collect the data from the relevant sources. 
The sources are basically two systems which are Connected with the machine:<br />
1. System that measures the weight of the liquid material that is coated on the paper.<br />
2. System that measures the humidity of the paper while it’s going through the machine.<br />

<br />These systems extract a csv file every certain period of time to specific folders on their server.
<h3></h3>
<br />
<h4>Creating an ETL process</h4>
At this point we will actually want to Define an organized collection of all the csv files into one file,Performing transformations if necessary and finally loading the data into the application.
<br />
Every time we will look for the newest csv file in the folder and we will concatenate it with the old data that was already in the application before:
<br />
<br />
<a href="https://ibb.co/2hcf4pB"><img src="https://i.ibb.co/tKYWr15/etl1.jpg" alt="etl1" border="0"></a>





<h2>Languages and Utilities Used</h2>

- <b>PowerShell</b> 
- <b>Diskpart</b>

<h2>Environments Used </h2>

- <b>Windows 10</b> (21H2)

<h2>Program walk-through:</h2>

<p align="center">
Launch the utility: <br/>
<img src="https://i.imgur.com/62TgaWL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Select the disk:  <br/>
<img src="https://i.imgur.com/tcTyMUE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Enter the number of passes: <br/>
<img src="https://i.imgur.com/nCIbXbg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Confirm your selection:  <br/>
<img src="https://i.imgur.com/cdFHBiU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Wait for process to complete (may take some time):  <br/>
<img src="https://i.imgur.com/JL945Ga.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Sanitization complete:  <br/>
<img src="https://i.imgur.com/K71yaM2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Observe the wiped disk:  <br/>
<img src="https://i.imgur.com/AeZkvFQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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
