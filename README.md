<!DOCTYPE html>
<html>
    <head>
        <meta charset="UTF-8">
        <title>出る出る出る.mp3</title>
    </head>
    <body>
        <p><h1>押してみてください</h1></p>
        <script>
            var audio = new Audio("deruderuderu.mp3");
            audio.oncanplaythrough = function ( ) { }
            audio.onended = function ( ) { }
            </script> <input type="image" src="Screenshot_3.jpg" onclick="audio.play ( )">
    </body>
</html>
