### Предыстория

Вы пришли работать QA-инженером в крутую технологическую компанию “Space Jam”. Ваша команда настолько же молодая, насколько амбициозная и уверенная в себе. Разработчики потягивают свежевыжатый сок, обсуждают криптовалюты и в свободное время пишут на современном стеке интранет для беспилотного космического корабля. В этой итерации запланирована важная часть – сервис регистрации. Команда рада, что у них есть теперь QA-инженер, который найдет все баги, ведь через две недели конец спринта и нужно показывать результат на демо, а корабль нужно было запустить еще в прошлом спринте.


К сожалению, уже на второй день спринта двух разработчиков ангажировали тушить пожары и собирать полимеры в соседнюю команду. К счастью, самый молодой разработчик управился за неделю и сделал сервис авторизации на стеке, который знает лучше всего. Продакт оунер зарегистрировался 3 раза, увидел, что все работает, и больше не имеет замечаний к сервису. В это время вы наконец получили все нужные доступы и готовы внести свою лепту в продукт.

 
После того, как вы открыли [инструкцию к API](API.md), вы почуяли неладное, и принялись думать, как же тестировать это высокотехнологичное чудо. У вас есть [UI](ui.png), доступ к [исходникам проекта](backend.php) и к [базе данных](db.sql). До релиза и демо осталось 4 дня.

### Задание
Пожалуйста:
  * придумайте и напишите (в свободной форме) набор тестовых сценариев, которые проверят сервис авторизации;
  * отметьте случаи, которые точно необходимо тестировать в первую очередь — время ограничено, а ведь еще нужно перепроверить решения, если баги найдутся;
  * расскажите, какие проблемы, кривые и неудачные решения вы видите в текущей реализации сервиса. Если увидите функциональный баг — оформите его, как оформили бы в баг-трекере;
  * расскажите, что можно улучшить в сервисе, и как это сделать;
  * расскажите, на какие случаи стоило бы написать автотесты, и на каких уровнях приложения это стоит сделать.
