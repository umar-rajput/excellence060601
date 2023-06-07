<template>
    <div class="faq">
        <div class="faq-main mb-3">
            <h1>FAQ’s</h1>
            <p>Some frequently asked questions</p>
            <div class="butons mb-5">
                <FAQsButton question="Can I use my Mastercard/Visa debit card?"></FAQsButton>
                <FAQsButton question="What can I do to keep my account safe?"></FAQsButton>
                <FAQsButton question="How long exchange will be complete?"></FAQsButton>
                <FAQsButton question="How long does it take to verify my account?"></FAQsButton>
            </div>
            <div class="sill-question">
                <p style="font-weight: 600;">Still have a questions?</p>
                <p>If you cannot find answer to your question in our FAQ, <br>
                     you can always contact us. We will answer to you shortly!
                </p>
                <a href="" style="color: #00AC99; font-weight: 500;">Contact Us</a>
            </div>
        </div>
    </div>
</template>

<script>
import FAQsButton from './FAQsButton.vue'

export default {
    name:`FAQs`,
    components:{FAQsButton},
    data() {
        return{
            question:"",
        }
    },
}
</script>

<style scoped>

.faq-main{
    width: 1265px;
    display: flex;
    align-items: center;
    flex-direction: column;
    background: linear-gradient(180deg, #F7F7F7 0%, #FFFFFF 100%);
    padding: 30px 0px;
}
.sill-question{
    padding: 30px 0px;
    text-align: center;
    background: #FFFFFF;
    border: 1px solid rgba(54, 65, 64, 0.16);
    border-radius: 24px;
    width: 704px;
}
</style>