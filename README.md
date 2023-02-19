<h4>Реализованная функциональность</h4>
<ul>
    <li>Ответы на вопросы</li>
    <li>Уведомления в телеграмм</li>
    <li>Помощь при заполнение полей</li>
    <li>Интеграция телеграмм бота на сайт/li>
    <li>Парсинг новых мероприятий по интересам пользователей/li>
</ul> 
<h4>Особенность проекта в следующем:</h4>
<ul>
 <li>Качественные и быстрые ответы на вопросы</li>
 <li>Единая точка входа в сервис</li>
 <li>Предложение пользователям о интересных им событиям</li>  
 </ul>
<h4>Основной стек технологий:</h4>
<ul>
  <li>Python, Fastapi, mysqlite</li>
	<li>HTML, CSS, JavaScript</li>
	<li>Scikitlearn, RuBERT</li>
	<li>Kotlin, ktor, telegram bot api</li>
 </ul>
<h4>Демо</h4>
<p>Инструкция для запуска здесь</p>
<p>https://github.com/ITMEM-HACKATHON-YOUNG-BIT/extension</p>




СРЕДА ЗАПУСКА
------------
1) развертывание сервиса производится на ubuntu linux (ubuntu 20.04);
2) требуется установленный web-сервер с поддержкой Python3.8+, Kotlin1.8, docker, docker-compose, git


УСТАНОВКА
------------
### Установка пакета name

Выполните 
~~~
sudo apt-get update
sudo apt-get upgrade
sudo apt-get install docker-ce docker-ce-cli containerd.io docker-buildx-plugin docker-compose-plugin
git clone https://github.com/ITMEM-HACKATHON-YOUNG-BIT/backend
cd backend
python3 run.py
cd ..
git clone https://github.com/ITMEM-HACKATHON-YOUNG-BIT/TgBot
cd tgBot/build/libs
java -jar {jar file} &
cd ..
git clone https://github.com/ITMEM-HACKATHON-YOUNG-BIT/ParserModule
cd ParserModule
sudo docker-compose up --build --remove-orphans
# После чего остается добавить расширение в браузер

...
~~~

РАЗРАБОТЧИКИ

<h4>Жимоедов Денис product manager https://t.me/denchicez </h4>
<h4>Пономаренко Илья bot developer https://t.me/noisegain </h4>
<h4>Трофимов Максим backend developer https://t.me/trofik00777 </h4>
<h4>Мясников Алексей frontend developer https://t.me/alekmia </h4>


