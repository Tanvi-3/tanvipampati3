---
toc: true
comments: false
layout: post
title: Login Page
type: plans
courses: loginpage
---

<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>User Information Form</title>
</head>
<body>
<h1>User Information Form</h1>
<form action="submit_form.php" method="post">
        <!-- Username -->
        <label for="username">Username:</label>
        <input type="text" id="username" name="username" required>
        <br>
<!-- Password -->
<label for="password">Password:</label>
        <input type="password" id="password" name="password" required>
        <br>
<!-- Age -->
<label for="age">Age:</label>
        <input type="number" id="age" name="age" required>
        <br>
<!-- Submit Button -->
<input type="submit" value="Submit">
    </form>
</body>
</html>