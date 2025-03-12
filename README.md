# Postal
Proyecto de postal de mi Prework en 4Geeks
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Postcard</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            height: 100vh;
            background-color: #f0f0f0;
            margin: 0;
        }
        .container {
            width: 600px;
            background: white;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
            border-radius: 10px;
            padding: 20px;
        }
        .header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin-bottom: 20px;
        }
        .header h1 {
            margin: 0;
            font-size: 24px;
        }
        .header img {
            width:50px;
            height:auto;
            border-radius: 5px;
        }
        .content {
            display:flex;
            justify-content:space-between;
            align-items: center;
        }
        .text {
            width: 50%;
            text-align: justify;
            font-size: 16px;
        }
        .form {
            width: 45%;
            display: flex;
            flex-direction: column;
        }
        .form input {
            margin-top: 10px;
            padding: 8px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        .button-container {
            display: flex;
            justify-content: center;
            margin-top: 20px;
        }
        .button-container button {
            padding: 10px 20px;
            border: none;
            background: #717071;
            color: white;
            font-size: 16px;
            cursor: pointer;
            border-radius: 5px;
        }
        .button-container button:hover {
            background: #616161;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="header">
            <h1>My Postcard</h1>
            <img src="http://assets.breatheco.de/apis/img/icon/4geeks.png" alt="Logo">
        </div>
        <div class="content">
            <div class="text">
                <p>
                    Look how awesome! This is a postcard that I created using HTML5 and CSS3 during my 4Geeks Academy course! 
                    This is so cool, can’t wait to start doing more stuff!
                </p>
            </div>
            <div class="form">
                <input type="text" placeholder="Some Name">
                <input type ="email" placeholder="Some Email">
                <input type ="text" placeholder="Some Comment">
            </div>
        </div>
        <div class="button-container">
            <button>Send my Postcard</button>
        </div>
    </div>
</body>
</html>
