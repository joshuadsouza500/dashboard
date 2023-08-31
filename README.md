# dashboard
DOCTYPE html>
<html lang="en">
<head>
    <link rel="stylesheet" href="styles.css">
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Admin Dashboard</title>
</head>
<body>
    <div class="dashboard">
        <h2>DASHBOARD</h2>
        <list>
            <ul>
                <li><a class="icons" href="">🏠 Home</a></li>
                <li><a class="icons" href="">👤 Profile</a></li>
                <li><a class="icons" href="">💬 Messages</a></li>
                <li><a class="icons" href="">📁 Projects</a></li>
                <li><a class="icons" href="">✔️ Tasks</a></li>
            </ul>
            <ul>
                <li><a class="icons" href="">⚙️ Settings</a></li>
                <li><a class="icons" href="">📞 Contact</a></li>
                <li><a class="icons" href="">🔒 Privacy</a></li>
            </ul>
        </list>
         
       </div>
    <div class="navbar">
    <div class="search">
        <button type="submit">🔍</button>
        <input type="search" name="search" id="sbar" style="background-color:#e2e8f0;" >
    </div>
    <div class="logo">
        <img class="image" src="logo.png" width="50px" height="50px">
       <h3>Joshua D'souza</h3>
    </div>
    <nav>
        <button class="btn">New</button>
        <button class="btn">Upload</button>
        <button class="btn">Share</button>
    </nav>
     </div>
    <div class="container">
    <div class="content">
        <h3>Your Projects </h3>
   <div class="cards">
       <div class="card"><h4>Project-1</h4><p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p></div>
       <div class="card"><h4>Project-2</h4><p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p></div>
       <div class="card"><h4>Project-3</h4><p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p></div>
       <div class="card"><h4>Project-4</h4><p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p></div>
       <div class="card"><h4>Project-5</h4><p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p></div>
       <div class="card"><h4>Project-6</h4><p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p></div>
   </div>
   </div>
   <div class="block1">
<h3>Announcement</h3>
<div class="box">
 <h4>Site maintenance</h4>
 <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis</p>
 <hr>
 <h4>Updated privacy policy</h4>
 <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis</p>
 <hr>
 <h4>New Update</h4>
 <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis</p>
</div>
   </div>
   <div class="block2">
    <h3>To-do list</h3>
    <div class="box2">
      <label><input type="checkbox" id="check">   Complete Project</label>  
        <label><input type="checkbox" id="check">   Update system</label>
        <label> <input type="checkbox" id="check">   Meeting</label>
        <label><input type="checkbox" id="check">  7:30 Reservation</label> 
    </div>
   </div>
    </div>
</body>
</html>



*{
    padding: 0%;
    margin: 0%;
}
body{
    background-color: #e5e7eb;
    display: grid;
    height: 100vh;
    width: 100vw;
    grid-template-columns: 200px 1fr;
    grid-template-rows: 100px 1fr ;
}

.dashboard{
    background-color: #1992d4;
    grid-row: 1/5; 
    font-weight: bold;
    padding: 1.3rem;
}
h2{
    color: white;
}
ul{
    font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
    padding: 10%;
    list-style: none;
    line-height: 2.2rem;
}
a{
    text-decoration: none;
    color: white;
}


.navbar{
    background-color: white;
    display: grid;
    grid-template-columns: 2fr 1fr;
    grid-template-rows: 2fr;
}
.search{
padding-top: 1.5rem;
padding-left: 1.5rem;
}
#sbar{
    border: none;
    border-radius: 1rem;
    width: 35rem;
    height: 1.7rem;
}
.logo{
    display: flex;
    justify-content: center;
    padding-right: 1.5rem;
    gap: 1.1rem;
}
.image{
    border-radius: 50%;
    padding: 3px;
}
nav{
    grid-column: 2/2;
display: flex;
flex-direction: row;
justify-content: center;
padding-right: 1rem;
gap: 1.5rem;
padding-bottom: 1rem;
}
.btn{
    border-color:#1992d4;
    font-weight: bold;
    font-size: 0.7rem;
    color: white;
    background-color: #1992d4;
    padding: 0.2rem 0.7rem;
    border-radius: 1.8rem;
    min-width: 4.5rem;
    height: 1.8rem;
}
.container{
    background-color: #e5e7eb;
   display: grid;
   grid-template-columns: 2.3fr 1fr;
   
}
.content{
    background-color:#e5e7eb;
    grid-row: 1/3;
   display: flex;
   flex-direction: column;
   flex-wrap: wrap;
   flex: 1;
}
.cards{
    display:grid;
    grid-template-columns: repeat(3,2fr);
   padding: 1rem;
}
.card{
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    border-left-color: #f0b429;
    border-style: solid;
    border-width: 0 0 0 .4rem;
    border-radius: 5%;
    height: 20vh;
   background-color: white;
   padding:1rem;
   margin: 5px;
   
   font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
}
.card:hover{
    box-shadow: 4px 4px 8px 1px  rgba(0,0,0,0.3);
}
.block1{
    grid-column: 2/5;
    font-size: small;
    font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
}
h3{
    padding-top: 1%;
    font-weight: bold;
    font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
padding-left:1rem
}
.box{
    background-color: white;
    border-radius: 5%;
    padding: 20px 10px 25px 20px;
    margin-left: 5px; 
    margin-top: 20px;
    margin-right: 10px;   

}
p{
    color: #646464;
    font-size: small;
}
hr {
    display: block;
    margin-top: 0.5em;
    margin-bottom: 0.5em;
    margin-left: auto;
    margin-right: auto;
    border-style: inset;
    border-width: 1px;
  }
.block2{
    grid-column: 2/5;
}
.box2{
    display: flex;
    flex-direction: column;
    gap: .5rem;
    font-weight: 500;
    font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
    background-color: white;
    border-radius: 5%;
    padding: 1.5rem;
    margin: 1rem; 

}
#check{
   width: 2rem;
}




