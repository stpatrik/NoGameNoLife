<template>
    <header>
        <div class="flex-container">            
            <img class="img-logo" src="~/assets/icons/logo.svg">
            <a>Discord</a>
            <a>Wiki</a>
            <a>Форум</a>
            <NuxtLink to="/test"><a>Лаунчер</a> </NuxtLink>
            <a>Магазин</a>
            <a class="last">Присоедениться</a>
            <img class="img-login" src="~/assets/icons/login.svg">

        </div>
    </header>
</template>


<style>
* {

    margin-left: auto;
    margin-right: auto;
}

body {
    margin: 0;
    padding: 0;
    margin-left: auto;
    margin-right: auto;
}

header {
    width: 100%;
    height: 120px;
    text-align: center;
    margin-bottom: 100px;
}

.flex-container {
    text-align: center;
    vertical-align: middle;
    display: flex;
}
.flex-container a { 
    text-align: center;
    vertical-align: middle;
    margin-top: 20px;
}

.img-logo {
    bottom: 10px;
    margin-right: 160px;
}

.last {
    margin-right: 0px;
    margin-left: 0px;
    padding-left: 140px;

}

.img-login {
    margin-top: 5px;
    margin-left: 6px;

}

</style>


<script>
export default {
  name: 'Header'
}
</script>
