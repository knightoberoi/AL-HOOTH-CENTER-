<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Auto Login</title>
    <script>
        function autoLogin() {
            document.getElementById('password').value = '112233';
            document.getElementById('loginForm').submit();
        }
    </script>
</head>
<body onload="autoLogin()">
    <form id="loginForm" action="https://open.iammeter.com/home/share/ccb4084b4b3f4e2593a23cf02af62e51" method="POST">
        <input type="hidden" id="password" name="password">
    </form>
</body>
</html>-
