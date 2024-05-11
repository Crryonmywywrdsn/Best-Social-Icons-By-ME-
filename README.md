# Best-Social-Icons-By-ME-
READ THE README
Floating/Hvr Social Icons, w/ custom anim-shdw-hvr-+css built in .HTML BEST for web design.
---------------------------------------------------------------------------------------------
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Font Awesome Icons</title>
    <!-- Link to Font Awesome stylesheet -->
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css">
    <!-- Your CSS styles -->
    <style>
    /* Apply box-sizing to all elements */
    * {
      box-sizing: border-box;
    }

    /* Center text and reset margin/padding for the body */
    body {
      text-align: center;
      margin: 0;
      padding: 0;
    }

    /* Style the wrapper container */
    .wrapper {
      display: flex;
      flex-wrap: wrap; /* Wrap the items if they exceed the container width */
      justify-content: center; /* Center the items horizontally */
      align-items: center; /* Center the items vertically */
      min-height: 100vh; /* Ensure the container covers at least the viewport height */
    }

    /* Style individual icons */
    .wrapper a i {
      padding: 0 10px; /* Add padding around each icon */
      cursor: pointer;
      text-shadow: 0px 7px 10px rgba(0, 0, 0, 0.4); /* Add shadow effect */
      transition: all ease-in-out 150ms; /* Smooth transition on hover */
    }

    /* Define hover effect for icons */
    .wrapper a i:hover {
      text-shadow: 0px 16px 10px rgba(0, 0, 0, 0.3); /* Adjust shadow on hover */
      transform: translateY(-8px); /* Move the icon upward on hover */
    }

    /* Button styles */
    .button-wrapper {
      display: flex;
      flex-direction: column;
      align-items: center;
    }

    .button {
      display: inline-block;
      padding: 10px 20px;
      background-color: #66FF99;
      color: #778899;
      text-decoration: none;
      border-radius: 5px;
      transition: background-color 0.3s, transform 0.5s;
      margin: 10px 0; /* Add space between buttons */
      box-shadow: 0px 10px 20px rgba(0, 0, 0, 0.3); /* Add shadow */
    }

    .button:hover {
      background-color: #663399;
      transform: scale(1.1); /* Add hover effect */
    }

    @keyframes beat {
      0% { transform: scale(1); }
      50% { transform: scale(1.1); }
      100% { transform: scale(1); }
    }

    .button:hover {
      animation: beat 1s infinite; /* Apply beat animation on hover */
    }

    /* Define unique hover animations for each icon */
    .wrapper a:nth-child(1) i:hover {
      transform: translateY(-16px); /* Adjust hover transform */
    }

    .wrapper a:nth-child(2) i:hover {
      transform: scale(1.1) rotate(360deg); /* Add rotation */
    }

    .wrapper a:nth-child(3) i:hover {
      transform: rotate(360deg) skewX(-20deg); /* Add rotation and skew */
    }

    .wrapper a:nth-child(4) i:hover {
      transform: skewY(-20deg) scale(1.1); /* Add skew and scale */
    }

    .wrapper a:nth-child(5) i:hover {
      transform: translateY(-20px) scale(1.1); /* Add vertical translation and scale */
    }

    .wrapper a:nth-child(6) i:hover {
      transform: translateX(20px) scale(1.1); /* Add horizontal translation and scale */
    }

    .wrapper a:nth-child(7) i:hover {
      transform: translateY(-20px) rotateY(180deg) scale(1.1); /* Add vertical translation, flip, and scale */
    }

    .wrapper a:nth-child(8) i:hover {
      transform: scale(0.9) rotate(360deg); /* Add scale and rotation */
    }

    /* Define colors for individual icons */
    .wrapper a:nth-child(1) i {
      color: #DAA520; /* Gold color */
    }

    .wrapper a:nth-child(2) i {
      color: #4682B4; /* Steel blue color */
    }

    .wrapper a:nth-child(3) i {
      color: #444; /* Dark gray color */
    }

    .wrapper a:nth-child(4) i {
      color: #40E0D0; /* Turquoise color */
    }

    .wrapper a:nth-child(5) i {
      color: #9370DB; /* Medium purple color */
    }

    .wrapper a:nth-child(6) i {
      color: #FF69B4; /* Hot pink color */
    }

    .wrapper a:nth-child(7) i {
      color: #CD5C5C; /* Indian red color */
    }

    .wrapper a:nth-child(8) i {
      color: #800080; /* Purple color */
    }
    </style>
</head>
<body>
    <div class="wrapper">
        <a href="https://www.instagram.com"><i class="fa fa-flip-horizontal fa-5x fa-instagram"></i></a>
        <a href="https://www.facebook.com/photo/?fbid=894710719333291&set=a.468578711946496"><i class="fa fa-5x fa-facebook-square"></i></a>
        <a href="https://twitter.com/TheAstralMrchnt"><i class="fa fa-flip-horizontal fa-5x fa-twitter-square"></i></a>
        <a href="https://github.com/Crryonmywywrdsn"><i class="fa fa-5x fa-github-square"></i></a>
        <a href="https://steamcommunity.com/groups/theastralmerchant"><i class="fa fa-5x fa-steam-square"></i></a>
        <a href="https://steamcommunity.com/id/Crryonmywywrdsn/"><i class="fa fa-flip-horizontal fa-5x fa-steam-square"></i></a>
        <a href="https://mail.google/theastralmerchant@gmail.com"><i class="fa fa-5x fa-envelope"></i></a>
        <a href="https://www.twitch.tv/theastralmerchant"><i class="fa fa-5x fa-twitch"></i></a>
    </div>
    <!-- Button Wrapper -->
    <div class="button-wrapper">
        <!-- Button 1 -->
        <a href="https://form.jotform.com/Theastralmerchant/contact-us-page" class="button">Contact Us Form</a>
        <!-- Button 2 -->
        <a href="https://form.jotform.com/Theastralmerchant/Dev-Team" class="button">Join Our Dev Team</a>
    </div>
</body>
</html>
