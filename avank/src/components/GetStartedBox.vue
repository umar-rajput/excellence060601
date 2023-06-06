<template>
    <div class="get-started-box">
        <div class="get-started-box-main">
            <p>{{ no }}</p>
            <p>{{ heading }}</p>
            <p>{{ para }}</p>
            <div class="image">
                <img :src=srcPath alt="">
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name:'GetStartedBox',
    props:['no','heading','para','srcPath']
    // data() {
        
    // },
}
</script>

<style scoped>

</style>