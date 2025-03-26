<body>
    <header class="header">
        <div class="headerOverlay"></div>
        <div class="headerItemsContainer">
            <img src="img/Logo.jpg" alt="Profile Image">
            <h1>Hi, I'm Garm</h1>
            <p>
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Impedit, necessitatibus! Pariatur consequuntur totam neque, culpa possimus in eveniet illo id iure ex eius nostrum rerum facere. Eligendi fuga laudantium voluptates?
            </p>
        </div>
    </header>
    <nav class="nav">
        <ul class="navUl">
            <li class="navItem"><a href="#" class="navLink">Home</a></li>
            <li class="navItem"><a href="#" class="navLink">About me</a></li>
            <li class="navItem"><a href="#" class="navLink">Contact</a></li>
        </ul>
    </nav>
</body>
    <style>
            body {
    margin: 0;
    font-family: sans-serif;
    box-sizing: border-box;
    font-size: 10px;
    background-image: url("img/background.webp");
    background-size: cover;
    background-position: center;
    background-attachment: fixed;
    color: #fff;
    z-index: 1;
}

*{
    box-sizing: border-box;
    padding: 0;
}

/*header section*/


.header {
    min-height: 100vh;
    box-sizing: border-box;
    display: flex;
}

.headerOverlay{
    width: 100%;
    min-height: 100vh;
    background-color: #0008;
    position: absolute;
    z-index: 10;
}

.headerItemsContainer{
    position: relative;
    z-index: 20;
    margin: auto;
    text-align: center;
}

h1{
    font-size: 6em;
    margin: 0;
    text-wrap: balance;
}

.headerItemsContainer p{
    font-size: 2em;
    max-width: 900px;
    text-wrap: balance;
}

.headerItemsContainer img{
    box-sizing: border-box;
    min-width: 200px;
    max-width: 35%;
    border-radius: 50%;
    border: 5px solid #eee;
    box-shadow: 0 0 25px #000;
    margin: 20px;
}


/*Nav section bar*/

.nav{
    min-height: 60px;
    background-color: #222;
    display: flex;
}

.navUl{
    margin: auto;
    width: 70%;
    display: flex;
    justify-content: space-evenly;
    flex-wrap: wrap;
}

.navItem{
    width: 150px;
    min-width: 150px;
    min-height: 55px;
    list-style: none;
    text-align: center;
}

.navLink {
    font-size: 2em;
    text-align: center;
    color: #eee;
    text-decoration: none;
    display: inline-block;
    padding: 15px;
    border-bottom: 0 solid transparent;
    transition: 500ms;
}

.navLink:hover{
    border-bottom: 2px solid #eee;
}
    </style>
