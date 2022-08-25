# git_test
My first github project 

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>NEXT WEBSITE</title>
    <link rel="stylesheet" href="styles.css" />
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.1.1/css/all.min.css"
        integrity="sha512-KfkfwYDsLkIlwQp6LFnl8zNdLGxu9YAA1QvwINks4PhcElQSvqcyVLLD9aMhXd13uQjoXtEKNosOWaZqXgel0g=="
        crossorigin="anonymous" referrerpolicy="no-referrer" />
</head>

<body>
    <!-- Navbar section -->
    <nav class="navbar">
        <div class="navbar__container">
            <a href="/" id="navbar__logo"><i class="fas fa-gem"></i> NEXT</a>
            <div class="navbar__toggle" id="mobile-menu">
                <span class="bar"></span>
                <span class="bar"></span>
                <span class="bar"></span>
            </div>
            <ul class="navbar__menu">
                <li class="navbar__item">
                    <a href="/" class="navbar__links">Home</a>
                </li>
                <li class="navbar__item">
                    <a href="/tech.html" class="navbar__links">Tech</a>
                </li>
                <li class="navbar__item">
                    <a href="/" class="navbar__links">Products</a>
                </li>
                <li class="navbar__btn">
                    <a href="/" class="button">SignUp</a>
                </li>
            </ul>
        </div>
    </nav>
    <!-- hero section -->
    <div class="main">
        <div class="main__container">
            <div class="main__content">
                <h1>NEXT GEN</h1>
                <h2>Technology</h2>
                <p>see what makes us different </p>
                <button class="main__btn"><a href="/">GET started</a></button>
            </div>
            <div class="main__img--container">
                <img src="images/pic1.svg" alt="pic" id="main__img">
            </div>
        </div>
    </div>
    <!-- service section -->
    <div class="services">
        <h1>See what the hype is about</h1>
        <div class="services__container">
            <div class="services__card">
                <h2>Experience Bliss</h2>
                <p> AI Powered Tech</p>
                <button> Get Started </button>
            </div>
            <div class="services__card">
                <h2>Are you ready </h2>
                <p> Take the leap </p>
                <button> Get Started </button>
            </div>
        </div>
    </div>
    <script src="app.js"></script>
</body>

</html>
