```<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Horizontal Navbar</title>
    <style>
        body {
            font-size: 28px;
        }

        ul {
            list-style-type: none;
            margin: 0;
            padding: 0;
            overflow: hidden;
            background-color: #333;
            position: -webkit-sticky;
            /* Safari */
            position: sticky;
            top: 0;
        }

        li {
            float: left;
        }

        li a {
            display: block;
            color: white;
            text-align: center;
            padding: 14px 16px;
            text-decoration: none;
        }

        li a:hover {
            background-color: #111;
        }

        .active {
            background-color: #4caf50;
        }
    </style>
</head>

<body>
    <div class="header">
        <h2>Scroll Down</h2>
        <p>Scroll down to see the sticky effect.</p>
    </div>

    <ul>
        <li><a class="active" href="#home">Home</a></li>
        <li><a href="#news">News</a></li>
        <li><a href="#contact">Contact</a></li>
    </ul>

    <p>
        Lorem ipsum dolor sit amet consectetur, adipisicing elit. Temporibus dicta in dolore optio! Maiores error natus necessitatibus dolore sunt alias. At obcaecati natus dolorem ut assumenda sunt corrupti. Inventore, deleniti harum voluptatibus, amet possimus
        repellendus, nemo repellat magni dolores ea dignissimos provident ipsa repudiandae beatae. Aliquam provident eveniet laborum cum.
    </p>

    <p>
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Vel ratione earum, minus labore deserunt beatae ipsam possimus rem voluptates debitis tempora eum obcaecati soluta eos distinctio minima quis harum quo eius quam? Possimus magni eum laudantium totam
        earum, ea, sint eligendi illo doloremque ratione, neque asperiores pariatur aliquid cupiditate. Perferendis perspiciatis sunt, omnis, ullam quod corrupti tempora autem nesciunt eum libero iusto, debitis saepe vel in. Sint atque dicta consectetur?
        Voluptate, quasi! Atque id iusto maiores ad quasi soluta consequatur?
    </p>

    <p>
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Vel ratione earum, minus labore deserunt beatae ipsam possimus rem voluptates debitis tempora eum obcaecati soluta eos distinctio minima quis harum quo eius quam? Possimus magni eum laudantium totam
        earum, ea, sint eligendi illo doloremque ratione, neque asperiores pariatur aliquid cupiditate. Perferendis perspiciatis sunt, omnis, ullam quod corrupti tempora autem nesciunt eum libero iusto, debitis saepe vel in. Sint atque dicta consectetur?
        Voluptate, quasi! Atque id iusto maiores ad quasi soluta consequatur?
    </p>
</body>

</html>
```

Tampilan yang dihasilkan :

![button](https://github.com/itsolution405/CSS/blob/main/Horizontal%20Navbar.png)
