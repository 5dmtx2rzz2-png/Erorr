<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Error</title>
<style>
    body {
        background-color: #1e1e1e;
        display: flex;
        justify-content: center;
        align-items: center;
        height: 100vh;
        font-family: Arial, sans-serif;
        color: white;
    }

    .box {
        background-color: #2c2c2c;
        padding: 30px;
        border-radius: 10px;
        text-align: center;
        box-shadow: 0 0 20px black;
        width: 300px;
    }

    h2 {
        color: red;
    }

    button {
        margin: 10px;
        padding: 10px 20px;
        border: none;
        border-radius: 5px;
        cursor: pointer;
        font-size: 16px;
    }

    .btnO {
        background-color: #ff4444;
        color: white;
    }

    .btnU {
        background-color: #4488ff;
        color: white;
    }

    button:hover {
        opacity: 0.8;
    }
</style>
</head>

<body>

<div class="box">
    <h2>Erorr</h2>
    <p>There is a problem in this file.</p>
    <button class="btnO" onclick="exitFile()">O</button>
    <button class="btnU" onclick="exitFile()">U</button>
</div>

<script>
function exitFile() {
    window.close();
}
</script>

</body>
</html>
