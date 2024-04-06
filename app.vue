<template>
  <div class="left-info">
    <img src="https://cdn.discordapp.com/attachments/1182034737599090800/1213523679456010311/host.png?ex=661ab2ff&is=66083dff&hm=c0ee5a050d5537e4e5ca714a91c2fb3628893e881926f93c871d94bbb9139106" alt="" class="profile-picture">
    <h1>Привет! Меня зовут </h1>
    <p class="add">Я веб-разработчик из России. Пишу разные вещи на js и тд.</p>
    <div class="info">
      
      <p>{{ currentTime }}</p>
      <p>{{ currentWeather }}</p>
    </div>
  </div>
  <div class="projects">
    <h2 class="projects-h2"><span class="completed">Завершенные</span> проекты</h2>
    <a href="https://spidernodes.space" class="spidernodes-button">
      <div class="spidernodes">
        <div class="html-logo">
          <img src="./png-transparent-logo-html-html5.png" alt="HTML Logo">
          <img src="./css.png" alt="CSS Logo">

        </div>
        <h3>SpiderNodes</h3>
        <p>Март 2024 - до сих пор.</p>
        <p>SpiderNodes - это надежный хостинг, который обеспечивает<br> высокую скорость и безопасность для вашего сервера.</p>
      </div>

      <a href="https://shadowmanager.space" class="spidernodes-button">
        <div class="spidernodes">
          <div class="html-logo">
            <img src="./png-transparent-logo-html-html5.png" alt="HTML Logo">
            <img src="./css.png" alt="CSS Logo">
  
          </div>
          <h3>ShadowManager</h3>
          <p>Март 2024 - до сих пор.</p>
          <p>ShadowManager — многофункциональный бот, <br> предназначенный для улучшения и защиты вашего сервера Discord.</p>
        </div>
      </a>

      
      <a href="https://akitiltka.space" class="spidernodes-button">
        <div class="spidernodes">
          <div class="html-logo">
            <img src="./png-transparent-logo-html-html5.png" alt="HTML Logo">
            <img src="./css.png" alt="CSS Logo">
  
          </div>
          <h3>akitiltka.space</h3>
          <p>Март 2024 - до сих пор.</p>
          <p>Сайт на котром вы щас находитесь.</p>
        </div>
      </a> 
      <a href="https://github.com/Elytrya/WarivetryProject" class="spidernodes-button">
        <div class="spidernodes">
          <div class="html-logo">
            <img src="./png-transparent-logo-html-html5.png" alt="HTML Logo">
            <img src="./css.png" alt="CSS Logo">
  
          </div>
          <h3>warivetryproject.xyz {old}</h3>
          <p>Декабрь 2023 - Январь 2024.</p>
          <p>Старый сайт WarivetryProject </p>
        </div>
      </a> 
      <a href="https://github.com/Akitilltka/akitiltka" class="spidernodes-button">
        <div class="spidernodes">
          <div class="html-logo">
            <img src="./png-transparent-logo-html-html5.png" alt="HTML Logo">
            <img src="./css.png" alt="CSS Logo">
  
          </div>
          <h3>akitiltka.space {OLD}</h3>
          <p>Ноябрь 2023 - Декабря 2023.</p>
          <p>Старый сайт akitiltka.space</p>
        </div>
      </a> 
      <a href="https://github.com/Elytrya/lousky" class="spidernodes-button">
        <div class="spidernodes">
          <div class="html-logo">
            <img src="./png-transparent-logo-html-html5.png" alt="HTML Logo">
            <img src="./css.png" alt="CSS Logo">
  
          </div>
          <h3>LouSky {old}</h3>
          <p>Сентябрь 2023 - Октябрь 2023.</p>
          <p>Старый сайт LouSky</p>
        </div>
      </a> 
      <a href="https://github.com/Elytrya/rilikclient" class="spidernodes-button">
        <div class="spidernodes">
          <div class="html-logo">
            <img src="./png-transparent-logo-html-html5.png" alt="HTML Logo">
            <img src="./css.png" alt="CSS Logo">
  
          </div>
          <h3>RillikClient [OLD]</h3>
          <p>Октябрь 2023 - Ноябрь 2023</p>
          <p>Сайт для чит клиента RillikClient.</p>
        </div>
      </a> 
      <a href="https://github.com/Akitilltka/rillikclienthack.fun" class="spidernodes-button">
        <div class="spidernodes">
          <div class="html-logo">
            <img src="./png-transparent-logo-html-html5.png" alt="HTML Logo">
            <img src="./css.png" alt="CSS Logo">
  
          </div>
          <h3>rillikclienthack.fun [VUE.JS] [OLD]</h3>
          <p>Октябрь 2023 - Ноябрь 2023</p>
          <p>Сайт для чит клиента RillikClient. Написан на vue.js</p>
        </div>
      </a> 
      <a href="https://github.com/Akitilltka/rillikclienthack.fun" class="spidernodes-button">
        <div class="spidernodes">
          <div class="html-logo">
            <img src="./png-transparent-logo-html-html5.png" alt="HTML Logo">
            <img src="./css.png" alt="CSS Logo">
  
          </div>
          <h3>jokeapi_vuejs [OLD]</h3>
          <p>Октябрь 2023 - Ноябрь 2023</p>
          <p>Сайт который нужен был для академии.</p>
        </div>
      </a> 
      <a href="https://github.com/Elytrya/akitiltka.space" class="spidernodes-button">
        <div class="spidernodes">
          <div class="html-logo">
            <img src="./png-transparent-logo-html-html5.png" alt="HTML Logo">
            <img src="./css.png" alt="CSS Logo">
  
          </div>
          <h3>akitiltka.space [VUE.JS] [OLD]</h3>
          <p>Октябрь 2023 - Ноябрь 2023</p>
          <p>Старый сайт akitiltka.space. Написан на vue.js</p>
        </div>
      </a> 
      <a href="https://github.com/Elytrya/jokeapi_vuejs" class="spidernodes-button">
        <div class="spidernodes">
          <div class="html-logo">
            <img src="./png-transparent-logo-html-html5.png" alt="HTML Logo">
            <img src="./css.png" alt="CSS Logo">
  
          </div>
          <h3>jokeapi_vuejs [OLD]</h3>
          <p>Октябрь 2023 - Ноябрь 2023</p>
          <p>Сайт который нужен был для академии.</p>
        </div>
      </a> 

      <a href="https://github.com/Elytrya/requestmanager" class="spidernodes-button">
        <div class="spidernodes">
          <div class="html-logo">
            <img src="./python.png" alt="python">
  
          </div>
          <h3>requestmanager</h3>
          <p>Октябрь 2023 - Ноябрь 2023</p>
          <p>Обычный парсер для python</p>
        </div>
      </a> 

      <a href="https://github.com/Elytrya/Mineparser" class="spidernodes-button">
        <div class="spidernodes">
          <div class="html-logo">
            <img src="./python.png" alt="python">
  
          </div>
          <h3>Mineparser</h3>
          <p>Март 2024 - До сих пор</p>
          <p>Парсер серверов для майнкрафт</p>
        </div>
      </a> 

      <a href="https://github.com/Elytrya/PCControl.py" class="spidernodes-button">
        <div class="spidernodes">
          <div class="html-logo">
            <img src="./python.png" alt="python">
  
          </div>
          <h3>PCControl</h3>
          <p>Январь 2024 - Февраля 2024 </p>
          <p>PCControl - удаленный доступ к ПК Через бота в дискорд</p>
        </div>
      </a> 
    </a>

      <a href="https://github.com/Elytrya/TimeControll" class="spidernodes-button">
        <div class="spidernodes">
          <div class="html-logo">
            <img src="./python.png" alt="python">
  
          </div>
          <h3>TimeControll</h3>
          <p>Февраля 2024 - Март 2024</p>
          <p>TimeControl - напоминания через дискорд</p>
        </div>
      </a> 
      <a href="https://github.com/Elytrya/FontChanger" class="spidernodes-button">
        <div class="spidernodes">
          <div class="html-logo">
            <img src="./python.png" alt="python">
  
          </div>
          <h3>FontsChanger</h3>
          <p>Март 2024 - Апрель 2024</p>
          <p>FontsChanger - красивый шрифт</p>
        </div>
      </a> 

      <a href="https://github.com/Elytrya/Generator-user-passwords" class="spidernodes-button">
        <div class="spidernodes">
          <div class="html-logo">
            <img src="./python.png" alt="python">
  
          </div>
          <h3>Generator-user-passwords </h3>
          <p>Март 2024 - Апрель 2024</p>
          <p>Генератор паролей и фейковых пользователей</p>
        </div>
      </a> 


  </div>
