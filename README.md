<!DOCTYPE html>
<html>
<head>
    <title>Demande à Fleur</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: pink;
            text-align: center;
            padding: 50px;
        }
        .valentine-box {
            background-color: white;
            border-radius: 15px;
            padding: 20px;
            margin: auto;
            width: 50%;
        }
        .button {
            display: inline-block;
            padding: 10px 20px;
            font-size: 16px;
            cursor: pointer;
            text-align: center;
            text-decoration: none;
            outline: none;
            color: white;
            background-color: red;
            border: none;
            border-radius: 15px;
            box-shadow: 0 9px #999;
        }
        .button:hover {background-color: #e60000}
        .button:active {
            background-color: #e60000;
            box-shadow: 0 5px #666;
            transform: translateY(4px);
        }
        #video {
            display: none;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <div class="valentine-box">
        <h1>Salut Fleur!</h1>
        <p>Veux-tu être ma Valentine?</p>
        <button class="button" onclick="showVideo()">Oui</button>
        <button class="button" onclick="alert('Peut-être une autre fois alors...')">Non</button>
    </div>
    <div id="video">
        <iframe width="560" height="315" src="https://www.youtube.com/embed/x0eGFZ6mcmg" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>
    </div>

    <script>
        function showVideo() {
            document.getElementById("video").style.display = "block";
        }
    </script>
</body>
</html>
