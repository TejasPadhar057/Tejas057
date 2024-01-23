HTML Code
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Job Dashboard</title>
    <link rel="stylesheet" href="css/style.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css" >

</head>
<body>
    <div class="container">
        <nav>
            <div class="navbar">
                <div class="logo">
                    <img src="img/job2.jpg"alt="">
                    <h1>Job's.com</h1>
                </div>
                <ul>
                    <li>
                        <a href="#">
                            <left><i class="fas fa-user"></i></left>
                            <span class="nav-item">Dashboard</span>
                        </a>
                    </li> <li>
                       <left> <i class="fas fa-chart-bar"></i> </left>
                        <a href="#">
                            <span class="nav-item">Analytics</span>
                        </a>
                    </li> <li>
                        <left><i class="fas fa-tasks"></i> </left>
                        <a href="#">
                            <span class="nav-item">Jobs Board</span>
                        </a>
                    </li> 
                    <li>
                        <a href="#">
                            <left><i class="fab fa-dochub"></i></left>
                            <span class="nav-item">Documnents</span>
                        </a>
                    </li> <li>
                        <a href="#">
                            <left><i class="fas fa-cog"></i></left>
                            <span class="nav-item">Setting</span>
                        </a>
                    </li> <li>
                        <a href="#">
                            <left><i class="fas fa-question-circle"></i></left>
                            <span class="nav-item">Help</span>
                        </a>
                    </li> <li>
                        <a href="#" class="logout">
                            <left><i class="fas fa-sign-out-alt"></i></left>
                            <span class="nav-item">Logout</span>
                        </a>
                    </li>
                </ul>
            </div>
        </nav>

        <section class="main">
            <div class="main-top">
            <p> <strong>Get the best job</strong></p>
            </div>
            <div class="main-body">
                <h1>Recent Jobs</h1>

            </div>
            <div class="search_bar">
                <input type="search" placeholder="Search job here...">
                 <select class="category">
                    <option>Category</option>
                    <option>Software Developer/Engineer</option>
                    <option>Network Engineer</option>
                    <option>IT Project Manager</option>
                    <option>UI/UX Designer</option>
                </select>
                <select class="filter">
                    <option>filter</option>
                </select>
            </div>
        
        
            <div class="tags_bar">
                <div class="tag">
                    <div class="fas fa-times"></div>
                    <span>Programming</span>
                </div><div class="tag">
                    <div class="fas fa-times"></div>
                    <span>Design</span>
                </div><div class="tag">
                    <div class="fas fa-times"></div>
                    <span>PHP</span>
                </div><div class="tag">
                    <div class="fas fa-times"></div>
                    <span>JavaScript</span>
                </div>
             </div>
             <div class="row">
                <p>There are more than <span>400</span> Jobs</p>
                <a href="#">See all</a>
             </div>

             <div class="job_card">
                <div class="job_details">
                    <div class="img">
                        <i class="fab fa-google-drive"></i>

                    </div>
                    <div class="text">
                        <h2>UX Designer</h2>
                        <span>Google Drive - junior Post</span>
                    </div>
                </div>
                <div class="job_salary">
                    <h4>$6.7 - 12.2k /yr</h4>
                    <span>1 days ago</span>
                </div>
             </div>


             <div class="job_card">
                <div class="job_details">
                    <div class="img">
                        <i class="fab fa-google"></i>

                    </div>
                    <div class="text">
                        <h2>Product Developer</h2>
                        <span>Google - Senior Post</span>
                    </div>
                </div>
                <div class="job_salary">
                    <h4>$8.7 - 13.2k /yr</h4>
                    <span>5 days ago</span>
                </div>
             </div>

             <div class="job_card">
                <div class="job_details">
                    <div class="img">
                        <i class="fab fa-youtube"></i>

                    </div>
                    <div class="text">
                        <h2>Web Designer</h2>
                        <span>Google - junior Post</span>
                    </div>
                </div>
                <div class="job_salary">
                    <h4>$10.7 - 14.2k /yr</h4>
                    <span>1 week ago</span>
                </div>
             </div>

             <div class="job_card">
                <div class="job_details">
                    <div class="img">
                        <i class="fab fa-facebook"></i>

                    </div>
                    <div class="text">
                        <h2>Network Engineer</h2>
                        <span>Microsoft - HR Post</span>
                    </div>
                </div>
                <div class="job_salary">
                    <h4>$20.7 - 22.2k /yr</h4>
                    <span>5 week ago</span>
                </div>
             </div>

             <div class="job_card">
                <div class="job_details">
                    <div class="img">
                        <i class="fab fa-telegram"></i>

                    </div>
                    <div class="text">
                        <h2>IT project manager</h2>
                        <span>wipro- junior Post</span>
                    </div>
                </div>
                <div class="job_salary">
                    <h4>$6 - 8k /yr</h4>
                    <span>1 days ago</span>
                </div>
             </div>

        </section>

    </div>
    
