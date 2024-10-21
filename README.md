<h1>CAST, CONCAT, AND COALESCE Furniture Store Data</h1>



<h2>Description</h2>
Using SQL to clean furniture store data. The furniture store owner has asked us to look at purchases that occurred during their sales promotion period in December. Data obtained through Google Data Analytics Certificate program.  
<br />


<h2>SQL FUNCTIONS AND COMMANDS USED</h2>

- <b>CAST</b> 
- <b>BETWEEN</b>
- <b>ORDER BY</b>
- <b>ASC</b>
- <b>DESC</b>
- <b>CONCAT</b>
- <b>COALESCE</b>


<h2>Environment Used </h2>

- <b>BIG QUERY</b> 

<h2>Walk-through:</h2>

<p align="center">
1. used CAST to transform column named "date" which was incorrectly typed as a DATETIME datatype. Order purchases ascending by order data.   <br/>
<img src="https://i.imgur.com/9p1N7UA.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
2. Determine if customers prefer one couch color over others. Use CONCAT to create a unique key. <br/>
<img src="https://i.imgur.com/R1nUjXJ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
3. In rows where the "product" column is null, use COALESCE to display "product code" instead. <br/>
<img src="https://i.imgur.com/w31wkMO.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />

