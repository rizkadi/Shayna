<template>
        <!-- Footer Section Begin -->
    <footer class="footer-section">
        <div class="container">
            <div class="row">
                <div class="col-lg-5">
                    <div class="footer-left">
                        <div class="footer-logo">
                            <router-link to="/"><img src="../../public/img/logo_website_shayna_white.png" alt="" /></router-link>
                        </div>
                        <ul>
                            <li>Address: Setra Duta, Bandung</li>
                            <li>Phone: +628 22081996</li>
                            <li>Email: hello.shayna@gmail.com</li>
                        </ul>
                        <div class="footer-social">
                            <a ><i class="fa fa-facebook"></i></a>
                            <a ><i class="fa fa-instagram"></i></a>
                            <a ><i class="fa fa-twitter"></i></a>
                            <a ><i class="fa fa-pinterest"></i></a>
                        </div>
                    </div>
                </div>
                <div class="col-lg-3 offset-lg-1">
                    <div class="footer-widget">
                        <h5>Information</h5>
                        <ul>
                            <li><a >About Us</a></li>
                            <li><a>Checkout</a></li>
                            <li><a >Contact</a></li>
                            <li><a >Serivius</a></li>
                        </ul>
                    </div>
                </div>
                <div class="col-lg-3">
                    <div class="footer-widget">
                        <h5>My Account</h5>
                        <ul>
                            <li><a >My Account</a></li>
                            <li><a >Contact</a></li>
                            <li><a >Shopping Cart</a></li>
                            <li><a >Shop</a></li>
                        </ul>
                    </div>
                </div>
            </div>
        </div>
        <div class="copyright-reserved">
            <div class="container">
                <div class="row">
                    <div class="col-lg-12">
                        <div class="copyright-text">
                            Copyright &copy;
                            <!-- <script>
                                document.write(new Date().getFullYear());
                            </script> -->
                            {{ new Date().getFullYear() }}
                            All rights reserved | Shayna
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </footer>
    <!-- Footer Section End -->
</template>

<script>
    // import carousel from 'vue-owl-carousel'

    export default {
    name: 'FooterShayna',
    components: {
        // HelloWorld
        //  carousel
        }
    }
</script>

<style scooped>
.footer-section{
    text-align :left
}
</style>