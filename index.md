<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Splash Page</title>
    <link rel="icon" type="image/png" href="favicon.png">
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="wrapper">
        <!-- Brand Logo -->
        <img src="./img/bridge-logo.png" alt="bridge logo" class="brand-img">
        <div class="background-toggles" title="Change Background">
            <div class="background-1" onclick="changeBackground('1')"></div>
            <div class="background-2" onclick="changeBackground('2')"></div>
            <div class="background-3" onclick="changeBackground('3')"></div>
        </div>
        <!-- Image Togle -->
        <!-- Title & Text -->
        <div class="text-container">
            <h1 class="title">Find the stuff you’ll love.</h1>
            <p class="text">Excitinng deals with the latest handsets. Get whatever you desire for exciting games, music player, camera, 3D sound and everything you want from a device.</p>
            <div class="app-store-btn">
                <a href="http://apple.com" target="_blank">
                <img src="./img/app-store-button.png" alt="App store"></a>
            </div>
            <div class="google-play-btn">
                <a href="http://play.google.com" target="_blank">
                <img src="./img/google-play-button.png" alt="Google Play"></a>
            </div>
        </div>
        <!-- Main image -->
        <div class="main-image-container">
            <img src="./img/main-image.png" alt="Landing page mock up">
        </div>
         <!-- Images -->
         <img src="./img/profile.png" alt="Profile Mockup" class="profile-img">
         <img src="./img/orders.png" alt="Orders" class="orders-img">
         <img src="./img/home.png" alt="Home Mockup" class="home-img">
         <img src="./img/cart.png" alt="Cart Mockup" class="cart-img">
         <img src="./img/product.png" alt="Product Mockup" class="product-img">
    </div>
    <!-- Script -->
    <script src="script.js"></script>
</body>
</html>
