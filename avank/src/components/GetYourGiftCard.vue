<template>
    <div class="get-your-gift-card">
        <div class="get-your-gift-card-main">
            <div class="row get-gift">
                <div class="col-6 get-gift-inner">
                    <span class="heading">Get Your
                        <span style="color: #00AC99;">Gift Card</span>
                    </span>
                    <p class="para">The crypto gift card that turns your everyday <br>
                        purchases into crypto rewards</p>
                    <div class="cards">
                        <img src="../assets/Group976.png" alt="">
                    </div>
                </div>
                <div class="col-6 form">
                    <form action="">
                        <div class="mb-4">
                            <label for="spend" class="mb-2 label">I want to spend</label> <br>
                            <input class="" id="spend">
                            <div class="eur input-inner">
                                <div class="euro-circle">
                                    <span style="font-weight: 600;">€</span>
                                </div>
                                <p style="font-weight: 700;">EUR</p>
                                <div class="upDown ">
                                    <i class="fa-solid fa-angle-up up"></i>
                                    <i class="fa-solid fa-angle-down down"></i>
                                </div>
                            </div>
                        </div>
                        <div class="mb-4">
                            <label for="buy" class="form-label label">I want to buy</label>
                            <input class="" id="buy">
                            <div class="eur input-inner">
                                <div class="euro-circle">
                                    <span style="font-weight: 600;">
                                    <img src="../assets/Vector.png" alt=""></span>
                                </div>
                                <p style="font-weight: 700;">ETH</p>
                                <div class="upDown ">
                                    <i class="fa-solid fa-angle-up up"></i>
                                    <i class="fa-solid fa-angle-down down"></i>
                                </div>
                            </div>
                        </div>
                        <div class="mb-4">
                            <p>You get 0.059335 ETH for 100.00 EUR
                                <!-- <span class=" border border-2 border-dark rounded-circle ">?</span> -->
                                <i class="fa-regular fa-circle-question"></i>
                            </p>
                        </div>
                        <button class="btn add">ADD TO CARD</button>
                    </form>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'GetYourGiftCard',
    // data() {

    // },
}
</script>

<style scoped>
.get-your-gift-card-main{
    width: 1265px;
}
.get-gift {
    height: 530px;
    background: radial-gradient(57.84% 189.04% at 30.77% 42.16%, #BEC6C6 0%, #DEE6E6 100%)
        /* warning: gradient uses a rotation that is not supported by CSS and may not behave as expected */
    ;
    box-shadow: inset 0px -90px 150px rgba(255, 255, 255, 0.24);
    border-radius: 64px;
    margin: 10px 50px;

}

.get-gift-inner {
    padding: 70px 10px 0px 60px;
}

.heading {
    font-weight: 700;
    font-size: 40px;
    color: #232A29;
}

.para {
    color: #364140;
    font-weight: 400;
    line-height: 20px;
}
.form{
    padding: 60px 80px;   
}
.add {
    width: 100%;
    background: linear-gradient(88.84deg, #00AC99 0%, #00E0B0 100%);
    box-shadow: 0px 16px 16px rgba(0, 0, 0, 0.08);
    border-radius: 12px;
    color: #FFFFFF;
    font-weight: 900;
    font-size: 20px;
    padding: 10px 0px;
    border: none;
}

.label {
    font-weight: 500;
}

input {
    width: 100%;
    background: rgba(255, 255, 255, 0.04);
    /* white/transparent/200 */
    border: 2px solid rgba(255, 255, 255, 0.32);
    box-shadow: 0px 4px 16px rgba(17, 53, 45, 0.08);
    backdrop-filter: blur(16px);
    /* Note: backdrop-filter has minimal browser support */
    border-radius: 12px;
    font-weight: 700;
    font-size: 24px;
    padding: 10px 2px 10px 20px;
}
input:focus{
    outline: none;
}
.input-inner{
    display: flex;
    gap: 15px;
    padding: 13px;
    height: 47px;
    width: 130px;
    background: rgba(255, 255, 255, 0.32);
    border-radius: 8px;
    float: right;
    position: relative;
    bottom: 54px;
    right: 6px;
}
.euro-circle{
    height: 25px;
    width: 25px;
    background: #fff;
    text-align: center;
    border-radius: 50%;
}
.upDown{
    position: absolute;
    right: 0px;
}
.up{
    position: relative;
    bottom: 5px;
}
.down{
    position: relative;
    top: 8px;
    right: 14px;
}
</style>