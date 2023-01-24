<script>
export default {
    name: 'AppFooter',
}
</script>

<template>

    <footer>
        <nav class="navbar">

        </nav>

        <div class="container">
            <nav class="social d-flex">
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
            </nav>
        </div>
    </footer>

</template>

<style>
footer {
    background-color: #313131;
}

.navbar {
    height: calc(100vh - 450px);
    background-image: url('../assets/img/footer-bg.jpg');
    display: flex;
    justify-content: center;
    align-items: center;
}

.social {
    height: 150px;
    justify-content: space-between;
    align-items: center;
}

.btn {
    padding: 10px 20px;
    border: 2px blue solid;
    color: white;
}

.social-icon {
    gap: 20px;
    margin-left: 20px;
}

h3 {
    color: blue;
}
</style>