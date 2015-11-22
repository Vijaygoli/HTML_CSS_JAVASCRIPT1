# HTML_CSS_JAVASCRIPT1
<!DOCTYPE html>
<html>
<head>
<style>
body {
    background-color: #ff3399;
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
<h1>PATH TRAINS ONLINE TICKET RESERVATION SYSTEM -NJ/NY</h1>
</body>
<body>
<style>
p {
    color: red;
    text-align: center;
} 
</style>
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
		
	} else if (z == null || z == "") {
        alert("Credit Card No. must be filled out");
    } else if (z == null || z == "") {
        alert("Credit Card No. must be filled out");		
    } else{
	alert("Your Reservation is Confirmed. Happy Journey..Thank You");
}
}
</script>
</head>
<body>

<form name="myForm" method="post">
<h1> Arrival-Destination: Newark, NJ-33rd st, NY </h1>
<table id="Email Id">
<tr>
<tr>
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
Credit Card No:</td>
<td>
<input type="text" name="address"/></td></tr>
<tr><td>
Billing Address:</td>
<td>
<input type="text" name="address"/></td></tr>
<tr>
<td>
State:</td>
<td>
<select name="state">
<option selected="" value="Default">(Please select a country)</option>
<option value="AD">NJ</option>
<option value="AD">NY</option>
<option value="AD">PA</option>
<option value="AD">CA</option>
<option value="AD">TX</option>
</select>
</td>
<tr>
<td>
Country:</td>
<td> 
<select name="country">
<option selected="" value="Default">(Please select a country)</option>
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
</tr>
</tr>
<td>
 <input type="submit" value="Submit" onclick="return validateForm()">
</td>
</tr>
</table>
</form>
</body>
</html>
