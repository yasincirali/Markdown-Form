# New Document


<button onclick="window.location.href='https://bing.com';">+New User</button>
<p align="right">
  <input type="button" value="Save User" disabled />
</p>

- [x] Hide Disabled User 


<div>

|ID|User Name   |Email   |Enabled   |
|---|---|---|---|
| 1  |AdminUser  | admin@piworks.net  |true   | 
| 2  |TestUser   | testuser@piworks.net  |true   | 


>New User 
<html>
  <head>
    <title>Title of the document</title>
    <style>
      div {
        margin-bottom: 10px;
      }
      label {
        display: inline-block;
        width: 110px;
        color: #777777;
      }
      input {
        padding: 5px 10px;
      }
    </style>
  </head>
  <body>
    <form action="/form/submit" method="post">
      <div>
        <label for="name">Username:</label>
        <input id="name" name="username" type="text" autofocus />
      </div>
      <div>
        <label for="lastname">Display Name:</label>
        <input id="lastname" name="lastname" type="text" />
      </div>
      <div>
        <label for="lastname">Phone:</label>
        <input id="lastname" name="lastname" type="text" />
      </div>
      <div>
        <label for="lastname">Email:</label>
        <input id="lastname" name="lastname" type="text" />
      </div>
      <div>
        <label for="lastname">User Roles:</label>
        <select class="form-control cell-control-select cell-control">
          <option>Guest</option>
          <option>Admin</option>
          <option>Super Admin</option>
          </select>
      </div>
      <div>
        <label for="lastname">Enabled:</label>
        <input type="radio" id="male" name="gender" value="male">
      </div>          
    </form>
  </body>
</html>