<template>
    <div class="services">
        <div class="services-main">
            <div class="support">
                <img src="../assets/ic_outline-support-agent.png" alt="" class="me-3">
                <span>Free 24-hour support</span>
            </div>
            <div class="security d-flex align-items-center">
                <div>
                    <img src="../assets/ic_outline-security.png" alt="" class="me-3">
                </div>
                <div>
                    <span>Serious about security <br> & privacy</span>
                </div>
            </div>
            <div class="levels">
                <img src="../assets/bi_speedometer.png" alt="" class="me-3">
                <span>Highest levels of uptime</span>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name:`Services`,
    data() {
        
    },
}
</script>

<style scoped>

.services-main{
    width: 1265px;
    display: flex;
    align-items: center;
    justify-content: space-evenly;
    padding: 20px 0px;
    margin: 40px 0px;
}
</style>