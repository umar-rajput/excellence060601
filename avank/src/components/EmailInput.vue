<template>
    <div class="email-input">
        <div class="email-input-main mb-4">
            <form action="">
                <input type="text" placeholder="Enter your email">
                <button> GET STARTED</button>
            </form>
        </div>
    </div>
</template>

<script>
export default {
    name: `EmailInput`,
    // data() {

    // },
}
</script>

<style scoped>
/* .email-input{
    width: 100px;
} */
.email-input-main {
    background: #00AC99;
    box-shadow: inset 0px -92px 148px rgba(255, 255, 255, 0.26);
    border-radius: 40px;
    height: 200px;
    width: 1130px ;
    display: flex;
    justify-content: center;
    align-items: center;
    margin: 15px 85px;
    background-image: url('../assets/Sphere_3.png');
    background-repeat: no-repeat;
    background-position: 220px;
}
.email-input-main form{
    width: 750px;
}
.email-input-main input {
    background: rgba(54, 65, 64, 0.08);
    color:#fff;
    border: 2px solid rgba(255, 255, 255, 0.32);
    box-shadow: 0px 4px 16px rgba(17, 53, 45, 0.08);
    -webkit-backdrop-filter: blur(16px);
    backdrop-filter: blur(16px);
    border-radius: 16px;
    padding: 12px 20px;
    width: 70%;
    margin-right: 15px;
}
.email-input-main input:focus{
    outline: none;
}
.email-input-main input::placeholder{
    color: #fff;
}
.email-input-main button {
    background: #FFFFFF;
    box-shadow: 0px 8px 16px rgba(0, 0, 0, 0.08);
    font-weight: 800;
    font-size: 20px;
    color: #00AC99;
    border: none;
    border-radius: 16px;
    padding: 10px 30px;
}
</style>