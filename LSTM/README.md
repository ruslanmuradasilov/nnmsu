Приложение к лекции 13. Рекуррентная нейронная сеть с долгой краткосрочной памятью (LSTM) 
=====================

Даны текстовые отзывы зрителей фильма «Звездные войны» с сайта Twitter.com (*). 
Рассматривается LSTM сеть для определения эмоционального окраса отзыва. 

В качестве целевого признака используется индекс степени удовлетворенности зрителя, принимающий значения [0,1], где 1 - очень понравилось, 0 - очень не понравилось. 

Файлы:
- lstm_new.py  - код LSTM сети
- encoder.py - кодировщик данных на основе фреймворка Stemmer
- data - наборы обработанных данных

***
Источники: 
- (*)  https://habr.com/ru/company/dca/blog/274027/
- Stemmer: http://snowball.tartarus.org/algorithms/russian/stemmer.html
