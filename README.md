# CurrencyConverter – Мультивалютный Конвертер
[![Codacy Badge](https://app.codacy.com/project/badge/Grade/a09523c1ea8948978858be2d10fbe7fb)](https://www.codacy.com/manual/Lesterrry/CurrencyConverter?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=Lesterrry/CurrencyConverter&amp;utm_campaign=Badge_Grade)
- Выполнены все 4 этапа конкурса
- Курсы валют автоматически обновляются при каждом запуске приложения и при нажатии на соответсвующую кнопку
- Интерфейс адаптивен под любые размер и ориентацию экрана, тему
- Дополнительно добавлен виджет, отслеживающий курс рубля в реальном времени
### Пояснения
Переключение между нижней и верхней валютой, значение которой меняется интерфейсом PickerView, осуществляется нажатием кнопки со значком валюты.
Переключившись, можно выбирать вводимую валюту, и валюту выходного значения. Доступны дробные значения.
Редактирование текста по умолчанию предусмотрено для верхнего левого текстового поля, но возможен также ввод в нижнее правое текстовое поле, в таком случае конверсия произойдет реверсивно.
Выбрать совпадающие валюты на ввод и на выходное значение невозможно.
При отсутствии рабочего подключения к сети интерфейс продемонстрирует значок, сообщающий об ошибке.
### Примечания
- Необходимо иметь ввиду, что предложенный на странице с описанием задания к конкурсу API сервис 'https://exchangeratesapi.io' по неизвестным причинам задерживает обновление курсов валют. На 31.05.2020 запрос `https://api.exchangeratesapi.io/latest?symbols=EUR,USD&base=RUB` возвращает данные, актуальные на 29.05.2020. Для исправления этой проблемы был использован альтернативный API сервис с квотой 2000 запросов/день.
- В случае проверки работоспособности приложения в симуляторе или на внешнем устройстве дополнительный виджет может быть недоступен на вкладке виджетов, для оценки его работоспособности рекомендуется удержать иконку приложения, в таком случае виджет будет показан в любом случае.
### Превью
| Виджет |
| ------ |
| ![screenshot 1](https://github.com/Lesterrry/CurrencyConverter/blob/master/Overview/IMG_708C6A264A85-1.jpeg)|

| iPhone 4S - Книжно | iPhone 11 - Книжно + Dark Mode |
| :------: | :------: |
| ![screenshot 2](https://github.com/Lesterrry/CurrencyConverter/blob/master/Overview/Снимок%20экрана%202020-06-03%20в%2019.58.03.png) | ![screenshot 3](https://github.com/Lesterrry/CurrencyConverter/blob/master/Overview/Снимок%20экрана%202020-06-03%20в%2019.58.30.png) |
| iPhone 4S - Альбомно | iPhone 8 Plus - Альбомно |
| ![screenshot 4](https://github.com/Lesterrry/CurrencyConverter/blob/master/Overview/Снимок%20экрана%202020-06-03%20в%2019.56.43.png) | ![screenshot 5](https://github.com/Lesterrry/CurrencyConverter/blob/master/Overview/Снимок%20экрана%202020-06-03%20в%2019.57.32.png) |
