LaTeX-шаблон для русской кандидатской диссертации и её автореферата.

## Структура
* [dissertation.tex](dissertation.tex): главный файл диссертации.
* **[папка Dissertation](Dissertation/):** Структурированная система файлов с шаблоном диссертации.
  * **папка images:** Папка для размещения файлов изображений, относящихся только к диссертации.
  * [setup.tex](Dissertation/setup.tex): Файл упрощённой настройки оформления диссертации. В нём же настраивается выбор реализации библиографии.
* [synopsis.tex](synopsis.tex): главный файл автореферата диссертации.
* **[папка Synopsis](Synopsis/):** Структурированная система файлов с шаблоном автореферата.
  * **папка images:** Папка для размещения файлов изображений, относящихся только к автореферату диссертации.
  * [setup.tex](Synopsis/setup.tex): Файл упрощённой настройки оформления автореферата. В нём же настраивается выбор реализации библиографии.
* **[папка Presentation](Presentation/):** Шаблон презентации.
* **[папка Documents](Documents/):** Полезные документы (ГОСТ-ы и постановления).
* **[папка PSCyr](PSCyr/):** Пакет PSCyr + инструкции по установке.
* **[папка BibTeX-Styles](BibTeX-Styles/):** Подборка русских стилевых пакетов BibTeX под UTF-8.
* **папка common:** Общие файлы настроек и управления содержанием шаблонов.
  * [characteristic.tex](common/characteristic.tex): Часть общей характеристики работы, повторяющаяся в диссертации и автореферате.
  * [concl.tex](common/concl.tex): Заключение. Является общим для автореферата и диссертации (согласно [ГОСТ Р 7.0.11-2011](Documents/GOST%20R%207.0.11-2011.pdf), пункты 5.3.3 и 9.2.3).
  * [data.tex](common/data.tex): Общие данные (название работы, руководитель, оппоненты, ключевые слова и т. п.).
  * [packages.tex](common/packages.tex) и [styles.tex](common/styles.tex): Общие пакеты и стили оформления автореферата и диссертации.
* **папка biblio:** Файлы с библиографией.
* **папка images:** Общие файлы изображений шаблонов.
* **папка listings:** Общие файлы листингов.

## Благодарности
* Большое спасибо Юлии Мартыновой за [оригинальный вариант шаблона](http://alessia-lano.livejournal.com/4267.html).
* Большое спасибо [dustalov](https://github.com/dustalov), [Lenchik](https://github.com/Lenchik), [tonkonogov](https://github.com/tonkonogov) за значительный вклад и обсуждения.
* Спасибо [storkvist](https://github.com/storkvist), [kshmirko](https://github.com/kshmirko), [ZoomRmc](https://github.com/ZoomRmc), [tonytonov](https://github.com/tonytonov), [Thibak](https://github.com/Thibak), [eximius8](https://github.com/eximius8), [Nizky](https://github.com/Nizky) за полезные правки и замечания.
