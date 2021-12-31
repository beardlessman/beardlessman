---
title: 'ТЕСТОВЫЕ ЗАДАНИЯ'
date: 2021-08-31
layout: layouts/post.njk
---
ТЕСТОВЫЕ ЗАДАНИЯ

Никто не любит тестовые задания. Я научился делать тестовые так чтоб их приняли. Пилю тред про мелочи которые повысят вероятность прохождения тестового задания. 

 1. Помни о том, что тот кто будет проверять тестовое будет это делать на бегу и вряд ли сможет сделать это хорошо. Дедлайны горят, прод горит, митинги кучами. А тут ещё тестовое проверять. Ни у кого нет времени два дня разбираться с твоим кодом.
 2. Проверяющий скорее всего будет смотреть на формальные признаки. Сам код будет прочитан по диагонали и если там нет цепляющих взгляд вещей то он пройдет “ревью”.
 3. Сделать тестовое задание, которое примут, сложнее чем делать работу. Нужно очень много сделать всякой мелочевки чтоб показать что ты норм.
 4. Первая мелочь - не пиши весь код в одном файле, даже если кода 50 строк. Проверяющий доебется что не умеешь декомпозировать и в прод будешь писать так же в одном файле. 
 5. Вторая мелочь - обязательно юнит тесты, даже если нечего тестировать. Нужно просто наличие - два-три теста которые проверяют ничего лучше чем их полное отсутствие. (Как писать юниты для фронта я не знаю, поделитесь в комментах)
 6. Третья - подробное ридми. Просто код без описания никому не нужен, скорее всего чел забьет его вообще смотреть. Напиши что ты сделал, для чего, как запускать, как запустить тесты, как правильно посмотреть работоспособность. Какими версиями собирать и тд. Представь что делаешь опенсорс проект. 
 7. Хорошо если ты заморочишься и сделаешь мейкфайл, а еще докерфайл. Делов на 15 минут а сразу бонусных очков заработаешь. 
 8. Если можешь - лучше пиши на английском - ридми, коммит месседжи, комментарии к коду. 
 9. Добавь файл с версией, пусть будет вечный 0.1.0-SNAPSHOT но проверяющий заметит что ты подумал о версии. Совсем мелочь на 10 секунд работы, а очень бросается в глаза. 
 10. Старайся форматировать код читабельно, чтоб он выглядел красиво. Не комментируй каждую строку. Код должен выглядеть прилично если его смотреть по диагонали. Однобуквенные переменные оставь для прода, в тестовом задании их писать нельзя. (Ну счетчики i,j можно)
 11. Если просят задание в виде репозитории отформатируй git log. Он должен выглядеть прилично и показывать ход мысли. Даже если ты писал за один присест. Покажи что ты умеешь атомарно вносить изменения а не одним куском. Ну и автора не забудь поправить. Фамилия имя почта вот это все. 
 12. Вот тут можно посмотреть как делал тестовое я. Кода меньше чем описания и обвязки в виде скриптов и описаний. https://github.com/the2pizza/authorizer
 13. Главный принцип - тестовое задание должно выглядеть как настоящий проект, даже если там делов на час. Это все не гарантия стопроцентного прохождения, но сильно сильно улучшит мнение проверяющего.

