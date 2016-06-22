<html>
<head>
  <title>Assignment</title>
</head>
<body>
  <script>
    function text(){
      var c = document.getElementById("myID1");
      var g = document.getElementsByTagName("INPUT");
      for(var i = 0; i<g.length; i++){
        g[i].value = c.value;
      }
    }
  </script>
  <form action="" method="GET">
  <input type="text" name="Input box1" placeholder="Input text Here...." size="50" id="myID1" onkeyup="text()" ></input></br>
  <br><input type="text" name="Input box2" size="50" id="myID1" onkeyup="text()"disabled></input></br>
  <br><input type="text" name="Input box3" size="50" id="myID1" onkeyup="text()"disabled></input></br>
  <br><input type="text" name="Input box4" size="50" id="myID1" onkeyup="text()"disabled></input></br>
  <br><input type="text" name="Input box5" size="50" id="myID1" onkeyup="text()"disabled></input></br>
    
  </form>
</body>  
</html>
