body
{
    background-color: gainsboro;
}

html
{
    overflow: hidden;
}

a{
    color: inherit;
    text-decoration: none;
}

a:hover
{
    color:deepskyblue;
    text-decoration: none;
    cursor: pointer;
}

.UtilityNavigation
{
    display: flex;
    width: 100%;
    text-align: center;
    color: gainsboro;
    background-color: black;
    opacity: 0.5;
    font-size: larger;
    font: bold;
    font-family: Impact, Haettenschweiler, 'Arial Narrow Bold', sans-serif;
    padding: 25px;
    justify-content: space-evenly;
    overflow: hidden;
    top: 0%;
    left: 0%;
    position: absolute;
}

.Headshot
{
    border-radius: 50%;
    height: 400px;
    width: 400px;
    margin-top: 10vh;
    margin-left: auto;
    margin-right: auto;
}



---

<!DOCTYPE html>
<html>

    <head>


        <!-- #region CSS-->
            <link rel="stylesheet" href="CSS/Styles.css">
        <!--#endregion CSS-->

        <title>
            Alexander Bowerman
        </title>
        
    </head>

    <body>

        <div>

            <div class = "UtilityNavigation">

                <a href ="index.html">

                    Alexander Bowerman

                </a>
                <a href="about.html">

                    About

                </a>
                <a href="contact.html">

                    Contact

                </a>

            </div>

        </div>

        <div class="Headshot">

            <img src="Assets/Headshot_2018.jpg" alt="AlexanderBowerman">

        </div>


    </body>

</html>