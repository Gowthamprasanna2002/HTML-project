<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>google form</title>
    <style>
        body{
            text-align: center;
            margin: 20%;
            border: 2px solid black;
            padding: 20px;
        }
    </style>
    
    
</head>
<body style="background-color: white;">
    <form action="https://github.com/Gowthamprasanna2002/project/tree/main" method="post">
        <label for="fname">First name:</label>
        <input type="text" id="fname" name="fname"><br><br>
        <label for="lnamew">Last name:</label>
        <input type="text" id="lname" name="lname"><br><br>
        <label for="college">College name:</label>
        <input type="text" id="college" name="college"><br><br>
        <label for="address">Address:</label>
        <input type="text" id="address" name="address"><br><br>
        <input type="button" value="click me" >
    </form>
    <script>
  fetch('https://github.com/Gowthamprasanna2002/project/tree/main')
    .then(res => res.json())
    .then(data => {
      document.getElementById("content").innerText = data.message;
    });
</script>


       
        
</body>
</html>
