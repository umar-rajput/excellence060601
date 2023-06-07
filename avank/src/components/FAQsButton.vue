<template>
    <div class="faq-button">
        <div class="faq-button-main">
            <button>
                <span style="font-size: 20px;">+</span>
                {{ question }}
            </button>
        </div>
    </div>
</template>

<script>
export default {
    name:'FAQsButton',
    props:['question'],
    data() {
        
    },
}
</script>

<style scoped>
button{
    background: rgba(54, 65, 64, 0.08);
    border-radius: 16px;
    display: flex;
    align-items: center;
    gap: 20px;
    border: none;
    font-weight: 600;
    width: 704px;
    padding: 12px 40px;
    margin-bottom: 10px;
}
</style>