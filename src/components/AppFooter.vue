<script>
export default {
    name: 'AppFooter',
}
</script>

<template>

    <footer>
        <div class="container">
            <!-- BARRA DI NAVIGAZIONE FOOTER -->
            <nav class="navbar">
                <!-- PRIA COLONNA -->
                <div class="navbar-col">
                    <h4>DC COMICS</h4>
                    <ul>
                        <li><a href="#">Characters</a></li>
                        <li><a href="#">Comics</a></li>
                        <li><a href="#">Movies</a></li>
                        <li><a href="#">TV</a></li>
                        <li><a href="#">Games</a></li>
                        <li><a href="#">Videos</a></li>
                        <li><a href="#">News</a></li>
                    </ul>

                    <h4>SHOP</h4>
                    <ul>
                        <li><a href="#">Shop DC</a></li>
                        <li><a href="#">Shop DC Collectibles</a></li>
                    </ul>
                </div>

                <!-- SECONDA COLONNA -->
                <div class="navbar-col">
                    <h4>DC</h4>
                    <ul>
                        <li><a href="#">Term Of Use</a></li>
                        <li><a href="#">Privacy Policy (New)</a></li>
                        <li><a href="#">Ad Choices</a></li>
                        <li><a href="#">Advertising</a></li>
                        <li><a href="#">Jobs</a></li>
                        <li><a href="#">Subscriptions</a></li>
                        <li><a href="#">Talent Workshops</a></li>
                        <li><a href="#">CPCS Certificates</a></li>
                        <li><a href="#">Rarings</a></li>
                        <li><a href="#">Shop Help</a></li>
                        <li><a href="#">Contact Us</a></li>
                    </ul>
                </div>

                <!-- TERZA COLONNA -->
                <div class="navbar-col">
                    <h4>SITES</h4>
                    <ul>
                        <li><a href="#">DC</a></li>
                        <li><a href="#">MAD Magazine</a></li>
                        <li><a href="#">DC Kids</a></li>
                        <li><a href="#">DC Universe</a></li>
                        <li><a href="#">DC Power Visa</a></li>
                    </ul>
                </div>
            </nav>
        </div>

        <!-- BARRA SOCIAL -->
        <nav class="social">
            <div class="container">
                <div class="d-flex space-between">
                    <a href="#" class="btn">SIGN UP NOW!</a>
                    <div class="d-center">
                        <h3>FOLLOW US</h3>
                        <div class="social-icon d-flex">
                            <a href="#"><img src="../assets/img/footer-facebook.png" alt="Facebook"></a>
                            <a href="#"><img src="../assets/img/footer-twitter.png" alt="Twitter"></a>
                            <a href="#"><img src="../assets/img/footer-youtube.png" alt="Youtube"></a>
                            <a href="#"><img src="../assets/img/footer-pinterest.png" alt="Pinterest"></a>
                            <a href="#"><img src="../assets/img/footer-periscope.png" alt="Periscope"></a>
                        </div>
                    </div>
                </div>
            </div>
        </nav>
    </footer>

</template>

<style lang="scss" scoped>
footer {
    background-image: url('../assets/img/footer-bg.jpg');
    background-repeat: no-repeat;
    background-size: cover;

    .navbar {
        display: flex;
        padding: 4rem 0;
        gap: 20px;
    }
}



.social {
    background-color: #313131;
    padding: 2rem 0;
}

.btn {
    padding: 10px 20px;
    border: 2px #0282f9 solid;
    color: white;
}

.social-icon {
    gap: 20px;
    margin-left: 20px;
}

h3 {
    color: #0282f9;
}

h4 {
    color: white;
    margin-bottom: 0.5rem;
    margin-top: 0.5rem;
}

a {
    color: #999999;
}
</style>