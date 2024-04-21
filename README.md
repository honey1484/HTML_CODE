# HTML_CODE
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Forward and Backward Buttons</title>
    <style>
        body {
            background-color: lightblue;
            text-align: center; 
        }
        h1 {
            margin-top: 50px; 
        }
        button {
            margin-top: 20px; 
        }
    </style>
</head>
<body>
    <h1>Web Navigation</h1>
    
    <button onclick="goForward()">Forward</button>

    <script>
        

        function goForward() {
            window.location.href = 'file:///C:/Users/Lenovo/OneDrive/Desktop/DSA_Summative/simple_code_1.html'; 
        }
    </script>
</body>
</html>
