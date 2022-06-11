<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Nimna Wijedasa</title>
    <link rel="stylesheet" href="style.css" />
    <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2
?family=Poppins:wght@100;300;400;600;700&display=swap" 
rel="stylesheet">
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@fortawesome/fontawesome-free@6.1.1/
css/fontawesome.min.css">
</head>
<body>
    <section class="header">
        <nav>
            
            <div class="nav-links" id="navLinks">
                <i class="fa fa-times" onclick="hidemenu()"></i>
                <ul>
                    <li> <a href="">HOME</a></li>   
                    <li> <a href="">ABOUT</a></li>
                    <li> <a href="">GITHUB</a></li>
                    <li> <a href="">BLOG</a></li>
                    <li> <a href="">CONTACT</a></li>
                </ul>
            </div>
            <i class="fa fa-bars" onclick="showmenu()"></i>
        </nav>


        <div class="text-box">
            <h1>Hello I'm Nimna </h1>
            <img src="images/portrait2.png">
            <p> I'm a software engineering student <br>
                currently studying at the University Of Calgary.<br>
                If im not working out or playing sports, <br>
                you can find me playing my guitar during my <br>free time.
            </p>
            <!-- <a href="" class = "hero-btn">click to learn more about me</a> -->
            
        </div>

    </section>
<!-----------------------  course ------------------------------>

<section class ="course">
    <h1>Education</h1>
    <p>Student at the university of calgary </p>
    <img src="images/ucalgary.jpg">

</section>

<!--------------  javascript for toggle menu ------------------->
<script>
    var navLinks =document.getElementById("navLinks");

    function showmenu(){
        navLinks.style.right="0"
    }
    function hidemenu(){
        navLinks.style.right="-200"
    }
</script>

</body>
</html>
