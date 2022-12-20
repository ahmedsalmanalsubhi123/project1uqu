<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="=IE=edge">
    <meta name = "viewport" content="width=device-width , initial-scale=1.0">
    <title>Hello Name</title>
</head>
<body>
    <h1>Hello. enter your name please </h1>
    <input id="userInput"> <br>  <br>
    <button onclick="myFunction()" > OK</button>
    <h1 id = "message"> </h1> 

    <style>
        body {background-color: cornflowerblue; text-align: center; color: white;} 

    </style> 

    <script>
        function myFunction() {
            let userInput = document.querySelector("#userInput");
            let message = document.querySelector("#message"); 

            message.innerHTML = " welcome, "  + userInput.value; 

            
        } 

    </script> 

</body>
</html>
