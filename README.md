# Volks
Leave Form
<!DOCTYPE html>
<html lang="en">
<head>
<title>CSS Template</title>
<style>
* {
  box-sizing: border-box;
}

body {
  font-family: 'Times New Roman', Times, serif, Arial, sans-serif;
  background-color: #fff;
  margin: 0; /* Remove default margin */
  padding: 0; /* Remove default padding */
}

/* Style the header */
header {
  background-color: #B3B6B7;
  text-align: center;
  font-size: 18px;
  color: black;
  padding: 10px 0;
}

/* Style the div */
.jackie {
  background-color: white;
  color: black;
  font-size: 20px;
  padding: 0px; /* Adjust padding */
  margin: 30px; /* Add margin for spacing */
  height: 420px;
  max-width: 70%; /* Limit max width */
  border: 4px solid rgb(240, 233, 233);
  border-radius: 10px;
}

/* Style the footer */
footer {
  background-color: #B3B6B7;
  padding: 9px;
  text-align: center;
  color: black;
  margin-bottom:1px;
}
.inputtext{
    margin:5px;
    background-color: rgb(248, 242, 242);
    height: 30px;
    width: 400px;
}
</style>
</head>
<body>

<header>
  <h2>Apply for Leave</h2>
</header>

<div class="jackie">
<form>
 <b><p style="text-align:center;">Apply for Leave</p></b>
 <table style="width:100%">
    <tr>
        <td>Name</td>
        <td></td>
      </tr>
    <tr>
      <td><input type="text" name="firstname" placeholder="First Name " class="inputtext"></td>
      <td><input type="text" name="lastname" placeholder="last Name " class="inputtext"></td>
    </tr>
    <tr>
      <td>Department</td>
      <td></td>
    </tr>
    <td>
      <select name="select_box_name" class="inputtext">
      <option value="ICT">ICT</option>
      <option value="Digital Marketing">Digital Marketing</option>
      <option value="Sales">Sales</option> 
      <option value="Procurement">Procurement</option>/* added a dropdown arrow to the department*/
  </select><br></td>
  <td></td>
    <tr>
      <td>Select Leave type</td>
      <td></td>
    </tr>
    <tr>
        <td>
            <select name="select_box_name" class="inputtext">
            <option value="Annual Leave">Annual Leave</option>
            <option value="Casual Leave">Casual Leave</option>
            <option value="Sick Leave">Sick Leave</option> 
        </select><br></td>
        <td></td>
      </tr>
      <tr>
        <td>From Date<input type="text" name="jackie" placeholder="From" class="inputtext"></td>
        <td>To Date<input type="text" name="jackie" placeholder="To" class="inputtext"><br></td>
      </tr>
      <tr>
        <td> Description</td>
        <td></td>
      </tr>
      <tr>
        <td><textarea rows="3" cols="40" class="inputtext">
        </textarea></td>
        <td> </td>
      </tr>
      <tr>
        <td><input type="submit" value="Apply"></td>
        <td></td>
      </tr>
  </table>
  </form>
</div>

<footer>
  <h1>Volks Elevator</h1>
</footer>
</body>
</html>
