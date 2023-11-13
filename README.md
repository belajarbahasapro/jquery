<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Latihan jquery</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet"
        integrity="sha384-T3c6CoIi6uLrA9TneNEoa7RxnatzjcDSCmG1MXxSR1GAsXEV/Dwwykc2MPK8M2HN" crossorigin="anonymous">
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js">
    </script>
    <!-- <script>
        $(document).ready(function () {
            $("#button").click(function () {
                $("p").hide();
            });
            $("p").click(function () {
                $(this).hide();
            });
        });
    </script> -->
    <script>
        $(document).ready(function () {
            $("#hide").click(function () {
                $("p").hide();
            });
            $("#show").click(function () {
                $("p").show();
            });
        });
    </script>
</head>

<body>
    <p>Kalimat Paragraf Pertama.HILANG</p>
    <p>Kalimat Paragraf Kedua.HILANG</p>
    <!-- <button id="button">HIDE</button> -->
    <button id="hide">Hide</button>
    <button id="show">Show</button>
</body>

</html>
