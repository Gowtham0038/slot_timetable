# Ex03 Time Table
## Date:

## AIM
To write a html webpage page to display your slot timetable.

## ALGORITHM
### STEP 1
Create a Django-admin Interface.

### STEP 2
Create a static folder and inert HTML code.

### STEP 3
Create a simple table using ```<table>``` tag in html.

### STEP 4
Add header row using ```<th>``` tag.

### STEP 5
Add your timetable using ```<td>``` tag.

### STEP 6
Execute the program using runserver command.

## PROGRAM
```
<!DOCTYPE html>
<html lang="en">
<head>
<title>Saveetha Engineering Collage Time Table</title>    
<style>
body{
    font-family: sans-serif;
    margin:0;
    padding: 0;
    display: flex;
    justify-content: center;
    align-items: center;
    min-height: 100vh;
    background-color: #f0f0f0;
}
div-container{
    width: 800px;
    background-color: #fff;
    border-radius: 10px;
    box-shadow: 0 4px 8px rgba(0,0,0,0.1);
    padding:20px;
    text-align: center;
}
header{
    background-color: #283747;
    color: white;
    padding: 20px;
    border-radius:10px 10px 0 0;
}
header img{
    max-width: 100px;
    vertical-align: middle;
    margin-right: 20px ;
}
header h1{
    display: inline-block;
    vertical-align: middle;
    margin: 0;
    font-size: 2em;
}
header span{
    float: right;
    font-size: 1.5em;
    margin-top: 10px;
}
table {
  width: 100%;
  border-collapse: collapse;
  margin-top: 20px;
}

table, th, td {
  border: 1px solid #ddd;
  padding: 8px;
  text-align: left;
}

table th {
  background-color: #f2f2f2;
}

table tr:nth-child(even) {
  background-color: #f9f9f9;
}

table tr:hover {
  background-color: #f1f1f1;
}

table-subjects {
  margin-top: 30px;
}

table-subjects th, table-subjects td {
  text-align: left;
}
</style>
</head>
<body>

<div class="div-container">
  <div class="header">
    <img src="https://via.placeholder.com/100" alt="College Logo"> 
    <h1>SAVEETHA AUTONOMOUS ENGINEERING COLLEGE</h1>
    <span>TNEA CODE 1216</span>
  </div>
  <p>Approved by AICTE | Affiliated to Anna University</p>

  <h2>SLOT TIME TABLE - GOWTHAM C (21224240046)</h2>

  <table class="table">
    <tr>
      <th>Day/Time</th>
      <th>Monday</th>
      <th>Tuesday</th>
      <th>Wednesday</th>
      <th>Thursday</th>
      <th>Friday</th>
    </tr>
    <tr>
      <td>8-10</td>
      <td></td>
      <td>FREE SLOT</td>
      <td>PHY</td>
      <td>CHE</td>
    </tr>
    <tr>
      <td>10-12</td>
      <td>GER</td>
      <td>FREE SLOT</td>
      <td>FWAD</td>
      <td>FWAD</td>
      <td>PHY</td>
    </tr>
    <tr>
      <td>12-1</td>
      <td colspan="5">LUNCH</td>
    </tr>
    <tr>
      <td>1-3</td>
      <td>FREE SLOT</td>
      <td></td>
      <td>MAT</td>
      <td>MAT</td>
      <td>SS</td>
    </tr>
    <tr>
      <td>3-5</td>
      <td>FREE SLOT</td>
      <td></td>
      <td>GER</td>
      <td>CHE</td>
      <td>FWAD</td>
    </tr>
  </table>

  <table class="table table-subjects">
    <tr>
      <th>S. No.</th>
      <th>Subject Code</th>
      <th>Subject Name</th>
    </tr>
    <tr>
      <td>1.</td>
      <td>19AI414</td>
      <td>Fundamentals of Web Application Development (FWAD)</td>
    </tr>
    <tr>
      <td>2.</td>
      <td>19EN612</td>
      <td>German Basic (GER)</td>
    </tr>
    <tr>
      <td>3.</td>
      <td>19PH206</td>
      <td>Physics for Information Technology (PHY)</td>
    </tr>
    <tr>
      <td>4.</td>
      <td>19CY205</td>
      <td>Principles of Chemistry in Engineering (CHE)</td>
    </tr>
    <tr>
      <td>5.</td>
      <td>19MA201</td>
      <td>Calculus and Matrix Algebra (MAT)</td>
    </tr>
    <tr>
      <td>6.</td>
      <td>19EY701</td>
      <td>Soft Skills (SS)</td>
    </tr>
    </style>
</head>
<body>
    
</body>
</html>
```

## OUTPUT
![Screenshot 2025-03-13 093707](https://github.com/user-attachments/assets/47c5a011-54ea-4709-8750-d633456f3589)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.

