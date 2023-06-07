<template>
    <div class="header">
        <div class="header-main">
            <nav>
                <div class="row align-items-center navbar">
                    <div class="col-3">
                        <div class="logo text-center">
                            <img src="../assets/logo.png" alt="">
                        </div>
                    </div>
                    <div class="col-4 list">
                        <ul class="nav">
                            <li class="nav-item"><a href="" class="nav-link disabled">EXCHANGE</a></li>
                            <li class="nav-item"><a href="" class="nav-link disabled">BNPL</a></li>
                            <li class="nav-item"><a href="" class="nav-link active">CARDS</a></li>
                        </ul>
                    </div>
                    <div class="col-1"></div>
                    <div class="col-1">
                        <select class="form-select disabled select-option" aria-label="Default select example">
                            <option selected>EN</option>
                            <option value="EN">English</option>
                            <option value="HD">Hindi</option>
                            <option value="FR">French</option>
                        </select>
                    </div>
                    <div class="col-3 d-flex gap-2">
                        <div class="login buttons">
                            <button>LOG IN</button>
                        </div>
                        <div class="signup buttons">
                            <button>SIGN UP</button>
                        </div>
                    </div>
                </div>
            </nav>
        </div>
    </div>
</template>

<script>
export default {
    name: `Header`,
    // data() {

    // },
}
</script>

<style scoped>
li {
    list-style-type: none;
}
.header-main{
    width: 1265px;
}
.navbar {
    padding: 15px 50px;
    width: 1265px;
}

.list ul {
    font-weight: 800;
}

a {
    text-decoration: none;
    color: #000;
}

.disabled {
    color: rgba(54, 65, 64, 0.64);
}
.form-select{
    border-radius: 20px;
    border: none;
    box-shadow: none;
    font-size: 12px;
    padding: 10px 20px;
}
.buttons button{
    border-radius: 20px;
    border: none;
    color: rgba(54, 65, 64, 0.8);
    font-weight: 800;
    font-size: 14px;
    padding: 10px 25px;
}
.login button{
    background: rgba(54, 65, 64, 0.04);
}
.signup button{
    background: #fff;
    box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.08);
}
</style>