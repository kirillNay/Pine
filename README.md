# Pine
Решение задачи Yandex Cup 2022.
<br>
<h3>Условие задачи</h3>
Участники клуба любителей природы очень любит ходить по лесу. Но вот беда, делают они все это в очень разное время, но очень хотят общаться друг с другом и обсуждать вопросы ухода за лесом и другие ботанические темы. В центре леса есть одна очень старая сосна, мимо которой так или иначе проходят все дорожки.

Для целей помощи любителя природы предположим, что в сосну можно спрятать телефон на котором будет постоянно работать приложение.

Необходимо реализовать возможность любителям природы общаться друг с другом вокруг этой сосны. Сообщения будут хранится в телефоне, внутри сосны спрятанном. Обмен сообщениями допускается, если любитель природы находится рядом (дойти до сосны обязательное требование, или человек не считается любителем природы). Можно оставить либо текстовое сообщение, либо повестить картинку в дополненной реальности.

Ваша задача написать обе части приложения - для сосны и для любителя природы. В простом варианте возможен текстовый обмен сообщениями, но за дополненную реальность вы получите больше баллов.
<br>
<h3>Архитектура</h3>
<h5>Используемые технологии и основные библиотеки</h5>
<li><a href="https://developer.android.com/jetpack/compose">Jetpack Compose</a></li>
<li><a href="https://github.com/terrakok/Cicerone">Cicerone</a></li>
<li><a href="https://insert-koin.io/">Koin</a></li>
<li><a href="https://github.com/NordicSemiconductor/Android-BLE-Library">Nordic</a></li>
<br>
<h5>Модульность</h5>
<code>
├── app
├── features
│   ├── mainmenu
│   ├── ...
|
├──bluetooth-sdk
    ├── scanning
    ├── client
    ├── server
    ├── ...
</code>
