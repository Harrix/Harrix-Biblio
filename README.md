HarrixBiblio
============

Версия 1.12

Файлы библиографических ссылок [**biblio.bib**](../master/biblio.bib) и [**biblioHarrix.bib**](../master/biblioHarrix.bib), которые я использую в своих статьях в формате LaTeX. При этом имеются все материалы в папках [**Materials**](../master/Materials) и [**MaterialsHarrix**](../master/MaterialsHarrix) в виде сканов и иных документов, чтобы вы могли ознакомиться с теми материалами, которые я использовал.

https://github.com/Harrix/HarrixBiblio

Данные распространяются по лицензии [Apache License, Version 2.0](../master/LICENSE.txt).

Не вижу смысла делать в работах ссылки на материалы, которые другие люди не смогут прочитать.

Данные файлы [**biblio.bib**](../master/biblio.bib) и [**biblioHarrix.bib**](../master/biblioHarrix.bib) рекомендуется использовать в составе шаблона документов HarrixLaTeXDocumentTemplate:

https://github.com/Harrix/HarrixLaTeXDocumentTemplate

**Правообладателям**. Если вы увидели что-то, что затрагивает ваши права, то сообщите по контактам ниже, и я удалю материал, который вам не нравится.

Структура проекта на GitHub
-------------------------

- [**biblio.bib**](../master/biblio.bib) - непосредственно сам файл библиографических ссылок.
- [**biblioHarrix.bib**](../master/biblioHarrix.bib) - файл библиографических ссылок с авторскими работами.
- [**Materials**](../master/Materials) - папка с материалами, которые упоминаются в файле библиографических ссылок.
- [**Materials**](../master/Materials) - папка с материалами, которые упоминаются в файле библиографических ссылок авторских работ.
- [**images**](../master/images) - папка с рисунками, для отображения в README.md. Служебная папка - вам не нужна.
- [**utf8gost705u.bst**](../master/utf8gost705u.bst) - файл для оформления по ГОСТ.

Установка и подключение в LaTeX
-------------------------------

Подробно о установке с подробным примером можно прочитать тут http://blog.harrix.org/?p=932.

Подробно прочитать о том, как находить материалы-источники, использованных в моих работах, можно тут http://blog.harrix.org/?p=962.

Для полноценной работы редактированию LaTeX документа вам потребуются программа для компиляции \*.tex документов в \*.pdf. Автор использует для этого связку MiKTeX + TeXstudio + pscyr.

 1. Скопируйте файл [**biblio.bib**](../master/biblio.bib) и [**utf8gost705u.bst**](../master/utf8gost705u.bst) в папку с вашим \*.tex файлом
 
 2. В месте, где хотите сослаться на материал, напишите, например: `\cite{web:makeingsimpleGA}` или `\cite[с. 93]{book:Bolshev1983}`.

 3. В месте, где вы хотите вставить список литературы, напишите:
```
\bibliographystyle{utf8gost705u}  %% стилевой файл для оформления по ГОСТу
\bibliography{biblio}     %% имя библиографической базы (bib-файла)
```

Подробное описание установки и настройки связки MiKTeX + TeXstudio + pscyr можно прочитать в статье http://blog.harrix.org/?p=849.
	
Пример списка литературы
------------------------

![alt text](../master/images/biblio.png "Пример списка литературы")

Использованные технологии
-------------------------

- [LaTeX](http://ru.wikipedia.org/wiki/LaTeX), [BiBTex](http://ru.wikipedia.org/wiki/BibTeX), [MiKTeX](http://miktex.org/), [TeXstudio](http://texstudio.sourceforge.net/).
- [HarrixLaTeXDocumentTemplate](https://github.com/Harrix/HarrixLaTeXDocumentTemplate).

История проекта
---------------

Подробный список изменений в файле [CHANGELOG.md](../master/CHANGELOG.md).

Контакты
--------

Автор: Сергиенко Антон Борисович.

С автором можно связаться по адресу sergienkoanton@mail.ru или  http://vk.com/harrix.

Сайт автора, где публикуются последние новости: http://blog.harrix.org, а проекты располагаются по адресу: http://harrix.org.