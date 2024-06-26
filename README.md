# project1
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Navigation Menu</title>
    <style>
         body{
            margin: 0;
            padding: 0;
            background-color: rgb(112, 110, 107); 
            background-image: url("download.jpeg");
            background-repeat: no-repeat;
            background-size: cover;
        }
 
        .navbar{
        margin-top: 100px;
         width: 100%;
         border-radius: 50px;
         padding: 10px 2px;
         height: 30px;
        }

        .navbar ul{
            margin: 0px;
            padding: 0px;
            display: flex;
            justify-content: center;
        }

        .navbar ul li{
          list-style: none;
          margin: 0 20px;
        }
        .navbar ul li a{
            color: black;
            /* color: white; */
            pad: 5px 10px;
            text-decoration: none;
            font-size: 30px;
            font-weight: 600;
        }
            
      ul li:hover{
       cursor: pointer;
       border-radius: 10px;   
      background-color:rgb(192, 186, 186);
    }

    .info{
        margin: 200px;
        justify-content: center;
        text-align: center;
        border-radius: 30px;
        color: black;
        /* color: rgb(255, 253, 253); */
        font-weight: bold;
    }

    .text p{
     font-size: 30px;
     text-align: justify;
     letter-spacing: 1px;
     font-weight: 800;
    }

    </style>
</head>
<body>
  <nav class="navbar">
    <ul>
        <li><a href="home">Home</a></li>
        <li><a href="about">About</a></li>  
         <li><a href="contact">Contact</a></li>
    </ul>
  </nav>
  <section class="info">
  <div class="text">
    <P>Lorem ipsum dolor sit amnostrum quisquam. Pariatur minus voluptatibus deserunt molestiae, tempore ipsum? Natus optio, itaque iste odio veritatis ratione minima exercitationem molestiae at adipisci sint sit ad et cupiditate deleniti voluptatibus doloremque nemo quod Lorem ipsum dolor sit amet consectetur adipisicing elit. Veritatis nulla cumque, rem, ipsa iste corrupti ipsum similique sint ad autem eum modi, tempora explicabo magni. Cum nihil esse delectus minus.
    </P>
</div>
  </section>

  <script>

    document.addEventListener("DOMContentLoaded", function() {
    const navbar = document.getElementById('.navbar');

    window.onscroll = function() {
        if (window.scrollY > 50) {
            navbar.style.backgroundColor = "#111";
        } else {
            navbar.style.backgroundColor = "#333";
        }
    };
});


    </script>
</body>
</html>

  
  
