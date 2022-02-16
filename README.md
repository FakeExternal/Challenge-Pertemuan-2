<!doctype html>
<html>
<head>
    <title>Learn For Loops</title>
</head>
<body>
    <b>Repeat my name generator</b>
    <br>
   
    <label for="input_stop">Enter Any Number </label>
    <input id="input_stop" type="number">
    <button onclick="sequence()">Submit</button>

</body>

<script>
    function sequence() {
        var stop=Number (document.getElementById
        ("input_stop").value);

        for ( var i =1; i<stop; i++) {
                document.write("Andhika");
                document.write("<br>");
        }
    }    
</script>
</html>
