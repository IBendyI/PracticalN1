# Шпоргалка для бро
Сейчас я бы хотел поведовать тебе о Git.
----
## Начнём с того, что зачем вообще он нужен.
Git — это программа, такая же, как Zoom, MS Office или Photoshop, а значит, она требует установки и предварительной настройки. Но, в отличие от перечисленных программ, у Git нет привычного графического интерфейса, и работа с этим инструментом происходит иначе.
Если кратко то GIT инструмент для сохранений версий твоего кода, инструмент который позволит тебе писать код с коллегами, а также синхронизировать их код с твоим(Например, если вы оба начали писать один и тот же код, но у него нету твоей части кода, а у тебя нету его, то Git всё исправит).
----
## В кратце я всё разъяснил, перейдём к консольным командам.
1. **pwd** - печатает директорию в которой ты сейчас находишься
2. **cd** - меняет директорию
3. **mkdir** - создаёт директорию
4. **touch** - создаёт файл(расширение задаёшь сам через точку)
5. **rm** - удаляет файл
6. **rmdir** - удаляет директорию
7. **cat** - напечатать наличие файла
8. **ls** - показывает информацию о директории в который вы нахоитесь(если добавить флаг -a то также будет показаны скрытые директории)

В целом это основные команды для создания, переключения, просмотра файлов и директорий 
----
#### Теперь расмотриим команды для создания репризиторий(проще говоря хранилище версий кода, точное определение можно узнать на курсе)
1. git init `папка` - превращает папку в репризиорий
2. rm -rf "репризиторий" - превращает репризиторий обратно в папку 
3. git add `файл` - подготавливает файл к сохранению в репризиторий
4. git commit -m "Сведенья о изменениях в вресии" - команда сохраняет вресию в репризиторий. Важно в поле "Сведенья о изменениях в вресии" писать полезную информацию, а не какой-ниюудь "Фиксы"
5. git log - просмотреть версии сохранёные  врепризитории

##### И пока что на гит логе я остановлюсь, ведь в нём есть много разной интересной информации, например там можно увидеть дату создания версии, её автора и какой-то непонятный набор символов типа ff31b1aa8d0a32719bdb94beb518a31e255a3778, сейчас о нём и пойдёт речь.**
ХЕШ - Основной идефикатор коммита. Можно сказать это вся инфа о версии в зашифрованном виде.

~~Скажи, что теперь ты знаешь больше и тут и вправду много полезной информации :D**~~

Вернёмся к git log в самой последний версии прокта можно увидеть HEAD -> master(или main), ~~очевидную вещь скажу,~~ но такая штука пишется только на последней версии и называется она HEAD(Твоя последняя версия)

На этом с git всё, остальное можно узнать на курсе [Основы работы с гит](https://practicum.yandex.ru/profile/git-basics/?from=catalog) на яндекс практикум 
----
##### Хотя может тебе интересно как я сделал такой красивый текст, с линиями и всей остальной фигнёй, такая штука называется markdown(не в обиду Маркам), специальный язык разметки, который с помощью некоторых символов может сделать твой текст оригинальным.
Вот подробней:
# H1 — заголовок первого уровня, самый большой
## H2 — заголовок второго уровня, поменьше
### H3
#### H4
##### H5
###### H6 — заголовок шестого уровня, самый маленький 

Текст над чертой

---

Текст под чертой 

Текст до переноса⋅⋅  
Текст после переноса <br>
Текст после второго переноса 

Курсив — это *звёздочки* или _подчёркивания_. 

Полужирный шрифт — двойные **звёздочки** или двойные __подчёркивания__.
Можно совместить выделение **звёздочки и _подчёркивания_**. 

~~Зачёркнутый текст.~~ 

1. Первый пункт нумерованного списка.
2. Второй пункт. 

* первый пункт ненумерованного списка;
* второй пункт ненумерованного списка

- первый пункт ненумерованного списка;
- второй пункт ненумерованного списка 

[Яндекс](https://www.yandex.ru "Я Yandex!") 

```bash
ls - la
```
```html
<h1>А я просто текст</h1>
``` 

----

Что бы просмотреть какие символы используется, рекомендуется скачать файл и открыть в блокноте

----

## На этом всё
надеюсь я тебе дал много полезной информации мой друг и начать работу с гит тебе бдует намного проще теперь.
# Удачи!