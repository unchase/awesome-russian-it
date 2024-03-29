## CONTRIBUTING

Спасибо за ваш интерес и решение принять участие в улучшении этого проекта. Уверен, что силами community мы сможем расширить базу русскоязычных ресурсов, связанных с ИТ, чтобы каждый мог найти в ней что-то полезное для себя!

## Шаги

- [ ] Сделайте *Fork & Clone* проекта.
- [ ] Отредактируйте соответствующий изменениям файл `README.md` (для мероприятий и блогов), или `YouTube.md` (для youtube-каналов) или `Podcasts.md` (для подкастов), добавив новый контент.
* Вы можете добавить новый раздел, если его нет, но он должен соответствовать тематике родительского раздела и размещаться в алфавитном порядке, как это сделано сейчас.
* **Прежде чем добавлять новый контент, проверьте, нет ли его уже в соответствующем файле**!
* Всегда проверяйте пунктуацию и грамматику.
- [ ] Убедитесь, что ваш редактор не оставляет пустые пробелы в местах, где их не должно быть.

---

- [ ] В файле `Podcasts.md` при добавлении нового **подкаста** разместите следующий шаблон таблицы (скопируйте из `CONTRIBUTING.md` в редакторе) для её дальнейшего заполнения в соответствующем разделе в алфавитном порядке по названию подкаста:

|Название         |[]()|
|:----------------|:--------------------------------------|
|**Логотип**      |<span itunes-id="" class="itunes-img"><img height=100 width=100 src=""></img></span>|
|**Ссылки**       |[![Apple Podcasts](img/favicons/podcasts.apple.com.png)]() • [![Google Podcasts](img/favicons/podcasts.google.com.png)]() • [![Podfm](img/favicons/podfm.ru.png)]() • [![Player](img/favicons/player.fm.png)]() • [![Castbox](img/favicons/castbox.fm.png)]() • [![SoundStream](img/favicons/soundstream.media.png)]() • [![YouTube](img/favicons/youtube.com.png)]() • [![VK](img/favicons/vk.com.png)]() • [![Twitter](img/favicons/twitter.com.png)]() • [![Facebook](img/favicons/facebook.com.png)]() • [![Telegram](img/favicons/t.me.png)]() • [![Instagram](img/favicons/instagram.com.png)]() • [![Яндекс Музыка](img/favicons/music.yandex.ru.png)]() • [![RSS](img/favicons/rss.png)]()|
|**Описание**     ||
|**Ведущие**      ||
|**Регулярность** ||
|**Длительность** ||
|**Количество эпизодов<br>(Apple Podcasts)**|<span itunes-id="" class="episodes" hashtag=""></span>|
|**Релиз последнего эпизода<br>(Apple Podcasts)**|<span itunes-id="" class="release-date"></span>|

- [ ] Добавьте основные детали подкаста, такие как **`Название`** подкаста; **`Ссылки`**, которые с ним связаны; **`Описание`** подкаста; данные о **`Ведущих`**, которые ведут этот подкаст; **`Регулярность`** выхода каждого следующего выпуска подкаста; **`Длительность`** выпусков подкаста.
- [ ] Добавьте дополнительные детали подкаста, такие как **`Логотип`**, **`Количество эпизодов (Apple Podcasts)`** подкаста; **`Релиз последнего эпизода (Apple Podcasts)`** подкаста. Здесь во всех `<span>` атрибут **id** необходимо заполнить идентификатором подкаста в **Apple Podcasts** (например, *1065445951*, то есть без *id* в начале), атрибут **hashtag** - хэштегом, соответствующим подкасту. Эта информация будет использоваться для автоматического ежедневного обновления данных по подкастам. 
* **`Регулярность`** выхода каждого следующего выпуска подкаста можно указывать следующим образом: `Время от времени`, `Один раз в месяц`, `Несколько раз в неделю`, `Еженедельно`, `Ежемесячно`, `<X> раз в месяц`, `Не выпускается` (подкасты с такой регулярностью лучше добавлять в исключительных случаях, например, если в них обсуждаются ещё актуальные темы).
* **`Длительность`** каждого подкаста можно указывать как интервалом (например, `40-60 минут`), так и приблизительным средним временем (например, `~60 минут`).
- [ ] В шаблоне таблицы в 1-ой строке укажите **`Название`** подкаста в виде ссылки, если у него есть свой сайт, иначе - просто текстом.
- [ ] В шаблоне таблицы во 2-ой строке, где должны быть размещены связанные с подкастом ссылки, поместите ссылки, разделённые символом ` • ` в следующем виде:

