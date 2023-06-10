<template>
    <div class="get-started-box">
        <div class="get-started-box-main">
            <h1 style="font-weight: 600; font-size: 64px;">{{ no }}</h1>
            <h4 style="font-weight: 700; font-size: 20px;">{{ heading }}</h4>
            <p style="margin-bottom: 30px;">{{ para }}</p>
            <div class="image">
                <!-- <img v-bind:src="srcPath" alt=""> -->
                <img :src="src" alt="">
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name:'GetStartedBox',
    props:['no','heading','para','src'],
    data() {
        return{
            pth:"../assets/Exchange_2.png",
        }
    },
}
</script>

<style scoped>

</style>