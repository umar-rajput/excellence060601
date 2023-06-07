<template>
    <div class="get-started">
        <div class="get-started-main">
            <div class="heading">
                <p class="heading-1 mb-1" style="font-weight:700; font-size: 32px;"> Get started in a few minutes</p>
                <p class="heading-2 mb-5" style="font-weight:300">Avank Crypto supports a variety of the most popular
                    digital currencies</p>
            </div>
            <div class="boxes d-flex">
                <GetStartedBox no="1" heading="Select the values to exchange"
                    para="We store the vast majority of the digital assets in secure." :src="imgUrl1" class="box1">
                </GetStartedBox>
                <GetStartedBox no="2" heading="Verify your identity" para="Avank maintains crypto insurance and all balances are covered by FDIC insurance." :src="imgUrl2" class="box2">
                </GetStartedBox>
                <GetStartedBox no="3" heading="Confirm your wallet or bank account details" para="Avank supports a variety of the most popular digital." :src="imgUrl3" class="box3">
                </GetStartedBox>
            </div>
        </div>
    </div>
</template>

<script>

import GetStartedBox from './GetStartedBox.vue'

export default {
    name: 'GetStarted',
    components: { GetStartedBox },

    data() {
        return {
            no: '',
            heading: "",
            para: "",
            imgUrl1: require('../assets/Exchange_2.png'),
            imgUrl2: require('../assets/Finger_Print_1.png'),
            imgUrl3: require('../assets/Bank_1.png'),
        }
    },
}
</script>

<style scoped>
.get-started-main {
    margin: 50px 120px;
    padding: 0px 100px;
    width:1265px;
}

.box1 {
    background-image: url('../assets/BG1.png');
    background-repeat: no-repeat;
    width: 337px;
    height: 400px;
    padding: 48px 37px;
    background-size: cover;
}

.box1::v-deep h1 {
    color: #006E62;
}

.box2 {
    background-image: url('../assets/BG2.png');
    background-repeat: no-repeat;
    width: 353px;
    height: 402px;
    padding: 47px 21px 47px 60px;
    background-size: cover;
}

.box2::v-deep h1 {
    color: #00AC99;
}

.box3 {
    background-image: url('../assets/BG3.png');
    background-repeat: no-repeat;
    width: 328px;
    height: 400px;
    padding: 48px 20px 48px 60px;
    background-size: cover;
}

.box3::v-deep h1 {
    color: #00E0B0;
}
</style>