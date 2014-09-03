rhetological-fallacies-Russian
==============================
About
-----
 Sources for Russian translation of [Rhetological Fallacies infographics](http://www.informationisbeautiful.net/visualizations/rhetological-fallacies/).
 
 Исходные файлы русского перевода _ритологических_ псевдоаргументов. (Ошибок, заблуждений, софизмов, паралогизмов, уловок, извращений --- называйте как хотите).
Translators
-----------
* Alina Gorbatova
* Yuri Baranov
* Aleksandr Popov

Contributors are welcome!

Как помочь с переводом
----------------------

См. также раздел "Текстовые версии" ниже.

Для помощи по доработке перевода не нужны навыки работы с git или github-клиентом. Достаточно зарегистрироваться
на github.

Все проблемы с переводом категоризованы следующими хэштегами ( в порядке убывания приоритетности)

1. Нет/неудовлетворительный перевод названия -- [`#title`](https://github.com/ub/rhetological-fallacies-Russian/labels/title)
2. Нет перевода описания/примера -- [`#descr`](https://github.com/ub/rhetological-fallacies-Russian/labels/descr)
3. Мета:  сравнение псевдоаргументов, исключение из игры из-за трудноотличимости -- [`#meta`](https://github.com/ub/rhetological-fallacies-Russian/labels/meta)
4. Неудачный пример в переводе -- [`#badexample`](https://github.com/ub/rhetological-fallacies-Russian/labels/badexample)
5. Ошибка/неточность/неудачный пример в оригинале -- [`#orig`](https://github.com/ub/rhetological-fallacies-Russian/labels/orig)
6. Требуется стилистическая правка русского текста -- [`#refine`](https://github.com/ub/rhetological-fallacies-Russian/labels/refine)
7. Неоригинальный пример в переводе -- [`#nonliteral`](https://github.com/ub/rhetological-fallacies-Russian/labels/nonliteral)


0. Зарегистрироваться на github.com, если еще не
1. Выбрать категорию по хэштегу, посмотреть  проблемы в этой категории. В категории `#meta` остаются открытые
философские/терминологические вопросы -- по ним можно высказать дискуссионное мнение
2. Выбрать незакрытую проблему и посмотреть текущий материал в файле
[`translation.txt`](https://github.com/ub/rhetological-fallacies-Russian/blob/master/text/translation.txt)
3. Предложить свой вариант перевода или высказать свое мнение в комментарии к теме

Полный список проблем с переводами fallacies перечислен в разделе [issues](https://github.com/ub/rhetological-fallacies-Russian/issues)


Текстовые версии
----------------

Те, кому сложно или утомительно использовать GIMP, могут поучаствовать в редактировании/доработке переводов самих текстов

* `text/translation.txt` -- актуальный вариант переводов определений и примеров
* `text/annotated-translation-table.md` -- примечания к спорным моментам перевода и/или использования в игре. Переводы
  в этом файле необязательно в последней редакции, они даны чисто для справки. Если вам бросилась в глаза какая-то
  неточность, проверьте, присутствует ли она в файле `translation.txt`.


Структура графического файла
----------------------------

В русском переводе используется шрифт [Gillius ADF No 2](http://arkandis.tuxfamily.org/adffonts.html) --- бесплатный шрифт, наиболее похожий на Adelle Sans, использованный в оригинале.

Формат `.xcf`читается и пишется редактором GIMP. Если вы привыкли работать в Photoshop'е, попробуйте установить [Gimpshop](http://www.gimpshop.com/downloads).

Слои в файле `rhetological-fallacies.xcf` идут снизу вверх. 

### Названия слоев
#### Три шаблона масок
* `page1 mask all text template`
* `page2 mask all text template`
* `page3 mask all text template`

Эти слои в самом низу и не отображаются. Их не надо трогать, а использовать для восстановления масок, скрывающий оригинальный текст

#### Оригинальная инфографика с английским текстом
* `page1`
* `page2`
* `page3`

Каждая страница умещается на листе A4.

#### Актуальные маски
* `page1  mask some text`
* `page2  mask some text`
* `page3  mask some text`

Скрывают английский текст. Эти слои можно модифицировать. Во время редактирования удобно эти слои делать полупрозрачными. 

Пока не переведены описания, можно с помощью ластика делать в масках них дырки и показать английский вариант описания --- лучше, чем ничего. Впоследствии можно копировать куски шаблонов масок внизу, чтобы залатать проделанные ранее дырки.

#### Разделители
* `{EMPTY LAYER}`
* `2------------3`
* `1------------2`

Полностью прозрачные пустые слои, служат для визуального разделения в списке слоев

#### Много слоев по названию fallacies
Текстовые слои, которые можно редактировать (и, таким образом, работать над переводом). Порядок: сверху вниз левая колонка страницы, потом правая колонка, потом пустой слой-разделитель.

Чего не хватает
----------------

 1. Нет перевода псевдоаргументов, помеченных в списке слоев вопросом (?)
 2. Нет перевода некоторых описаний и примеров.
 3. Почти нигде нет дырок для того, чтобы были видны описания на английском, пока не готов русский вариант.


 
Acknowledgments and attribution
-------------------------------
 Rhetological fallacies Russian translation is derived from Rhetological fallacies infograhics published under [CC BY-NC 3.0](http://creativecommons.org/licenses/by-nc/3.0/) license by  David McCandless &copy; 2013
 
 
License
-------
*Creative Commons Attribution-NonCommercial 3.0*
See [LICENSE](./LICENSE) file.




&copy; 2014 Alina Gorbatova, Yuri Baranov, Russian translation
 