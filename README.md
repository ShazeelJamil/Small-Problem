# Navigation Bar 
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Navigation Bar</title>
</head>
<style>
    .navbar {
        background-color: black;
        border-radius: 20px;
    }
    .navbar ul{
        overflow: auto;
    }
    .navbar li{
        list-style: none;
        float: left;
        padding: 10px;
        color: hsl(0, 0%, 100%)


    }
    .navbar li a{
        margin: 20px;
        padding: 10px;
        padding-top: px;
        /* margin-top: 5px; */
        /* margin: 4px; */
    }
    .search{
        float: right;
        /* padding: 10px; */
        margin: 10px;
        border-radius: 7px;
        padding-right: 20px;

    }
    .navbar li a:hover{
        cursor: pointer;
        background-color: cornflowerblue;
    }
</style>

<body>

    <header>
        <nav class="navbar">
            <ul>
                <li> <a href="https://www.google.com.pk/webhp?tab=rw" target="_blank" ></a>Home</li>
                <li> <a href="https://www.facebook.com/?ref=logo"target="_blank"></a>Catagories</li>
                <li> <a href="https://www.youtube.com/" target="_blank" ></a>Services</li>
                <li> <a href="https://www.instagram.com/"target="_blank" ></a>Contact Us</li>
                <input type="text" class="search" placeholder="Search here">
            </ul>
        </nav>

    </header>
</body>

</html>
