<!DOCTYPE html>
<html>
<head>
    <title>Color Customizer</title>

    <style>
        body {
            font-family: Arial;
            background-color: #eeeeee;
            text-align: center;
        }

        .container {
            background-color: white;
            width: 80%;
            margin: 40px auto;
            padding: 25px;
            border-radius: 15px;
        }

        .box {
            background-color: black;
            color: white;
            padding: 30px;
            margin: 20px;
            border-radius: 10px;
        }

        button {
            background-color: #333333;
            color: white;
            padding: 10px 18px;
            margin: 5px;
            border: none;
            border-radius: 6px;
            cursor: pointer;
        }

        button:hover {
            background-color: green;
        }
    </style>
</head>

<body>

    <div class="container">

        <h1>Color and Font Customizer</h1>

        <div class="box" id="box">
            <h2>Welcome to My Project</h2>
            <p>Change background, text color and font family</p>
        </div>

        <h3>Background Color</h3>

        <button data-type="bg" data-color="black">Black</button>
        <button data-type="bg" data-color="blue">Blue</button>
        <button data-type="bg" data-color="white">White</button>
        <button data-type="bg" data-color="green">Green</button>

        <h3>Text Color</h3>

        <button data-type="text" data-color="black">Black</button>
        <button data-type="text" data-color="blue">Blue</button>
        <button data-type="text" data-color="white">White</button>
        <button data-type="text" data-color="green">Green</button>

        <h3>Font Family</h3>

        <button data-type="font" data-font="Arial">Arial</button>
        <button data-type="font" data-font="Georgia">Georgia</button>
        <button data-type="font" data-font="Courier New">Courier</button>
        <button data-type="font" data-font="Verdana">Verdana</button>

    </div>

    <script>

        let box = document.getElementById("box");

        let buttons = document.querySelectorAll("button");

        buttons.forEach(function(button) {

            button.addEventListener("click", function() {

                let type = button.getAttribute("data-type");

                if (type === "bg") {
                    let color = button.getAttribute("data-color");
                    box.style.backgroundColor = color;
                }

                else if (type === "text") {
                    let color = button.getAttribute("data-color");
                    box.style.color = color;
                }

                else if (type === "font") {
                    let font = button.getAttribute("data-font");
                    box.style.fontFamily = font;
                }

            });

        });

    </script>

</body>
</html>
