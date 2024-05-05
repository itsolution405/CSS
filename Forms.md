```
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Forms</title>
    <style>
        input[type="text"],
        select {
            width: 100%;
            padding: 12px 20px;
            margin: 8px 0;
            display: inline-block;
            border: 1px solid #ccc;
            border-radius: 4px;
            box-sizing: border-box;
        }

        input[type="submit"] {
            width: 100%;
            background-color: #a42bb9;
            color: white;
            padding: 14px 20px;
            margin: 8px 0;
            border: none;
            border-radius: 4px;
            cursor: pointer;
        }

        input[type="submit"]:hover {
            background-color: #2bdede;
        }

        div {
            border-radius: 5px;
            background-color: #f2f2f2;
            padding: 20px;
        }
    </style>
</head>

<body>
    <h3>Menggunakan CSS untuk menata Formulir HTML</h3>

    <div>
        <form action="/action_page.php">
            <label for="fname">Nama Depan</label>
            <input type="text" id="fname" name="firstname" placeholder="Your name.." />

            <label for="lname">Nama Belakang</label>
            <input type="text" id="lname" name="lastname" placeholder="Your last name.." />

            <label for="country">Negara</label>
            <select id="country" name="country">
          <option value="australia">Australia</option>
          <option value="canada">Canada</option>
          <option value="usa">USA</option>
        </select>

            <input type="submit" value="Submit" />
        </form>
    </div>
</body>

</html>
```

Tampilan yang dihasilkan :

![button](https://github.com/itsolution405/CSS/blob/main/Forms.png)
