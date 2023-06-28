<html>
<head>
  <title>Document</title>
  <style>
    *
    {
      margin: 0;
      padding: 0;
    }
    body
    {
      padding: 120px 400px;
      font-family: sans-serif;
    }
    .container
    {
      border: solid black 1px;
      border-radius: 5px;
      box-shadow: 10px 10px lightgray;
      padding-left: 70px;
      padding-right: 70px;
      display: inline-block;
      box-shadow: 2px;
      height: 450px;
    }
    .container h1
    {
      text-align: center;
      margin-bottom: 60px;
      margin-top: 50px;
    }
    .container label
    {
      font-size: 20px;
    }
    .container input
    {
      width: 100%;
      height: 35px;
      margin-top: 10px;
      margin-bottom: 25px;
      font-size: 18px;
      border: solid gray 0.5px;
      background-color: rgb(243, 239, 239);
      padding-left: 8px;
    }
    .container input:focus
    {
      background-color: lightgray;
    }
    .container button
    {
      font-family: sans-serif;
      font-size: 20px;
      width: 100%;
      height: 35px;
      margin-top: 40px;
      background-color: lightgreen;
      border: solid 1px darkgreen;
      border-radius: 10px;
    }
    .container button:hover
    {
      background-color:limegreen;
      color: white;
    }
  </style>
</head>
<body>
  <div class = "container">
    <h1>Login Form</h1>
    <label for="">Username</label>
    <input type="text" id ="user">
    <label for="">Password</label>
    <input type="password" id ="pass">
    <button onclick='f1()'>Sign in</button>
  </div>
  <script>
    function f1()
    {
      var user = document.getElementById("user").value;
      var password = document.getElementById("pass").value;
      
      if(user == "kane" && password == "tagay")
      {
        alert("You have successfully log in");
      }
      else
      {
        alert("Wrong Email/Password");
      }
    }
  </script>
</body>
</html>
