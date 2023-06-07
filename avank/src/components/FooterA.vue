<template>
    <div class="footer">
        <div class="footer-main">
            <img src="../assets/Scroll_to_Top.png" alt="" class="arrow">
            <div class="footer-inner">
                <div class="logo">
                    <div class="logo1">
                        <img src="../assets/logo.png" alt="">
                    </div>
                    <div class="social">
                        <div class="twitter social-inner">
                            <i class="fa-brands fa-twitter"></i>
                        </div>
                        <div class="linkedin social-inner">
                            <i class="fa-brands fa-linkedin"></i>
                        </div>
                        <div class="instagram social-inner">
                            <img src="../assets/instagram.png" alt="">
                        </div>
                        <div class="facebook social-inner">
                            <i class="fa-brands fa-facebook"></i>
                        </div>
                    </div>
                    <div class="copyright">
                        <p style="font-size: 12px;">Copyright 2023 ® Avank. All Rights Reserved.</p>
                        <p style="font-size: 10px;">Avank LLC is a registered money service business (Reg# 16013890)</p>
                    </div>
                </div>
                <div class="menu">
                    <div class="menu1">
                        <p>MENU</p>
                        <ul>
                            <li>Exchange</li>
                            <li>BNPL</li>
                            <li>Gift Cards</li>
                        </ul>
                    </div>
                    <div class="menu2">
                        <p>COMPANY</p>
                        <ul>
                            <li>About Us</li>
                            <li>Contacts</li>
                            <li>Privacy Policy</li>
                            <li>Terms of Service</li>
                        </ul>
                    </div>
                    <div class="menu3">
                        <p>LEGAL</p>
                        <ul>
                            <li>AML/KYC Policy</li>
                            <li>Cookie Policy</li>
                            <li>Security Policy</li>
                            <li>Refund Policy</li>
                        </ul>
                    </div>

                </div>
                <div class="app">
                    <p>DOWNLOAD THE APP</p>
                    <img src="../assets/iOS.png" alt="" class="mb-2">
                    <img src="../assets/Android.png" alt="">
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: `FooterA`,
    data() {

    },
}
</script>

<style scoped>
.footer-main {
    width: 1265px;
    background-image: url('../assets/hot_cold_3_1.png');
    background-repeat: no-repeat;
    background-position: -60px 65px;
    margin-top: 70px;
}
.arrow{
    position: relative;
    top: 20px;
    left: 50%;
}
.footer-inner{
    display: flex;
    justify-content: space-between;
    margin: 0px 100px;
    border-top: 1px solid #dfe0e0;
    padding: 80px 0px 5px 0px;
}

.logo {
    width: 338px;
    height: 218px;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
}

.social {
    display: flex;
    gap: 6px;
}

.social-inner {
    background: rgba(54, 65, 64, 0.08);
    border-radius: 8px;
    width: 32px;
    height: 32px;
    display: flex;
    justify-content: center;
    align-items: center;
}

.menu {
    width: 450px;
    height: 170px;
    display: flex;
    justify-content: space-between;
}

.menu ul {
    padding-left: 0rem;
}

.menu li {
    list-style-type: none;
    font-weight: 600;
    margin-bottom: 10px;
}

.app {
    width: 180px;
    height: 155px;
}
</style>