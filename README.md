# AI ChatGPT

[![](https://img.shields.io/github/last-commit/Zalexanninev15/ai-for-all.svg)](https://github.com/Zalexanninev15/ai-for-all/commits/main)
[![](https://img.shields.io/github/stars/Zalexanninev15/ai-for-all.svg)](https://github.com/Zalexanninev15/ai-for-all/stargazers)
[![](https://img.shields.io/github/forks/Zalexanninev15/ai-for-all.svg)](https://github.com/Zalexanninev15/ai-for-all/network/members)
[![](https://img.shields.io/github/issues/Zalexanninev15/ai-for-all.svg)](https://github.com/Zalexanninev15/ai-for-all/issues?q=is%3Aopen+is%3Aissue)
[![](https://img.shields.io/github/issues-closed/Zalexanninev15/ai-for-all.svg)](https://github.com/Zalexanninev15/ai-for-all/issues?q=is%3Aissue+is%3Aclosed)
[![](https://img.shields.io/badge/license-GPLv3-ligthgreen.svg)](LICENSE)
[![](https://img.shields.io/badge/Donate-FFDD00.svg?logo=buymeacoffee&logoColor=black)](https://zalexanninev15-donate.pfm.live/)

## Описание
Провайдеры ChatGPT для бесплатного использования, преимущественно без регистрации и с +/- адекватной поддержкой русского языка. Имеется скрипт для получения провайдеров со сторонних источников на GitHub. Сайт сделал для себя, упрощения жизни при отсутвии возможности использования технологии на 3 буквы (\*P\*) и для использования по учёбе. [Подробнее о создании проекта и релиз (Telegram)](https://t.me/Zalexanninev15_News/1172)

## Как использовать?

#### Выбор сайта (инстанты)

- https://zalexanninev15.github.io/AI-ChatGPT
- https://ai.chilledjoke.repl.co - зеркало

#### Описание разделов

1. Альтернативные ресурсы с большим уклоном на разные модели, работу с фото/видео и т.д.
Провайдеров ChatGPT в них немного, а вот других AI инструментов более чем хватает.

<p align="center">
  <img src="/assets/1.png">
</p>

2. Моя личная подборка провайдеров.
Их я составляю вручную и проверяю каждый из них. Главные критерии - доступность и использование без сайтов-прослоек. Некоторых провайдеров беру из сайтов-прослоек, которые хранят провайдеров для отображения, довольно часто, используя элемент ```<frame>```. Таким образом убирается огромная доля сайтов-мошейников (просят денег за то, что бесплатно) и ненужных сайтов-прослоек.

<p align="center">
  <img src="/assets/2.png">
</p>

3. Следом идут провайдеры в Telegram (пока в разработке)

4. Подгружаемая страница с провайдерами с GitHub репозиториев.
Данные для данной таблицы будут обновляться раз в 2 дня. Сама таблица доступна после клика по кнопке "Развернуть список других провайдеров".

#### Python-скрипт

Для того, чтобы получить список провайдеров для сайта с GitHub репозиториев, последняя таблица (4), я за несколько дней написал [скрипт](https://github.com/Zalexanninev15/AI-ChatGPT/blob/main/get_providers.py) для сбора провайдеров с GitHub репозиториев. Его можно просто запустить в терминале. Итогом станет компактный список провайдеров в файле `providers.txt`. Не все провайдеры могут работать.