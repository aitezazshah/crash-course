<template>
    <div class="container">
        <div class="logo">
        <img src="../assets/Devaxl.png" alt="">
        
        </div>
        <div class="login">
        
        <input type="text" placeholder="Enter your email address"/>
        <input type="text" placeholder="Enter your password" />
        <button>Login</button>
        </div>
    </div>
    
</template>

<script>


export default {
    name: 'Login'
    
}
</script>

<style>
.container{
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    
    
}

.logo{
    width: 150px;
}
.login{
    display: flex;
    justify-content: center;
    flex-direction: column;
}
.login input{
    width: 300px;
    height: 40px;
    padding-left: 20px;
    display: block;
    margin-bottom: 30px;
    margin-right: auto;
    margin-left: auto;
    border: 1px solid skyblue;
    
}
.login button{
    height: 30px;
    background-color: goldenrod;
    border: none;
    cursor: pointer;
}
</style>
