# CurrencyConverter – Мультивалютный Конвертер
[![Codacy Badge](https://app.codacy.com/project/badge/Grade/a09523c1ea8948978858be2d10fbe7fb)](https://www.codacy.com/manual/Lesterrry/CurrencyConverter?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=Lesterrry/CurrencyConverter&amp;utm_campaign=Badge_Grade)
- Выполнены все 4 этапа конкурса
- Курсы валют автоматически обновляются при каждом запуске приложения
- Интерфейс адаптивен под любые размер ориентацию экрана, тему
- Дополнительно добавлен виджет, отслеживающий курс рубля в реальном времени
### Пояснения
Переключение между нижней и верхней валютой, значение которой меняется интерфейсом PickerView, осуществляется нажатием кнопки со значком валюты.
Переключившись, можно выбирать вводимую валюту, и валюту выходного значения.
Редактирование текста по умолчанию предусмотрено для верхнего левого текстового поля, но возможен также ввод в нижнее правое текстовое поле, в таком случае конверсия произойдет реверсивно.
Выбрать совпадающие валюты на ввод и на выходное значение невозможно.
### Примечание
Предложенный на странице с описанием задания к конкурсу API сервис 'https://exchangeratesapi.io' по неизвестным причинам задерживает обновление курсов валют. На 31.05.2020 запрос `https://api.exchangeratesapi.io/latest?symbols=EUR,USD&base=RUB` возвращает данные, актуальные на 29.05.2020. Для исправления этой проблемы был использован альтернативный API сервис с квотой 2000 запросов/день.
[Данная ветвь](https://github.com/Lesterrry/CurrencyConverter/tree/New-api) использует альтернативный сервис, гарантирующий более свежий курс, но ограничивается квотой, а [ветвь master](https://github.com/Lesterrry/CurrencyConverter) предоставляет старые курсы, гарантируя бесперебойность работы засчет отсутсвия ограничений по запросам. В случае, если клонированная ветвь работает с перебоями или дает ложнае данные, стоит клонировать другую.