```
 • [![<имя_для_иконки>](img/favicons/<png_файл_иконки>)](<ссылка>)
```

- [ ] При добавление новых ресурсов (мест размещения подкастов) добавьте отсутствующий *favicon*, получив и сохранив его из браузера с помощью сервиса:

```
http://favicon.yandex.net/favicon/<ссылка_на_ресурс>
```

- [ ] Удалите из шаблона таблицы ссылки на те ресурсы, для которых данные не были добавлены.
- [ ] В шаблоне таблицы в 3-ей строке укажите краткое описание подкаста, раскрывающее его суть, или то, которое указано на официальном сайте (ресурсе) подкаста.
- [ ] В шаблоне таблицы в 4-ой строке укажите ведущих подкаста и ссылки на другие их ресурсы в виде иконок, так же как и во 2-ой строке шаблона таблицы, но без символа ` • ` между ними (аналогично существующим записям). Каждый следующий ведущий отделяется от предыдущего тегом `<br>`.
- [ ] Если автор подкаста уже встречался в другом подкасте, то скопируйте его данные, обновив их во всех местах.

---

* В файле `README.md` при добавлении **Блога** необходимо придерживаться тех же правил, что и для **Подкастов**. В качестве шаблона заполняемой таблицы можно взять:

|Название|Описание|Автор/Создатель/Ссылки|
|:-------|:-------|:---------------------|
|**[]()**<br>[![RSS](img/favicons/rss.png)]()||<Имя_Фамилия_или_никнейм> [![MVP](img/favicons/mvp.microsoft.com.png)]() [![GitHub](img/favicons/github.com.png)]() [![Habr](img/favicons/habr.com.png)]() [![Medium](img/favicons/medium.com.png)]() [![dev.to](img/favicons/dev.to.png)]() [![YouTube](img/favicons/youtube.com.png)]()|

---

В файле `YouTube.md` при добавлении нового **YouTube-канала** необходимо размещать их в соответствующей категории в алфавитном порядке по названию канала, а также в качестве шаблона заполняемой таблицы использовать:

|Название|Описание|Всего видео|Подписчиков|Дата последнего видео|
|:------:|:-------|:---------:|:---------:|:-------------------:|
|<a href=""><img width="30" src=""></a><br>[]()||<span id="" class="youtube-count" hashtag=""></span>|<span id="" class="youtube-subscribers"></span>|<span id="" class="last-video-date"></span>|

*Во все `<span>` в качестве id необходимо подставить идентификатор YouTube-канала или идентификатор пользователя YouTube. В атрибут hashtag необходимо подставить хэш-тег, который будет отображаться в telegram-канале.* 
Эта информация будет использоваться для автоматического ежедневного обновления данных по YouTube-каналам.

---

В файле `README.md` при добавлении **Мероприятий** в таблицу придерживайтесь стиля, который уже используется в этом файле (по аналогии).

В качестве шаблона заполняемой таблицы можно взять:

|Название|Описание|Места проведения мероприятий|Связанные ссылки|
|:------:|:-------|:--------------------------:|:--------------:|
|[![](img/favicons/)]()<br>[]()|||[![Twitter](img/favicons/twitter.com.png)]() [![VK](img/favicons/vk.com.png)]() [![Facebook](img/favicons/facebook.com.png)]() [![YouTube](img/favicons/youtube.com.png)]() [![Telegram](img/favicons/t.me.png)]() [![Instagram](img/favicons/instagram.com.png)]() [![LinkedIn](img/favicons/linkedin.cn.png)]()|

---

- [ ] Отправьте *Pull-Request*.
- [ ] Ожидайте подтверждение и слияние или замечания по *Pull-Request'у*.