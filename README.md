<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bank Application</title>
</head>
<body >
    
    <h1 style="text-align: center;">Bank Account Registation Form</h1>

    <hr>
    <h3>Basic Details:-</h3>
    <form>
        <label>Firstname:</label>
        <input type="text"name="Firstname" placeholder="Firstname.."required><br><br>
        <label>Middlename:</label>
        <input type="text"name="Middlename"placeholder="If Applicable.."><br><br>
        <label>Lastname:</label>
        <input type="text"name="Lastname" placeholder="Lastname.." required><br><br>
        <label>PhoneNumber:</label>
        <input type="text"name="PhoneNumber" placeholder="+918919113364"><br><br>
        <lable>Email:</lable>
        <input type="email"id="email" name="Email" placeholder="Your email adress.."><br><br>
        <lable>DOB:</lable>
        <input type="date"><br><br>

        Address:<br>
        <textarea cols="40 rows=30" value="Address" placeholder="Your permenant adress.."></textarea><br><br>
        <label>
            Gender:
        </label>
        <select>
            <option value="male">male</option>
            <option value="female">female</option>
            <option value="dontno">prefer not to say</option>
         </select><br><br>
         <label>
            Account Type:
            </label><br>
            <input type="radio" name="savings">savings<br>
            <input type="radio"name="current">current<br>
            <input type="radio"name="joint">joint<br><br>
            <input type="checkbox"name="checkbox">T&C<br><br>
            <input type="submit">  <input type="reset">
               
    </form>
</body>
</html>
