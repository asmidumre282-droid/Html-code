# Html-code
Html code
<!DOCTYPE html>
<html>
<head>
<title>Student Bio Data</title>
<style>
body{
    font-family: Arial, sans-serif;
    background:#f2f2f2;
}
.container{
    width:90%;
    max-width:500px;
    margin:auto;
    background:white;
    padding:20px;
    border-radius:10px;
    box-shadow:0 0 10px gray;
}
h1{
    text-align:center;
}
.photo{
    width:120px;
    height:120px;
    border:2px solid black;
    text-align:center;
    line-height:120px;
    margin:auto;
    margin-bottom:15px;
}
input{
    width:100%;
    padding:6px;
    margin:5px 0;
}
table{
    width:100%;
    border-collapse:collapse;
    margin-top:10px;
}
table,th,td{
    border:1px solid black;
    text-align:center;
    padding:5px;
}
progress{
    width:100%;
}
button{
    padding:8px 15px;
    margin-top:10px;
}
</style>
</head>

<body>
<div class="container">

<h1>Student Bio Data</h1>

<div class="photo">PHOTO</div>

<label>Name:</label>
<input type="text" value="Asmi Dumre" readonly>

<label>Class:</label>
<input type="text" value="11" readonly>

<label>Father:</label>
<input type="text" value="Arjun Dumre" readonly>

<label>Mother:</label>
<input type="text" value="Laxmi Dumre" readonly>

<label>Address:</label>
<input type="text" value="Sekham 5, Syangja, Sim" readonly>

<label>Contact:</label>
<input type="text" value="9768854631" readonly>

<h3>Hobby</h3>
<ol>
<li>Traveling</li>
<li>Writing</li>
<li>Singing</li>
</ol>

<h3>Education</h3>
<table>
<tr>
<th>S.N</th>
<th>Level</th>
<th>GPA</th>
<th>Remark</th>
</tr>
<tr>
<td>1</td>
<td>Grade 8</td>
<td>3.01</td>
<td>Pass</td>
</tr>
<tr>
<td>2</td>
<td>SEE</td>
<td>2.97</td>
<td>Pass</td>
</tr>
</table>

<h3>Language</h3>
Nepali <progress value="90" max="100"></progress><br>
Hindi <progress value="80" max="100"></progress><br>
English <progress value="75" max="100"></progress><br>

<center>
<button>Submit</button>
</center>

</div>
</body>
</html>
