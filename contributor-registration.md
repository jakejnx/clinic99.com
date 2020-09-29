---
layout: page
title: Contributor Registration
---
<h3>Clinical Role</h3>
<p>We are asking clinical experts in sexual health, cotnraception and HIV to take part in the discussion about what we need to include in the app.  We will also need some time to help test drive the new app.  Volunteering does not tie you to comit time, but we will be in touch to ask for help.  We expect that any discussion would take place over video call in future.</p>
<h3>Technical</h3>
<p>If you would like to learn new skills, or work with other technical occolleagues to help build a real world application we would very much like to hear from you.  Once you have completed the form we will be in touch shortly to find out more.</p>
<form name="contributor" method="POST" action="/registration-success" class="w3-container" netlify>
  <p>
  <label>Role you are applying for?</label>
  <input class="w3-radio" type="radio" name="role" value="clinical" checked>
<label>Clinical</label>

<input class="w3-radio" type="radio" name="role" value="technical">
<label>Technical</label></p>
  <p><label>First Name</label>
  <input class="w3-input" type="text" name="firstname"></p>
  <p>
  <label>Last Name</label>
  <input class="w3-input" type="text" name="lastname"></p>
  <p>
  <label>Email</label>
  <input class="w3-input" type="text" name="email"></p>
   <p> <label>Telephone</label>
  <input class="w3-input" type="text" name="tel"></p>
   <p> <label>Bio</label>
  <textarea name="bio" class="w3-input" rows="4" placeholder="eg: John has worked as a sexual health nurse in London for 8 years..." cols="50">
</textarea></p>
<p><input name="websitefeature" class="w3-check" type="checkbox" checked="checked">
<label>I wish to be featured on the website.</label></p>
<p><input name="int-property-disclaimer" class="w3-check" type="checkbox" checked="checked">
<label>I understand that contribuiting to the project is voluntary and does not result in payment or ownership of the system</label></p>
<p><button type="submit" class="w3-button w3-large w3-round w3-deep-orange">Register</button></p>

</form>