HarrixBiblio
============

Версия 1.0

Файл библиографических ссылок **biblio.bib**, которые я использую в своих статьях в формате LaTeX. При этом имеются все материалы в папке Materials в виде сканов и иных документов, чтобы вы могли ознакомиться с теми материалами, которые использовал.

https://github.com/Harrix/HarrixBiblio

Не вижу смысла делать в работах ссылки на материалы, которые другие люди не смогут прочитать.

Данный файл **biblio.bib** рекомендуется использовать в составе шаблона документов HarrixLaTeXDocumentTemplate:

https://github.com/Harrix/HarrixLaTeXDocumentTemplate

**Правообладателям**. Если вы увидели что-то, что затрагивает ваши права, то сообщите по контактам ниже, и я удалю материал, который вам не нравится.

Данные распространяются по лицензии Apache License, Version 2.0.

Структура папок на GitHub
--------------------------

**biblio.bib** - непосредственно сам файл библиографических ссылок.

**Materials** - папка с материалами, которые упоминаются в файле библиографических ссылок.

**utf8gost705u.bst** - файл для оформления по ГОСТ.

Подключение в LaTeX
--------------------------

	\bibliographystyle{utf8gost705u}  %% стилевой файл для оформления по ГОСТу
	\bibliography{biblio}     %% имя библиографической базы (bib-файла)

Как искать материал?
---------------

Вы вдруг натолкнулись на какой-то мой материал или статью (а вдруг?), а там, например, ссылка на книжку **Матвеев М. Г., Свиридов А. С., Алейникова, Н. А. Модели и методы искусственного интеллекта. Применение в экономике: учеб. пособие**. И знаете откуда-то, что у меня можно найти все материалы. 

Итак, заходите на сайт https://github.com/Harrix/HarrixBiblio , скачивайте файл **biblio.bib**.

В нем находите соответствующий код этой книги:

	@BOOK{book:Matveev2008,
	author = "Матвеев, М. Г. and Свиридов, А. С. and Алейникова, Н. А.",
	title = "Модели и методы искусственного интеллекта. Применение в экономике: учеб. пособие",
	address = "М.",
	publisher = "Финансы и статистика",
	year = 2008,
	numpages = 448,
	language = "russian"
	}
	
Книга имеет наименование **book:Matveev2008**. Заходите в папку **PartsOfMaterials** и ищите файл в названием **book_Matveev2008 - Модели и методы искусственного интеллекта. Применение в экономике учеб. пособие**. Всё. Обычно я размещаю не весь материал, а только тот, на который ссылаюсь.

Также можете находить по имени материала, так как имена файлов составные.

А вообще, в первую очередь, файл создан для себя, чтобы иметь актуальную базу библиографических файлов и самому вспомнить - а что я такое там находил.

История проекта
---------------

**[-]** исправление

**[+]** добавление

**[*]** разное

**1.0**

**[*]** Первоначальная версия и 12 ссылок.

Контакты
---------------

С автором можно связаться по адресу sergienkoanton@mail.ru или  http://vk.com/harrix .

Сайт автора, где публикуются последние новости: http://blog.harrix.org, а проекты располагаются по адресу http://harrix.org .