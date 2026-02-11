# GPL2026 Player Registration Form
<!DOCTYPE html>
<html>
<head>
<title>Cricket Player Registration</title>
<meta name="viewport" content="width=device-width, initial-scale=1">

<style>
body{
  font-family: Arial, sans-serif;
  background:#0f2027;
}
.form-box{
  max-width:480px;
  background:#fff;
  margin:30px auto;
  padding:20px;
  border-radius:10px;
}
h2{text-align:center;}
label{font-weight:bold; display:block; margin-top:12px;}
input,select{
  width:100%;
  padding:10px;
  margin-top:6px;
}
button{
  margin-top:20px;
  width:100%;
  padding:12px;
  background:#203a43;
  color:#fff;
  border:none;
  font-size:16px;
}
</style>
</head>

<body>

<div class="form-box">
<h2>🏏 Player Registration</h2>

<form>
<label>Full Name</label>
<input type="text" placeholder="Enter full name">

<label>Date of Birth</label>
<input type="date">

<label>Age</label>
<input type="number">

<label>Team Name</label>
<input type="text">

<label>Playing Role</label>
<select>
<option>Batsman</option>
<option>Bowler</option>
<option>All-Rounder</option>
<option>Wicket Keeper</option>
</select>

<label>Batting Style</label>
<select>
<option>Right Hand</option>
<option>Left Hand</option>
</select>

<label>Bowling Style</label>
<input type="text">

<label>Mobile Number</label>
<input type="tel">

<label>WhatsApp Number</label>
<input type="tel">

<button type="submit">Register</button>
</form>
</div>

</body>
</html>
