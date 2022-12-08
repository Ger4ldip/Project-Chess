# ChVsS

2022 
10-3 Павлов И.Г. , Коровин М.М.
10-4 Тьебо А.Е.
Python, C#;
Приложение собирается работать с сайтом https://lichess.org/

### Описание
Приложение позволяет подключить собственного бота к сайту Lichess.org путем изменения содержимого файла config.yml.
Бот поддерживает как стороних ботов (умеющих передовать свои ходы через uci/xml протоколы) так и собственноручно сделанных, через изменение параметра "protocol" 
на homemade. Так же для подключения аккаунта оболочка использует токен, который можно получить, создав аккаунт, и получив на него bot - права.

### Картинки =)

![prntscrn1](https://user-images.githubusercontent.com/113096503/202991638-e31b8883-b6fe-4fe4-9c52-2b7c15b480d7.png)
![prntscrn](https://user-images.githubusercontent.com/113096503/202991644-03cde915-ba2f-4502-b265-246a80410b06.png)
![image](https://user-images.githubusercontent.com/113096503/205003656-4f3fae67-8733-4493-9c73-7656c7e741a2.png)

### План Работы

Подключение оболочки (25 часов)
- [x] - установить рабочий прототип
- [x] - установить Anaconda для работы с оболочкой
- [x] - подключить оболочку к аккаунту
- [x] - сыграть партию ботом, совешающим случайные ходы
- [x] - сыграть партию open-source ботом Stockfish

Написать бота (60 часов)
- [x] - установить библеотеку keras для python
- [x] - подключить модуль uci
- [x] - добавить uci в homemade оболочку
- [ ] - реализовать работу ходов на lichess.org
- [x] - разработать структуру нейронной сети, способной играть в шахматы
- [ ] - написать прототип движка на основе полученных знаний
- [ ] - подключенить Data-set'ы к нейронной сети
- [ ] - сыграть игру с движком на нейронной сети
- [ ] - разработать книгу дебютной теории
- [ ] - разработать алгоритм для исполнения дебютной теории
- [ ] - разработать алогоритм для постановки мата-в-N-ходов
- [ ] - объеденить все в рабочую систему

### оболочка 
от Shali-Choksi (https://github.com/ShailChoksi/lichess-bot)

### Наш FAN движок
https://datalore.jetbrains.com/notebook/zv3h4nG3nlpHDDNvqvbJeh/SA4UiAYBSKgRGfwC6w3i6l/
