# IITISoC-22-Web9-MeetingScheduler
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Event</title>
    <link rel="stylesheet" href="app.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <script src="https://kit.fontawesome.com/16b8733e74.js" crossorigin="anonymous"></script>
<body>
    <nav>
        <div class="navbar">
            <div class="nav-logo"><i class="fa-brands fa-google fa-3x"></i></div>
        <div class="name"><h1>710 Calendar</h1></div>
        <div class="side_nav"><ul>
            <li>
                <div  class="search">
                <input type="text" placeholder="Search">
                <button type="submit>"><i class="fa-solid fa-magnifying-glass"></i></button>
            </div>
            </li>
           
            <li>
                <ul class="dropdown">
                    <li>week</li>
                    <li>Day</li>
                    <li>Month</li>
                </ul>
            </li>
            <li  class="notification">
                <i class="fa-solid fa-bell"></i>
            </li>
            <li>
                <div class="profile-logo"><i class="fa-solid fa-user"></i>
                <p>Account</p>
            </div>
            </li>
        </ul>
    </div>
    </div>
    </nav>
    <hr>
    <h2>Create New Event</h2>
    <
    <hr>
    <div class="one-on-one">
        <div class="logo_description">
            <div class="img"><i class="fa-solid fa-person fa-5x"></i></div>
        <div class="description"><h3>One-on-One</h3>
        
    <p>Let an invitee pick a time to meet with you</p></div>
        </div>
        <div class="button">
        <button id="button-1">Create</button>
        </div>
    </div>
    <div class="Group">
        <div class="logo_description">
            <div class="img"><i class="fa-solid fa-people-roof fa-5x"></i></div>
        <div class="description"><h3>Group</h3>
        
    <p>Let multiple invitees meet with you at one time</p></div>
        </div>
        <div class="button">
        <button id="button-1">Create</button>
        </div>
    </div>
</body>
</html>

CSS
h2{
    text-align: center;
    align-items: center;
    font-family: 'Roboto Slab', serif;
}

.one-on-one{
    width: 1000px;
    height: 180px;
    display: flex;
    margin: 20px auto;
    /*padding: 0 90px 0 90px;*/
    border: 5px black solid;
    border-radius: 40px;

}

.img{
    width: 150px;
    height:150px;
    background-color: #e9c46a;
    border-radius: 30%;
    display: flex;
    justify-content: center;
    align-items: center;
}

.logo_description{
    width: 70%;
    padding: 20px 20px;
    display: flex;
    
}

.description{
    padding-left: 20px;
    width: 400px;
}

img{
    height: 80px;
}

#button-1{
    height: 40px
}

.button{
    display: flex;
    justify-content: center;
    align-items: center;

}

.button button{
    width: 100px;
    border-radius: 40px;
    background-color:#48cae4;
    /* transition: background-color 2s 1ms; */
}

.button button:hover{
    width: 120px;
    background-color: aliceblue;
    font-weight: bold;
}

.fa-solid{
    color: black;
    
}

.Group{
    width: 1000px;
    height: 180px;
    display: flex;
    margin: 20px auto;
    /*padding: 0 90px 0 90px;*/
    border: 5px black solid;
    border-radius: 40px;;
}
/*navbar*/
.navbar{
    display: flex;
    width: 100%;
}

.nav-logo{
    width: 8%;
    display: flex;
    justify-content: center;
    align-items: center;
}

.name{
    width: 20%;
    display: flex;
    justify-content: center;
    align-items: center;
    font-size: 22px;
}

.side_nav{
    width: 72%;
    display: flex;
    justify-content: flex-end;
    align-items: center;
}

nav ul li{
    margin: 0 5px;
    display: inline-block;
    text-align: right;
}

.profile{
    display: flex;
}

.profile-logo{
    display: flex;
    align-items: center;
}

.search{
    /* width: 20%; */
    display: flex;
    justify-content: center;
    align-items: center;
    width: 100%;
    /* background-color: rgb(142, 151, 159); */
    border: 2px black solid;
    border-radius: 60px;
    padding: 0 5px;
}

.search input{
    background: transparent;
    flex: 1;
    border: 0;
    outline: none;
    padding: 10px 0;
}

.search button i{
    width: 20px;
}

.search button{
    border-radius: 45px;
    border: 0;
}

/* navbar ends */

