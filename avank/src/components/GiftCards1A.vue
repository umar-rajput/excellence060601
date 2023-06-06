<template>
    <div class="GiftCards">
        <div class="GiftCards-main">
            <Header></Header>
            <GetYourGiftCard></GetYourGiftCard>
            <GetStarted></GetStarted>
        </div>
    </div>
</template>

<script>
import Header from './Header.vue'
import GetYourGiftCard from './GetYourGiftCard.vue'
import GetStarted from './GetStarted.vue'

export default {
    name:'GiftCards1A',
    components:{Header,GetYourGiftCard,GetStarted},
    // data() {
        
    // },
}
</script>

<style scoped>

.GiftCards{
    font-family: Montserrat;
    overflow: hidden;
}

</style>