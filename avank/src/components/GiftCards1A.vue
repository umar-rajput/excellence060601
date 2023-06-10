<template>
    <div class="GiftCards">
        <div class="GiftCards-main">
            <Header></Header>
            <GetYourGiftCard></GetYourGiftCard>
            <GetStarted></GetStarted>
            <FAQs></FAQs>
            <EmailInput></EmailInput>
            <Services></Services>
            <FooterA></FooterA>
        </div>
    </div>
</template>

<script>
import Header from './Header.vue'
import GetYourGiftCard from './GetYourGiftCard.vue'
import GetStarted from './GetStarted.vue'
import FAQs from './FAQs.vue'
import EmailInput from './EmailInput.vue'
import Services from './Services.vue'
import FooterA from './FooterA.vue'

export default {
    name:'GiftCards1A',
    components:
        {
            Header,
            GetYourGiftCard,
            GetStarted,
            FAQs,
            EmailInput,
            Services,
            FooterA
        },
    // data() {
        
    // },
}
</script>

<style scoped>

.GiftCards{
    font-family: Montserrat;
    /* overflow: hidden; */
    display: flex;
    justify-content: center;
}

.GiftCards-main{
    /* max-width: 1265px; */
    width: 1265px;
}

</style>