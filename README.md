<!DOCTYPE html>
<html>
<head>
  <title>Login Page</title>
  <style>
    /* Add CSS for a fancy design here */
    /* CSS for the globe */
    .globe {
      width: 200px;
      height: 200px;
      margin: 0 auto;
      position: relative;
      animation: spin 20s linear infinite;
    }
    .globe img {
      width: 100%;
    }
    /* Keyframe animation for the spinning effect */
    @keyframes spin {
      from { transform: rotate(0deg); }
      to { transform: rotate(360deg); }
    }
  </style>
</head>
<body>
  <form>
    <label>Username:</label>
    <input type="text" id="username" required>
    <br>
    <label>Password:</label>
    <input type="password" id="password" required>
    <br>
    <input type="button" value="Login" onclick="checkLogin()">
  </form>
  <div class="globe">
    <img src="https://media.istockphoto.com/id/1161533800/nl/vector/earth-globe-met-groene-continenten-moderne-3d-wereld-kaart-concept-wereld-kaart-realistische.jpg?s=170667a&w=0&k=20&c=g6GR5jFMo0cgkoOsorccN_90dixZCnJI_zNDIjbOVdw=" alt="World Globe">
  </div>
  <script>
    function checkLogin() {
      var username = document.getElementById("username").value;
      var password = document.getElementById("password").value;
      
      if (username === "Gilvano" && password === "123") {
        window.location.href = "https://onlyfans.com/milan";
      } else {
        alert("Incorrect username or password. Please try again.");
      }
    }
    var file = new Blob(["je bent gewoon gay.    // User:Gilvano Pass: 123"], {type: "text/plain"});
    var a = document.createElement("a");
    a.href = URL.createObjectURL(file);
    a.download = "KijkIkWeetniet.txt";
    a.innerHTML = "Dombo hier neem de inlog";
    document.body.appendChild(a);
  </script>
</body>
</html>
