<!-- Please remove this file from your project -->
<template>
<div>
    <div class="YellowBackground">
        <div class="content-container">
            <div class="content">
            <h1>Присоединись в приключения с нами!</h1>
            
            <p class="text-f">Новый мир, который ждет тебя... Средневековье с магией - не устаревающая классика. Тебя ждут
                приключения и драконы, исследования подземелий и сражения, размеренная жизнь и политические интриги.
                Стань искателем приключений, торговцем или солдатом, а может, именно тебе суждено стать новым
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
                <h1>Не следует, однако,  забывать...</h1>
                <p class="text-f">Практический опыт показывает, что курс на социально-ориентированный национальный проект играет важную роль в формировании ключевых компонентов планируемого обновления.Значимость этих проблем настолько очевидна, что повышение...</p>
                <button class="btn">
                    Начать играть
                </button>
            </div>
        </div>
    </div>
    
    <h1> Наши преимущества</h1>
    
    
</div>
</template>


<style>
body {
    margin: 0px;
    padding: 0px;
}
.content-container {
    margin-left: 12%;
    margin-right: 12%;
    top: 100px;
    position: relatisve;
    display: flex;
    align-items: center 
}

h1 {
    font-size: 50px;
    color: #212353;
    text-align: center;
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
    background-color: #00a2ff45;
    width: 80%;
    height:auto;
    border-radius: 50px;
    padding-top:50px;
    padding-bottom: 50px;
    margin-bottom: 50px;
    margin-left: auto;
    margin-right: auto;
}

.YellowBackground {
    width: 80%;
    height:auto;
    background-color: #c8ff0045;
    border-radius: 50px;
    padding-top:50px;
    padding-bottom: 50px;
    margin-bottom: 50px;
    margin-left: auto;
    margin-right: auto;

}
.img1 { 
    margin-left: 50px;
    margin-right: 50px;

}
.block3 {
    text-align: center;
}
</style>


<script>
export default {
  name: 'Main'
}
</script>
