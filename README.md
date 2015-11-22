# Yuvraj
<!DOCTYPE html>
<html>
<head>
<style>
body {
    background-color: #a6a6a6;
}

h1 {
    color: orange;
    text-align: center;
}

p {
    font-family: "Times New Roman";
    font-size: 40px;
}
</style>
</head>
<body>
<h1>HARRISBURG UNIVERSITY</h1>
</body>
<body>
<style>
p {
    color: red;
    text-align: center;
} 
</style>
<head>
<p>Student Portal</p>
</head>
</body>
<body>
<style>
p {
    color: red;
} 
</style>
<script>
function validateForm() {
    var x = document.forms["myForm"]["fname"].value;
    var y=document.forms["myForm"]["sname"].value;
    var z = document.forms["myForm"]["cname"].value;
    if (x == null || x == "") {
        alert("Full Name must be filled out");
        
    } else if (y == null || y == "") {
        alert("Email Id must be filled out");
        
    } else if (z == null || z == "") {
        alert("Phone Number must be filled out");
       
    } else{
	alert("Information have been submitted successfully");
}
}
</script>
</head>
<body>

<form name="myForm" method="post">
<h1> Please submit the below information: </h1>

<table id="Email Id">
<tr>
<td>Full Name:</td>
 <td> <input type="text" name="fname"> </td>
</tr>
<tr>
<td>
Email Id:</td>
<td> 
<input type="text" name="sname">
</td
</tr>
<tr>
<td>
Phone Number:</td>
<td> 
<input type="number" name="phone number">
</td
</tr>
<tr><td>
Address:</td>
<td>
<input type="text" name="address"/></td></tr>
<tr>
<td>
Country:</td>
<td> 
<select name="country">
<option selected="" value="Default">(Please select a country)</option>
<option value="AF">Australia</option>
<option value="AF">China</option>
<option value="AL">Canada</option>
<option value="AL">Pakistan</option>
<option value="AL">Singapore</option>
<option value="AF">Japan</option>
\<option value="DZ">India</option>
<option value="AS">Russia</option>
<option value="AD">USA</option>
</select>
</td
</tr>
<tr>
<td>
Zip Code:</td>
<td> 
<input type="number" name="zipcode">
</td
</tr>
<tr>
<td>
 <input type="submit" value="Submit" onclick="return validateForm()">
</td>
</tr>
</table>
</form>
</body>
</html>
