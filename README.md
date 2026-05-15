<h1>Electric Vehicle Population Analysis</h1>

 ## [kaggle Ev Dataset](https://www.kaggle.com/datasets/fatmanur12/electric-vehicle-population/data)
 
<h2>General Dataset Information</h2>

<h3>Description:</h3>
U.S based electric vehicle registration data including make, model year of vehicles, location of vehicles, vehicle type, clean fuel eligibility and other identifying variables

<h2>Dataset Details:</h2>

- <b>Rows: 130,000</b> 
- <b>Columns: 10</b> 
- <b>Size: 1,200 kb (1.2 mb)</b> 
- <b>Source: [Electric Vehicle Population Analysis](https://www.kaggle.com/datasets/fatmanur12/electric-vehicle-population/data)

<h2>Data Profile:</h2>


<h4> 1. Applied filters to review entries per column</b>
<h4> 2. Checked for:</b>
  
- <b>consistent state and make name ( e.g. “Tesla motor” vs “Tesla”)</b>
- <b>Missing or blank fields.</b>
<h4> 3. Notable features:

  
- <b>Electric Vehicle Types: Battery electric vehicle (BEV), plug-in Hybrids electric vehicle (PHEV)
- <b>Over 50 different vehicle makes</b>
- <b>Model years span e.g 1997-2023</b>
<h4> 4. Recorded Inconsistencies:</b>

  
- <b>Variability in manufacturer name capitalization and spacing</b>
- <b>Missing values in electric range, model year and location</b>


<h2>Data Wrangling:</h2>


<h4> 1.Cleaned inconsistent manufacturer names (e.g “Tesla Motors” vs “Tesla”)</b>
<h4> 2.Converted model year to numeric data type and removed missing years</b>
<h4> 3.Removed rows with missing state or make</b>
<h4> 4.Created a new columns for analyzing:</b>
  
- <b>Vehicle age: Derived by subtracting model year from 2024</b>
- <b>is bev: - Boolean flag for battery electric vehicles</b>
<h4> 5.Filtered dataset to include only complete entries for core analysis</b>
<h4> 6.Optional: Created “ Top Makes” subset based on frequency count</b>



<h2>Data table:</h2>

<p align="center">
 <br/>
 <img src="https://github.com/Dan-Dee-analyst/Data-Curation/blob/main/Screenshot%202026-05-15%20at%2010.02.23.png?raw=true" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />


<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
