<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Instagram Clone</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #fafafa;
        }
        .header {
            background-color: #fff;
            border-bottom: 1px solid #dbdbdb;
            padding: 10px 20px;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        .header img {
            height: 40px;
        }
        .main {
            display: flex;
            justify-content: center;
            padding: 20px;
        }
        .post {
            background-color: #fff;
            border: 1px solid #dbdbdb;
            margin-bottom: 20px;
            width: 500px;
        }
        .post img {
            width: 100%;
        }
        .post .info {
            padding: 10px;
        }
        .post .info h2 {
            margin: 0;
            font-size: 16px;
        }
        .post .info p {
            margin: 5px 0 0;
            font-size: 14px;
        }
    </style>
</head>
<body>
    <div class="header">
        <img src="https://upload.wikimedia.org/wikipedia/commons/a/a5/Instagram_icon.png" alt="Instagram Logo">
        <input type="text" placeholder="Search">
        <div>
            <img src="https://img.icons8.com/material-outlined/24/000000/like--v1.png" alt="Likes">
            <img src="https://img.icons8.com/material-outlined/24/000000/user.png" alt="Profile">
        </div>
    </div>
    <div class="main">
        <div class="post">
            <img src="https://via.placeholder.com/500" alt="Post Image">
            <div class="info">
                <h2>Username</h2>
                <p>Caption for the post goes here...</p>
            </div>
        </div>
        <div class="post">
            <img src="https://via.placeholder.com/500" alt="Post Image">
            <div class="info">
                <h2>Username</h2>
                <p>Caption for the post goes here...</p>
            </div>
        </div>
    </div>
</body>
</html>
