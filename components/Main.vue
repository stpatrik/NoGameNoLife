<!-- Please remove this file from your project -->
<template>
<div>
    <div class="YellowBackground">
        <div class="content-container">
            <div class="content">
            <h1>Присоединись в <br>приключения с нами!</h1>
            
            <p class="text-f">Новый мир, который ждет тебя... <br>Средневековье с магией - не устаревающая классика.<br> Тебя ждут
                приключения и драконы, исследования подземелий и<br> сражения, размеренная жизнь и политические интриги.
                Стань<br> искателем приключений, торговцем или солдатом, а может, именно<br> тебе суждено стать новым
                Императором ?</p>
                <button class="btn">
                    Начать играть
                </button>
            </div>
            <img class="img1" src="~/assets/images/img1.png">
        </div>
    </div>
    <div class="BlueBackground">
        <div class="content-container">
            <img class="img1" src="~/assets/images/img2.png"></img>
            <div>
                <h1>Не следует, однако,  <br>забывать...</h1>
                <p class="text-f">Практический опыт показывает, что курс <br>на социально-ориентированный национальный проект играет важную роль<br> в формировании ключевых компонентов планируемого обновления.<br>Значимость этих проблем настолько очевидна, что повышение...</p>
                <button class="btn">
                    Начать играть
                </button>
            </div>
        </div>
    </div>
</div>
</template>


<style>
.content-container {
    margin-left: 12%;
    margin-right: 12%;
    top: 100px;
    position: relatisve;
    display: flex;
    align-items: center 
}

h1 {
    font-size: 55px;
    color: #212353;
}

h2 {
    font-size: 40px;
    color: #212353;
}

h5 {
    font-size: 18px;
    color: #4B5D68;
}

p {
    font-size: 15px;
    color: #444444;
}

a {
    font-size: 16px;
    color: #4B5D68;
}
.btn {

    color: #ffffff;
    background-color: #7615D8;
    font-size: 18px;
    border: 1px solid #2d63c8;
    border-radius: 18px;
    padding: 15px 50px;
    cursor: pointer;
    width: 250;
    margin-top: 30px;
}
.text-f {
    margin-top: 30px ;
}
.BlueBackground {
    width: 70%;
    height:auto;
    background-color: #00a2ff45;
    border-radius: 50px;
    padding-top: 10px;
    padding-bottom: 10px;
    margin-bottom: 50px;
}

.YellowBackground {
    width: 70%;
    height:auto;
    background-color: #c8ff0045;
    border-radius: 50px;
    padding-top:10px;
    padding-bottom: 10px;
    margin-bottom: 50px;
}
</style>


<script>
export default {
  name: 'Main'
}
</script>
