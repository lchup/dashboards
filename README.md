
## Описание данных
**feed_actions  - Cодержит информацию о всех пользователях соц.сети и их действия в ленте новостей**
|Field name	| Overview|
|-:|:-|
|action       |Действие пользователя (лайк или просмотр)|
|age	      |Возраст пользователя (в профиле)|
|city	      |Город пользователя (в профиле)  |
|country	  |Страна пользователя (в профиле) |
|exp_group	|Экспериментальная группа: некоторая зашифрованная категория|
|gender	    |Пол пользователя|
|os	        |Операционная система устройства, с которого происходит пользование соц.сетью|
|post_id    |Уникальный идентификатор поста|
|source	    |Пришел ли пользователь в приложение с органического трафика или с рекламы|
|time       |Двтв. время|
|user_id	  |Уникальный идентификатор пользователя|

**message_actions  - Cодержит информацию о всех пользователях соц.сети и их действия в мессенджере**
|Field name	| Overview|
|-:|:-|
|age	      |Возраст пользователя (в профиле)|
|city	      |Город пользователя (в профиле)  |
|country	  |Страна пользователя (в профиле) |
|exp_group	|Экспериментальная группа: некоторая зашифрованная категория|
|gender	    |Пол пользователя|
|os	        |Операционная система устройства, с которого происходит пользование соц.сетью|
|receiver_id    |Уникальный идентификатор пользователя, которому отправлено сообщения|
|source	    |Пришел ли пользователь в приложение с органического трафика или с рекламы|
|time       |Двтв. время|
|user_id	  |Уникальный идентификатор пользователя|



# Базовые дашборды

## Лента новостей - ретроперспективные данные

<image src="/img/1.gif" alt="">

## Лента новостей - оперативные данные

<image src="/img/2.gif" alt="">

## Взаимодействие двух сервисов - ленты новостей и месседжера

<image src="/img/3.gif" alt="">

## Анализ продуктовых метрик
### 1.
Маркетологи запустили массивную рекламную кампанию, 
в результате в приложение пришло довольно много новых пользователей.
Необходимо изучить, что стало с рекламными пользователями в дальнейшем, 
как часто они продолжают пользоваться приложением?

<image src="/img/4.jpg" alt="">

### 2. 
Мы наблюдаем внезапное падение активной аудитории! Нужно разобраться, какие пользователи не смогли воспользоваться лентой новостей, что их объединяет?  

<image src="/img/5.jpg" alt="">

На графиках DAU наблюдается резкое падение активных пользователей 10 декабря. Причем проблема наблюдается только для старых пользователей. Далее сследуем более детально.

<image src="/img/6.jpg" alt="">
<image src="/img/7.jpg" alt="">