<template>
    <div class="get-started">
        <div class="get-started-main">
            <div class="heading">
                <p class="heading-1" style="font-weight:700; font-size: 32px;"> Get started in a few minutes</p>
                <p class="heading-2" style="font-weight:300">Avank Crypto supports a variety of the most popular digital currencies</p>
            </div>
            <div class="boxes">
                <GetStartedBox no="1" heading="Select the values toexchange"
                para="We store the vast majority of the digital assets in secure."
                srcPath="../assets/Exchange 2.png">

                </GetStartedBox>
            </div>
        </div>
    </div>
</template>

<script>

import GetStartedBox from './GetStartedBox.vue'

export default {
    name:'GetStarted',
    components:{GetStartedBox},

    data() {
        return{
            no:'',
            heading:"",
            para:"",
            srcPath:"",
        }
    },
}
</script>

<style scoped>
.get-started-main{
    margin: 50px 120px;
}

</style>