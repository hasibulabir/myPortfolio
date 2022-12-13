<template>
    <div class="login">
        <div class="formLogin">
            <form>
                <input type="email" placeholder="Enter your Email" />
                <br>
                <input type="password" placeholder="Enter your Password" />
                <br>
                <input type="submit" value="Login" />   
            </form>
        </div>
    </div>
</template>

<style>
    *{
        margin: 0;
        padding: 0;
        box-sizing: border-box;
        font-family: 'Fira sans', sans-serif;
        font-size: 16px;
    }
    .login{
        background: #6c5ce7;
        padding: 0;
        margin: 0;
        width: 100%;
        height: 100vh;
    }
    .formLogin{
        display: flex;
        align-items: center;
        width: 22.8em;
        height: 55em;
        margin: 0 auto 0 auto;
        overflow: hidden;
    }


</style>