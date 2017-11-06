<!doctype html>
<html>
<head>
	<title>Tabbed Form</title>
	<script src="js/jquery.js" type="text/javascript"></script>
	<script src="js/animation.js" type="text/javascript"></script>
	<script src="js/validation.js" type="text/javascript"></script>
	<link rel="stylesheet" href="css/style.css" type="text/css" />
</head>
<body>

<form name="myform" onsubmit="return validateForm()">
<ul>
	<li class="title">Who Are You?</li>
	<li class="fields">
		<label>*First Name:</label><br />
		<input id="first_name" class="req" type="text" /><br />
		<label>Middle Name:</label><br />
		<input id="middle_name" type="text" /><br />
		<label>Last Name:</label><br />
		<input id="last_name" type="text" /><br />
		<label>*Email:</label><br />
		<input id="email" class="req" type="text" /><br />
	</li>
	<li class="title">Where Are You?</li>
	<li class="fields">
		<label>City:</label><br />
		<input id="city" type="text" /><br />
		<label>*State:</label><br />
		<input id="state" class="req" type="text" /><br />
		<label>Country:</label><br />
		<input id="country" type="text" /><br />
	</li>
	<li class="title">What Do You Do?</li>
	<li class="fields">
		<label>
		*Occupation:</label><br />
		<input id="occupation" class="req" type="text" /><br />
		<label>Company:</label><br />
		<input id="company" type="text" /><br />
		<label>Company Location:</label><br />
		<input id="location" type="text" /><br />
	</li>
</ul>
<input type="submit" value="Submit Form" />
</form>

</body>
</html>







