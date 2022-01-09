# Введение в глубокое обучение и вообще

Добро пожаловать на страничку курса "Введение в глубокое обучение и вообще". 

- Большая часть материалов курса нагло украдена из других курсов. В README к каждой неделе я пытался описывать что и где я спёр
- Материалы для каждого семинара лежат в папках `/week*`
- Курс сделан на Tensorflow 2.0
- Если вы хотите скачать из репозитория конкретную папку, просто вставьте ссылку на неё [в сервис для скачки.](https://minhaskamal.github.io/DownGit/#/home) Ну либо наконец уже [разберитесь с git](https://githowto.com/ru) и сделайте pull. 

> Нашёл на этой страничке ошибку? Нашёл какой-то ультраполезный ресурс? Придумал какое-то интересное задание для семинара? Есть конструктивная критика? Не молчи, заводи issue, делай пулл-реквест и напиши мне на почту filfonul@gmail.com или в Telegram (@Ppilif). 


## Идеология курса 

Показать, что никакого искусственного интеллекта не существует. Нейросетка — это просто ансамбль из регрессий. Дать понять на каком уровне развития сейчас находится эта область машинного обучения и когда ждать нормальный искуственный интеллект, который всех поработит ну или хотябы будет присылать терминаторов.


## План курса

- [__week01_intro__](./week01_intro) От регрессии к нейросети.
- [__week02_backprop__](./week02_backprop) Алгоритм обратного распространения ошибки. 50 оттенков градиентного спуска.
- [__week03_matrix_diff__](./week03_matrix_diff) Матричное диффириенцирование.
- [__week04__]( ) Нейросети - конструктор LEGO.
- [__week05__](./week05_conv_nets) Свёрточные сети.
- [__week06__]( ) Оптимизация и эвристики.
- [__week07__]( ) Современные архитектуры свёрточных сетей. Transfer learning.
- [__week08__]( ) Задачи компьютерного зрения.
- [__week09__]( ) Обучение без учителя.
- [__week10__]( ) Работа с текстами, введение в NLP, идея эмбедингов: w2v.
- [__week11__]( ) Рекурентные нейронные сетки: RNN, LSTM, GRU. Временные ряды.
- [__week12__]( ) Нейросети для текстов: свёрточные сети, рекурентные сети, какими бывают эмбединги (представления слов).
- [__week13__]( ) Seq2seq модели. Механизмы внимания. Автопереводчики. Генерация текстов.
- [__week14__]( ) Разбираемся с трансформерами.
- [__week15__]( ) Генеративные нейронные сети.
- [__week16__]( ) Работа со звуком/видосами/ченить прикольное.



## Домашки и контрольная 

Список домашек: 

1. Основы tensorflow, сбор своих первых нейросетей на tensorflow
2. Собираем нейросеть своими руками
3. Большое задание по работе с картинками
4. Рекурентные сетки и временные ряды 
5. Большое задание по работе с текстами 

В домашних заданиях будет довольно много бонусных баллов. Из-за их наличия вы сможете выбирать те разделы, которые вас больше всего заинтересовали. 


__Предполагаемая дата контрольной:__ 30 марта


## Самый важный раздел 

Итоговая оценка вычисляется по формуле: 

```
Накоп = 0.3 СР + 0.5 ДЗ + 0.2 КР 

Итог = min(10, 0.7 Накоп + 0.3 Экз)
```

- ДЗ - средняя оценка за домашки на python (5 заданий), одна домашка сделанная хуже всего при расчёте средней оценки, не учитывается
- СР - средняя оценка за самостоялки на семинарах (около 12 квизов), две работы, написанные хуже всего, не учитываются
- КР - балл за письменную контрольную работу
- Экз - балл за письменный экзамен

Если накопленная оценка оказалась >= 6, а также за контрольную вы получили оценку >=6, можно забрать себе накопленную оценку как автомат и не сдавать экзамен. 


__Правила сдачи заданий:__ 

За каждый день просрочки после мягкого дедлайна снимается 1 балл. После жёсткого дедлайна работы не принимаются. Даже при опозданиии на одну секунду. Сдавайте работы заранее. 

Есть исключение, и имя ему __Late days policy.__ У каждого студента есть право отложить мягкий дедлайн на 1,2 или 3 дня. Суммарно для откладывания в запасе есть три дня. Можно отодвинуть один дедлайн на три дня, а можно три дедлайна подвинуть на один день. Распоряжаться этими днями студент может как угодно. Жёсткий дедлайн, при этом, не меняется. 

При обнаружении плагиата оценки обнуляются всем, кто был задействован в списывании, а также подаётся докладная записка в учебный офис. При наличии уважительной причины пропущенную проверочную можно написать позднее, а дедлайн по домашнему заданию может быть перенесён. Дедлайн по домашнему заданию переносится на количество дней, равное продолжительности уважительной причины. Решение о том, является ли причина уважительной, принимает исключительно учебный офис. 

Любой из студентов может быть вызван на защиту любого домашнего задания. На защите по тексту работу ему задаётся несколько вопросов. Если студент не отвечает на них, работа обнуляется.

### Книги:

* [Нейронки от Николенко,](https://yadi.sk/i/EIL8nVcLCzR80g) книга, которую всем рекомендую читать в первую очередь.
* [Верховный алгоритм,](https://yadi.sk/i/zYNv-pLMYLZXfQ) книга для рефлексии и мыслях о том, когда же нас поработит искуственный интеллект.
* [Глубокое обучение,](https://yadi.sk/i/NZIdukL2tpufBA) библия нейросеток с ответами на многие вопросы и хорошей математикой.


### Онлайн-курсы:

* [Advanced ML от Яндекса.](https://www.coursera.org/specializations/aml) Это для тех, кто хочет развиваться дальше. В специализации есть разные специфические курсы. Первый из них про нейронки. Код на Tensorflow. Версия библиотеки там пока что старая.

* [Курс нейронок, который читают в ШАД и сколтехе.](https://github.com/yandexdataschool/Practical_DL/tree/master)  Есть варианты кода на разных фреймворках. Есть видео лекций на русском и английском.
* Бесплатный [курс по tf от Google.](https://www.udacity.com/course/intro-to-tensorflow-for-deep-learning--ud187) Короткий. Покрывает весь базовый Keras. Все тетрадки выложены в colab. Внутри есть очень странные интервью.  
* Бесплатный [курс по pytorch от Samsung.](https://stepik.org/course/50352/syllabus)  Состоит из двух частей: CV и NLP. Для тех, кто хочет писать на pytorch.
* [Deep learning на пальцах.](https://dlcourse.ai) Семён из кремниевой долины записывает лекции на youtube. Объясняет и правда на пальцах. Причём сложные вещи. Круто смотреть его стримы в метро, пока куда-то едешь. 


## Лицензия

Весь контент, созданный для этого курса распространяются на правах лицензии [MIT License](https://github.com/hse-econ-data-science/dap_2020_fall/blob/master/LICENSE) Материалы публикуются как общественное достояние.

<img align="center" src="http://www.roundcrisis.com/presentations/ndc-oslo/images/legos.jpg" height="250" width="500">
<br>
<br>



