<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Registration Form</title>
</head>
<body>
    <fieldset>
    <legend>Name and Address</legend>
    <p>Dou you use CiviCRM
    <input type="radio" name="civicrm" value="yes">yes
    <input type="radio" name="civicrm" value="no">no
    (<a href="#">unslect</a>)
</p>
<p>
    how long you have been using CiviCRM?<br>
    <select>
        <option>--selcet--</option>
        <option>1 YEAR</option>
        <option>3 YEAR</option>
        <option>5 YEAR</option>
        </select>
</p>
<p>
    which CMS do you use ?<br>
    <select>
        <option>--selcet--</option>
        <option>Word Press</option>
        <option>Joomla</option>
        <option>Backdrop CMS</option>
    </select>
    </p>
<p>
    Your Skill Set <br>
    
    <select>
        <option>--select--</option>
        <option>Frontend Developer</option>
        <option>Backend Developer</option>
        <option>Full-Stack Developer</option>
        </select>
</p>
<p>
    email* <br>
    <input type="email" name="email">
</p>
<p>
    First Name* <br>
    <input type="text" name="first name">
</p>
<p>
    Last Name* <br>
    <input type="text" name="Last name"> <br>
    <small>First and last name will be shared with other visitors to the site.</small>
</p>
<p> State (home) <br>
<select>
    <option>--select--</option>
    <option>Punjab</option>
    <option>Sindh</option>
    <option>KPK</option>
    <option>Balochistan</option>
    <option>Islamabad</option>
    </select>
</p>
<input type="submit" value="save">
<input type="reset" name="cancel" >
</fieldset>
</body>
</html>
