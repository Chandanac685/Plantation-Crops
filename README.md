<!DOCTYPE html>
<html>
  <head>
    <title>Registration Form</title>
  </head>
  <body>
    <form>
      <input type="text"placeholder="Your Name"required><br/><br/>
      Gender:
      <input type="radio"name="gender"value="Male">Male
      <input type="radio"name="gender"value="Female">Female
      <input type="email"placeholder="Email Address"required><br/><br/>
      Date of Birth<br/>
      <input type="date"><br/><br/>
      <input type="password"placeholder="Password"><br/><br/>
      Select your University<br/>
      <select>
        <option>Kannur University</option>
        <option>Calicut University</option>
        <option>MG University</option>
        <option>Kerala University</option>
      </select><br/><br/>
      Languages Known<br/>
      <input type="checkbox"name="language"value="English">English
      <input type="checkbox"name="language"value="Hindi">Hindi
      <input type="checkbox"name="language"value="Malayalam">Malayalam
      <input type="submit">
    </form>
  </body>
</html>