<footer>
  <p>design by elytrya__</p>
</footer>
</template>



<script>
  export default {
    data() {
      return {
        currentTime: '',
        currentWeather: ''
      };
    },
    mounted() {
      this.updateTime(); // Сначала обновляем время
      this.updateWeather(); // Затем обновляем погоду
  
      // Запускаем интервал обновления времени каждую секунду
      setInterval(() => {
        this.updateTime();
      }, 1000);
  
      // Запускаем интервал обновления погоды каждые 5 секунд
      setInterval(() => {
        this.updateWeather();
      }, 5000);
    },
    methods: {
      updateTime() {
        const currentDate = new Date();
        this.currentTime = currentDate.toLocaleString('ru-RU', {
          day: 'numeric',
          month: 'long',
          year: 'numeric',
          hour: 'numeric',
          minute: 'numeric',
          second: 'numeric'
        });
      },
      updateWeather() {
        const apiKey = '89bdc4e4cb2fd40ace1dcd0c34549510';
        const city = 'Tula';
        const apiUrl = `https://api.openweathermap.org/data/2.5/weather?q=${city}&appid=${apiKey}&lang=ru&units=metric`;
  
        fetch(apiUrl)
          .then(response => response.json())
          .then(data => {
            this.currentWeather = `${data.main.temp} °C • ${data.weather[0].description}`;
          })
          .catch(error => {
            console.error('Ошибка при получении данных о погоде:', error);
          });
      }
    }
  };
  </script>


