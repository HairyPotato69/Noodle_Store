<!DOCTYPE html>
<html lang="en">
    <meta charset="UTF-8"/>
    <meta name ="viewport" content="width=device-width, initial-scale=1.0">
    <title> Noodle Store</title>
    <!-- Reset -->
    <link rel="stylesheet" href="../css/normal.css"/>
    <link rel="stylesheet" href="../css/index.css"/>
    <!-- icon -->
    <link rel="icon" sizes="16x16" href="../icons/ramen_icon.svg"/>
</html>
<body>
    <!-- This is the area that immediately shows up on the screen under your logo and menu -->
    <section id="hero">
        <!-- This will contain things inside of the hero -->
        <div class="container">
            <video 
                autoplay
                muted
                loop>
                <source src="videos/video-1@c.mp4" type="video/mp4"/>
            </video> 
            <header>
                <a href="index.html" style="filter: invert(93%) sepia(94%) saturate(0%) hue-rotate(248deg) brightness(106%) contrast(106%);"><img src = "../icons/ramen_icon.svg"></a>
                <nav>
                    <ul>
                        <li><a href = "index.html"> Home </a></li>
                        <li><a id ="anchor-about" href = "#"> About </a></li>
                        <li><a href = "#"> Product </a></li>
                        <li><a href = "#"> Contact </a></li>
                        <li><a target="_blank" class="has_external_links" href = "https://github.com/HairyPotato69">Github</a></li>
                    </ul>
                </nav>
            </header>
            <h1>
                Noodles that you can <span style="color:blanchedalmond">slurp</span> for days
            </h1>
        </div>
    </section>
    <section id ="product-showcase">
        <header>
            <p style="color:red">Attractive texts</p>
            <h1>
                Products
            </h1>
            <p>
                description about product
            </p>
        </header>

        <ul class="gallery">
            <li>
                <figure>
                    <img src="images/green-noodle.png">
                    <figcaption>

                        <main>
                            <h3>Product A</h3>
                            <p>Description about product A</p>
                            <p>More description about product A</p> 
                        </main>
                        
                        <footer>
                            <div>
                                <p class = "small">Price:</p>
                                <p class = "price">$123456</p>
                            </div>

                            <img src="Icons/pay.svg" alt="Icon" style="filter: invert(93%) sepia(94%) saturate(0%) hue-rotate(248deg) brightness(106%) contrast(106%);width: 48px; height: 48px;"/>
                            <!-- img -->
                        </footer>

                    </figcaption>
                </figure>
            </li>
            <li>
                <figure>
                    <img src="images/pumpkin-noodle.png">
                    <figcaption>

                        <main>
                            <h3>Product A</h3>
                            <p>Description about product A</p>
                            <p>More description about product A</p> 
                        </main>
                        
                        <footer>
                            <div>
                                <p class = "small">Price:</p>
                                <p class = "price">$123456</p>
                            </div>

                            <img src="Icons/pay.svg" alt="Icon" style="filter: invert(93%) sepia(94%) saturate(0%) hue-rotate(248deg) brightness(106%) contrast(106%);width: 48px; height: 48px;"/>
                            <!-- img -->
                        </footer>

                    </figcaption>
                </figure>
            </li>
            <li>
                <figure>
                    <img src="images/purple-noodle.png">
                    <figcaption>

                        <main>
                            <h3>Product A</h3>
                            <p>Description about product A</p>
                            <p>More description about product A</p> 
                        </main>
                        
                        <footer>
                            <div>
                                <p class = "small">Price:</p>
                                <p class = "price">$123456</p>
                            </div>

                            <img src="Icons/pay.svg" alt="Icon" style="filter: invert(93%) sepia(94%) saturate(0%) hue-rotate(248deg) brightness(106%) contrast(106%);width: 48px; height: 48px;"/>
                            <!-- img -->
                        </footer>

                    </figcaption>
                </figure>
            </li>
            <li>
                <figure>
                    <img src="images/red-noodle.png">
                    <figcaption>

                        <main>
                            <h3>Product A</h3>
                            <p>Description about product A</p>
                            <p>More description about product A</p> 
                        </main>
                        
                        <footer>
                            <div>
                                <p class = "small">Price:</p>
                                <p class = "price">$123456</p>
                            </div>

                            <img src="Icons/pay.svg" alt="Icon" style="filter: invert(93%) sepia(94%) saturate(0%) hue-rotate(248deg) brightness(106%) contrast(106%);width: 48px; height: 48px;"/>
                            <!-- img -->
                        </footer>

                    </figcaption>
                </figure>
            </li>
        </ul>
    </section>

    <footer>
        <p>hello</p>
    </footer>
</body>