</body>
</html>


CSS Code
@import url("https://fonts.googleapis.com/css2?family=poppins:wght@400;500;600;700&dispiay=swap");
*{
    margin: 0;
    padding: 0;
    outline: none;
    border: none;
    text-decoration: none;
    box-sizing: border-box;
    font-family: "poppins",sans-serif;
}
body{
    background: rgb(233, 233, 233);
}
.container{
    display: flex;
    width: 3000px;
    margin: auto;
}
nav{
    position: sticky;
    top: 0;
    bottom: 0;
    width: 300px;
    height: 100vh;
    background: white;
}
.logo{
    margin: 2rem;
    padding-bottom: 3rem;
}
.logo img{
    width: 100px;
    height: 100px;
    border-radius: 75%; 
    margin: 25px;
    margin-bottom: 0rem;
}
.logo h1{
    text-transform: uppercase;
}
ul{
    margin: 0 auto;
    text-align: center;
}
li{
    padding-bottom: 2rem;
}
li a{
    font-size: 22px;
    color: grey;
}
.nav-item{
    

}
nav i{
    width: 50px;
    font-size: 18px;
    text-align: center;
}
.logout{
    position: center;
    bottom: 100px;
}
/* main section*/
.main{
    width: 100%;
}
.main p{
    width: 56%;
    background: white;
    padding: 10px;
    text-align: center;
    font-size: 20px;
    letter-spacing: 2px;
    text-transform: uppercase;
    color: rgb(45,45, 45);
    font-style: bold;

}
.main-body{
    padding: 10px 10px 10px 20px;
}
.h1{
    margin: 20px 10px;
}
.search_bar{
    display: flex;
    padding: 10px;
    justify-content: space-between;
}
.search_bar input{
    width: 15%;
    padding: 10px;
    border: 1px solid black;
    
}
.search_bar input:focus {
    border: 1px solid blue;
    
}

.search_bar select{
    border: 1px solid black;
    padding: 10px;
    margin-left: -4000px;
}
.search_bar .filter{
    width: 10%;
    margin-left: -1250px;
    padding-left: 50px;
}
.search_bar .category{

    width: 10%;
    margin-left: -2800px;
    padding-left: 50px;
}
.tags_bar{
    width: 55%;
    display: flex;
    padding: 10px;
    justify-content: space-between;
}
.tag{
    
    background: white;
    padding: 10px 15px;
    border-radius: 20px;
    display: flex;
    align-items: center;
    font-size: 20px;
    cursor: pointer;
    
}
.tag i{
    margin-right: 0.7rem;
}
.row{
    display: flex;
    padding: 10px;
    margin-top: 1.3rem;
    justify-content: space-between;
}
.row p{
    color: red;
    font-size: 20px ;
}
.row p span{
    color: black;
}
.job_card{
    width: 50%;
    padding: 15px;
    cursor: pointer;
    display: flex;
    border-radius: 20px;
    background: white;
    margin-bottom: 15px;
    justify-content: space-between;
    border: 2px solid black;
    box-shadow: 0 20px 30px grey;
}
.job_details{
    display: flex;
}
.job_details .img{
    display: flex;
    justify-content: center;
    align-items: center;
}
.job_details .img i{
    width: 70px;
    font-size: 3rem;
    margin-left: 1rem;
    padding: 10px;
    color: rgb(228, 11, 174);
    background: rgb(216,205 ,226);
}
.job_details .text{
    margin-left: 2.3rem;
}
.job_details .text span{
    color: rgb(116, 112, 112);
}
.job_salary{
    text-align: right;
    color: grey;
}
.job_card:active{
    border: 5px solid rgb(5, 248, 5);
    transition: 0.4s;
}
