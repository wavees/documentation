# Про наши методы авторизации.

> Про то, какой подход авторизации используем мы.

Другие сервисы авторизации слишком сложны, там нужны какие-то подтверждения, подключение каких-то библиотек и много другой подобной и не-очень-то-и-быстрой работы. Мы же в свою очередь можем предложить вам максимально быстрый и максимально логичный вариант из всех - банальное перенаправление пользователя на другую страничку. Да-да! Про это вы сможете узнать ниже.

Ну и как же работает наша мега-крутая система авторизации? Для того, что бы "попросить" пользователя авторизоваться - вам просто нужно перенаправить его на опеределённую ссылку *(про то, как получить эту ссылку вы узнаете ниже)*, из которой пользователь потом вернётся на ваш сайт с Токеном Пользователя!

?> Хотите узнать про Пользовательские Токены? Вот вам ссылочка на страницу документации про эти самые токены: [Пользовательские Токены](/ru/users/tokens.md)

***

# Туториал: «Авторизация пользователя»

> Мини-туториал про то, как именно произвести авторизацию.

Тут вы сможете узнать про то, как именно вы можете "попросить" вашего пользователя авторизоваться через наши сервисы. Но давайте сначало посмотрим на то, *что вам именно пригодится*.

#### 1) Что вам пригодится?

Для того, что бы иметь возможность производить авторизацию вам понадобится:

* Wavees Аккаунт *(хотя бы один)*
* Доступ к интернету.

И да-да, это всё что нам понадобится! Смотрите что мы сделаем дальше!

#### 2) Регистрация приложения в Wavees Developers

Для всех наших простых сервисов для разработчиков мы придумали не менее простой сайт! Там всё очень банально, даже сам дизайн ~сосёт~ очень простой! И так, для того, что бы зарегистрировать ваше приложение вам нужно перейти по данной ссылке:

[Зарегистрировать приложение](https://developer.wavees.co.vu/panel/projects/create?return=authentication/configuration)

После того, как вы зарегистрируйте приложение - переходите обратно сюда! Дальше мы расскажем как именно произвести авторизацию, и что мы получим по итогу.

### 3) Авторизация пользователя

А вот и настало время авторизировать нашего пользователя! После успешной авторизации пользователя мы, как разработчики, получим ограниченный доступ к его аккаунт, и сможем им манипулировать!

?> Если вы хотите узнать больше про то, что именно разработчик может делать с аккаунтом пользователя - прочитайте эту статью: [Пользовательские Права](/ru/users/permissions.md)