<style>
@import url('https://fonts.googleapis.com/css2?family=Ubuntu+Mono:ital,wght@0,400;0,700;1,400;1,700&display=swap');












footer{
  text-align: center;
  color: white;
}


.spidernodes-button {
  display: inline-block;
  padding: 10px 20px;
  background-color: #262626; /* зеленый цвет */
  color: #fff; /* белый цвет текста */
  text-decoration: none; /* удаление подчеркивания */
  border-radius: 20px; /* закругление углов */
  transition: background-color 0.3s; /* плавный переход */
  padding: 20px; /* Внутренний отступ блока */
  margin-left: 20px;
  margin-top: 20px;

}

.spidernodes-button:hover {
  background-color: #252626; /* темнозеленый цвет при наведении */
}




.html-logo {
  display: flex;
  align-items: center;
  margin-bottom: 10px; /* отступ между логотипом и заголовком */
}

.html-logo img {
  width: 50px; /* задайте размер логотипа HTML */
  height: auto;
  margin-right: 10px; /* отступ между логотипом и текстом */
}



.projects-h2{
  text-align: center;
  color: white;
  margin: 350px;
  font-size: 40px;
}
a{
  font-size: 20px;
}
.profile-picture{
  box-shadow: 20px 20px 130px rgb(255, 166, 0);
}


.left-info {
  margin-right: 20px; /* Отступ справа от границ сайта */
}

.completed {
  color: #00ff00; /* Зеленый цвет */
  
  text-shadow: 20px 20px 150px #00ff00;
}

  .add{
    font-size: 30px;
    color: gray;
  }
  .info{
    font-size: 20px;
    color: gray;
  }
  body {
    background-color: #171717;
    font-family: "Ubuntu Mono", monospace;
  }
  .left-info {
    text-align: left;
    color: white;
    margin-left: 100px;
    margin: 100px;
  } 
  .profile-picture {
    width: 100px; /* Размер по вашему выбору */
    height: 100px; /* Размер по вашему выбору */
    border-radius: 50%; /* Сделаем круглый */
    transition: transform 0.3s; /* Добавим плавное изменение при наведении */
  }
  .profile-picture:hover {
    transform: scale(1.2); /* Увеличение при наведении */
  }

  .profile-picture:hover {
    transform: scale(1.2); /* Увеличение при наведении */
  }
  h1{
    font-size: 40px;
  }
  h1::after {
    content: "elytrya__"; /* Добавляем "__" после заголовка */
    background: rgb(226,77,32);
    background: linear-gradient(90deg, rgba(226,77,32,1) 0%, rgba(214,150,97,1) 100%);
    background-clip: text;
    -webkit-background-clip: text;
    color: transparent;
  }





</style>
