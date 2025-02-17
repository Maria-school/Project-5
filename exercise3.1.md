## Что такое язык разметки?

**Язык разметки (markup languages)** - это набор специальных инструкций, называемых тэгами, предназначенных для формирования в документах какой-либо структуры и определения отношений между различными элементами этой структуры. Другими словами разметка показывает, какая часть документа является заголовком, какая подзаголовком, что следует считать именем автора и т. д. Разметка разделяется на стилистическую разметку, структурную и семантическую.
***
**Стилистическая разметка**
Стилистическая разметка отвечает за внешний вид документа. Например, в HTML к данному типу разметки относятся такие теги как \<I> \</I> (курсив), \<B> \</B> (жирный), \<U> \</U> (подчеркивание), \<S> \</S> (перечеркнутый текст) и т.д.

**Структурная разметка**
Структурная разметка задает структуру документа. В HTML за данный тип разметки отвечают, например, теги \<P> \</P> (параграф), \<H?> \</H?> (заглавие), \<DIV> \</DIV> (секция) и т.д.

**Семантическая разметка**
Семантическая разметка информирует о содержании данных. Примерами данного типа разметки являются теги \<TITLE> \</TITLE> (имя документа), \<CODE> \</CODE> (код, используется для листингов кода), \<VAR> \</VAR> (переменная), \<ADDRESS> \</ADDRESS> (адрес автора).
***

## Какие вы знаете языки разметки? Опишите каждый из них.

Языки разметки текста представляют собой определённый набор символов, которые необходимы для его корректного вывода на страницу и придания нужной структуры. Таким образом, документ содержит не только сам текст, но и данные об особенностях его составляющих − названиях разделов и подразделов, маркированных списках, использовании того или иного выделения и т. д. В некоторых случаях использование языка разметки позволяет вводить в тело текста интерактивные элементы или части других документов.

Существует достаточно много языков разметки, однако в силу ряда факторов наиболее популярными из них являются следующие:

- HTML;
- XML;
- XHTML;
- SGML;
- Wiki;
- BBCode;
- Textile;
- Markdown.

**HTML**

Больше всего распространён язык HTML (аббревиатура от английского Hypertext Markup Language − «язык разметки гипертекста»). Он является стандартным для интернет-документов, с его помощью создаются все веб-страницы. Документы, которые содержат в себе специальный код, обрабатываются браузерами и представляются пользователям в удобном интерфейсе. Таким образом, вы получаете возможность просматривать страницы, распечатывать их, использовать для передачи данных на серверы.

Язык HTML открывает такие возможности работы с текстом, как выделение его составляющих полужирным или подчёркнутым шрифтом, курсивом, использование специальных символов, которых нет в предустановленной пунктуации, изменение цвета буквенных и цифровых символов, проведение выравнивания теста, создание отступов, вставка гиперссылки, таблиц. Начало и конец каждого элемента обозначается специальными пометками (тегами), заключёнными в угловые скобки.

**XML**

XML (в переводе с английского eXtensible Markup Language − расширяемый язык разметки). Название связано с тем, что он не имеет зафиксированного формата. Это значит, что пользователи могут создавать собственные теги, которые позволяют глубоко обработать текстовый документ. Как правило, XML используется с целью осуществления описания грамматики других языков, а также обеспечения контроля над правильностью составления документа. Внешне документы HTML и XML очень похожи. Принципиальное отличие − более высокие требования к тегам во втором случае (например, при простановке тега нужно следить за регистром).

Язык XML позволяет проводить обмен данными даже между системами, которые не имеют совместимости. Это обеспечивает удобную работу с разными типами программ.

**XHTML**

XHTML (англ. E x tensible H yper t ext M arkup L anguage -- расширяемый язык разметки гипертекста) -- семейство языков разметки веб-страниц на основе XML, повторяющих и расширяющих возможности HTML 4. Спецификации XHTML 1.0 и XHTML 1.1 являются рекомендациями консорциума Всемирной паутины, однако на данный момент его развитие остановлено с рекомендацией использовать HTML. Новые версии XHTML не выпускаются.

Главное отличие XHTML от HTML заключается в обработке документа. Документы XHTML обрабатываются своим модулем (парсером) аналогично документам XML. В процессе этой обработки ошибки, допущенные разработчиками, не исправляются.

XHTML соответствует спецификации SGML, поскольку XML является её подмножеством. HTML обладает множеством особенностей в процессе обработки и фактически перестал относиться к семейству SGML, что и закреплено в черновике спецификации HTML 5.

**SGML**

SGML (от английского Standard Generalized Markup Language — стандартный общий язык разметки) — метаязык, на котором можно определять язык разметки для документов, являющийся международны стандартом для обеспечения электронного обмена документами между разными системами.

Основные части SGML документа:

1. SGML декларация (описание заголовка файла, содержащего информацию о системе, в которой будет использоваться документ);
2. Document Type Definition (определение типов документа, задающего его структуру, категории лиц, имеющих к нему доступ, иерархию объектов);
3. Содержимое SGML-документа, по крайней мере, должен быть корневой элемент (текстового содержания документа).

SGML является прародителем HTML и XML.

**Wiki**

Wiki-разметка используется для тех веб-страниц, которые могут правиться (дополняться, редактироваться) пользователями. Это позволяет создавать тексты даже тем, кто не разбирается в особенностях HTML-разметки. Безусловно, в этом языке существуют свои правила, но они предельно просты, все изменения можно просмотреть и при необходимости вернуться к первоначальной версии. Благодаря этому исправить ошибки гораздо проще. Администраторы могут ограничить права редактирования размещённых текстов, разрешить проведение манипуляций только определённым пользователям и т. д. Отличительная особенность этой разметки − гипертекстовость (связь документов посредством проставления контекстных гиперссылок).

 
**BBCode**

Этот язык разметки применяется для форматирования сообщений, размещаемых на электронных досках с объявлениями, в блогах, на форумах и т. д. Теги похожи на аналоги из HTML, однако заключаются не в угловые, а в квадратные скобки. Появление такой разметки связано с многочисленными ошибками в отображении информации в чатах, на форумах и т. д. из-за относительной сложности стандартного языка. Особенность BBCode заключается в том, что браузеры не воспринимают его самого по себе. Нужно устанавливать специальную программу, которая разберёт текст и преобразует его в понятный и универсальный HTML-код.

**Textile**

Является одним из наиболее простых языков разметки, похож на предыдущий вид, но имеет несколько большую функциональность. Его основная задача − автоматическое преобразование текста в разметку при сохранении разбивки на абзацы. Язык используется в CMS Textpattern.

**Markdown**

Markdown, или маркдаун, — это язык разметки для текстовых документов. Он позволяет создавать тексты без использования Word и других редакторов. Разметку можно прочитать и воспроизвести в любой системе или браузере.


***
## Что такое теги, атрибуты и элементы в XML?
Основными понятиями любого языка разметки являются **теги, элементы и атрибуты**.

**Тэги и элементы**.

Тэги, или, как их еще называют, управляющие дескрипторы, служат в качестве инструкций для программы, производящей показ содержимого документа на стороне клиента как поступить с содержимым тега. Для того чтобы выделить тег относительно основного содержимого документа используются угловые скобки: тег начинается со знака "меньше" (<) и завершается знаком "больше" (>), внутри которых помещаются название инструкций и их параметры. 

Теги могут быть *парными: открывающими (начальными) и закрывающими (конечными)*. Открывающие теги состоят из знаков «<» и «>» между которыми указывается имя тега, а у закрывающих перед именем дополнительно ставится прямой слэш (/).

 Или *одиночными*. Такие теги добавляют на страницу одиночный объект, и им не нужно для этого заключать в себя какой-то текст. Поэтому их называют одиночными. 

*Элемент* - это тэги в совокупности с их содержанием. Следующая конструкция является примером элемента:

    <I> Это текст выделен курсивом </I>.

Элемент состоит из открывающего тега , содержимого тега (в примере это текст "Это текст, выделен курсивом") и закрывающего тега, правда иногда в HTML, закрывающий тег можно опустить.

**Атрибуты**

Для того чтобы при определении элемента задать какие-либо параметры, уточняющие характеристики данного элемента используются атрибуты.

Атрибуты состоят из пары "название" = "значение", которую можно задавать при определении элемента в начальном тэге. Слева и справа от символа равенства можно оставлять пробелы. Значение атрибута указывается в виде строки, заключенной в одинарные или двойные кавычки.

Любой тэг может иметь атрибут, если этот атрибут определен.

В случае использования атрибута элемент принимает следующую форму:

    <имя_тега атрибут = "значение"> содержимое тега </имя_тега>

Пример:

    <p ALIGN="CENTER"> текст выравнивается по центру </p>

В одном открывающемся теге может содержаться несколько атрибутов, например:

    <FONT SIZE = 7 color = "RED"> Указан размер и цвет текста </FONT>
***

## Что такое XML?

**XML (eXtensible Markup Language — расширяемый язык разметки)** — это язык программирования для создания логической структуры данных, их хранения и передачи в виде, удобном и для компьютера, и для человека. Отличается простотой синтаксиса и универсальностью. XML позволяет описывать документы с помощью тегов, которые можно задавать самостоятельно.
XML - это метаязык. Этот язык используется в качестве средства для описания грамматики других языков и контроля за правильностью составления документов.

XML используется везде, где требуется выделить логическое содержимое документа для обработки. Формат рекомендован Консорциумом Всемирной паутины (W3C), поэтому применяется в API, когда ответ от сервера поступает в виде XML-файлов.

XML позволяет:
- записывать иерархию — «один подчиняется другому»;
- размечать текст по смыслу от важного к второстепенному;
- хранить типовые данные — скрипты, настройки программ, названия чего-либо;
- размечать текст для машинного обучения;
- хранить результаты работы текстовых редакторов.

Основные стандарты XML
Стандарты XML — это расширения, дающие дополнительные возможности при работе с XML-файлами. Вот некоторые из них:

- XPath — для навигации по документам XML;
- XSLT — для преобразования XML-документов в другие форматы (например, в HTML);
- XQuery — для обработки данных в XML-формате и др.;
- AJAX — для изменения содержимого веб-страницы без ее перезагрузки;
- XML DOM — для получения, изменения, добавления или удаления отдельных элементов из XML-файла;
- DTD — для определения списка разрешенных элементов для сущности в XML-файле.

***
## Чем XML отличается от HTML?

XML не является заменой HTML. Они предназначены для решения разных задач: XML решает задачу хранения и транспортировки данных, фокусируясь на том, что такое эти самые данные, HTML же решает задачу отображения данных, фокусируясь на том, как эти данные выглядят. Таким образом, HTML заботится об отображении информации, а XML о транспортировке информации.

- XML - это текстовый язык разметки, который имеет структуру с самоописанием и может эффективно определять другой язык разметки. С другой стороны, HTML является предопределенным языком разметки и имеет ограниченные возможности.
- XML обеспечивает логическое структурирование документа, в то время как структура HTML предопределена, где используются теги «head» и «body».
Когда дело доходит до типа языка HTML не чувствителен к регистру. В отличие от XML чувствителен к регистру.
- HTML был разработан с акцентом на особенности представления данных. В отличие от XML, данные являются специфическими, где хранение и передача данных были первостепенной задачей.
- XML не допускает каких-либо ошибок, если в коде есть ошибки, которые не могут быть проанализированы. И наоборот, в HTML мелкими ошибками можно пренебречь.
- Пробелы в XML используются для конкретного использования, так как XML учитывает каждый отдельный символ. Напротив, HTML может игнорировать пробелы.
- Теги в XML обязательно должны быть закрыты, тогда как в HTML открытый тег также может работать совершенно нормально.
- Вложение в XML должно быть сделано правильно, это имеет большое значение в синтаксисе XML. И наоборот, HTML не заботится о вложенности.


| Сравнительная   таблица |                                                            |                                              |   |   |
|-------------------------|------------------------------------------------------------|----------------------------------------------|---|---|
| Основа для сравнения    | XML                                                        | HTML                                         |   |   |
| Расширяется   до        | расширяемый язык   разметки                                | Язык   гипертекстовой разметки               |   |   |
| основной                | Предоставляет   платформу для определения языков разметки. | HTML - это   предопределенный язык разметки. |   |   |
| структурная             | Информация   gредоставлена                                 | Не содержит   структурной информации         |   |   |
| Тип   языка             | С учетом   регистра                                        | Без учета   регистра                         |   |   |
| Назначение   языка      | Передача   информации                                      | Представление   данных                       |   |   |
| ошибки                  | Не положено                                                | Небольшие ошибки   можно игнорировать.       |   |   |
| Пробелы                 | Может быть   сохранен                                      | Не сохраняет   пробелов.                     |   |   |
| Закрывающие   теги      | Обязательно   использовать закрывающие теги.               | Закрывающие теги   необязательны.            |   |   |

***

## Что такое DTD? Расшифруйте и приведите примеры использования в различных документах.

**DTD (англ. Document Type Definition — определение типа документа)** — аббревиатура для обозначения следующих двух понятий:

1. Схема всего документа или его части (в контексте языка схем DTD).
2. Язык схем DTD (DTD schema language) — компьютерный язык, который используется для записи фактических синтаксических правил метаязыка SGML и расширяемого языка разметки XML. С момента его внедрения другие языки схем для языков разметки, такие как XML Schema и RELAX NG, обзавелись дополнительной функциональностью.

DTD, относительно XML документа, могут быть двух типов: **внешними и внутренними**. Также возможно вXML документе одновременно использовать оба типа DTD.

Для объявления DTD в XML документе используется предложение **DOCTYPE**, которое должно располагаться перед корневым элементом XML документа, а указываемое в нем имя DTD должно совпадать с именем корневого элемента. Предложение DOCTYPE имеет вид:

    <!DOCTYPE имя_dtd  расположение_dtd >,

где: имя_dtd – имя схемы DTD, совпадающее с именем корневого элемента XML документа;

расроложение_dtd – описатель местоположения схемы DTD, вид которого зависит от типа DTD.

**РАЗМЕЩЕНИЕ DTD**

Либо в отдельном файле “*.dtd” указав его имя в кавычках во второй части пролога DOCTYPE, либо включить описание непосредственно во вторую часть пролога, заключив его в квадратные скобки.

    <!DOCTYPE root_element SYSTEM "schema.dtd">

**Синтаксис**  
Основной синтаксис DTD выглядит следующим образом:

    <!DOCTYPE element DTD identifier
    [
     declaration1
    declaration2
    ........
    ]>

**Примеры:**  
 DTD в XML:

    <!DOCTYPE Catalog PUBLIC "abc/Catalog" "http://xyz.abc.org/dtds/catalog.dtd">

DTD в HTML 5

    <!DOCTYPE html>
    <html>
    <head>
    <title>!DOCTYPE</title>
    <meta charset="utf-8">
    </head>
    <body>
    <p>Разум — это Будда, а прекращение умозрительного мышления — это путь. 
    Перестав мыслить понятиями и размышлять о путях существования и небытия, 
    о душе и плоти, о пассивном и активном и о других подобных вещах, 
    начинаешь осознавать, что разум — это Будда, 
    что Будда — это сущность разума, 
    и что разум подобен бесконечности.</p>
    </body> 
    </html>

***
## Из чего состоит HTML-документ?

Базовая структура любого HTML-документа:

    <!DOCTYPE html>
    <html lang="ru">
    <head>
        <meta charset="UTF-8">
        <title>Моя первая страница</title>
    </head>
    <body></body>
    </html>

**DOCTYPE**

Первая конструкция в любом HTML-документе — элемент <!DOCTYPE>. Он не относится к тегам и никаким образом не может отображаться на странице. Его задача — указать браузеру, какой стандарт HTML используется в этом документе. Сейчас это везде стандарт HTML5. Записывается он следующим образом:

    <!DOCTYPE html>

**Парный тег html**

Тег \<html>\</html>  является основой основ. Именно внутри него располагается вся информация. Благодаря этому тегу браузер понимает, где начинается контент, который необходимо обработать как HTML.

Важной частью тега html является наличие атрибута lang. В нем указывается язык, на котором отображается веб-страница. С помощью этого атрибута браузеры могут корректно считать множество специфичных символов, которые присутствуют в разных языках. 

В качестве значения атрибут lang принимает знакомые всем сокращения языков. Для русского — lang="ru", для английского — lang="en", для немецкого — lang="de".

**Парный тег head**

Тег \<head>\</head> служит для хранения служебной информации. Здесь возможны самые разные сочетания тегов, которые подсказывают браузеру название страницы, описание, ключевые слова и так далее. Такая информация называется метаинформацией. В современном вебе она отвечает не только за служебную информацию для браузера, но и активно используется при продвижении сайта. Поисковые системы считывают всю эту информацию и на основе множества алгоритмов определяют место сайта при разных поисковых запросах.

Любые данные, которые указаны внутри тега \<head>, не видны при отображении страницы в браузере. Это значит, что нет необходимости располагать там информацию, которая предназначена для отображения.

**Тело документа**

После тега \<head> в документе указывается парный тег \<body>\</body>, который является «телом» всей страницы. Именно здесь размещается вся информация, которая будет выведена на странице.

В body находится значимое содержимое. Обычно в body выделяют три части: шапка сайта, основное содержимое и подвал. В шапке обычно содержится верхнее меню сайта, за это отвечает тег header. Для содержимого нет определенного тега, но обычно используется section. Для подвала используется footer, там обычно содержатся контактная информация, ссылки на ключевые страницы сайта и копирайт. Теги header и footer должны быть единственными на странице, а section может бесконечно повторяться.

**DOM** — это объектная модель документа, которую браузер создает в памяти компьютера на основании HTML-кода, полученного им от сервера. Иными словами, это представление HTML-документа в виде дерева тегов.

**Как строится DOM-дерево**

Для описания структуры DOM потребуются термины: корневой, родительские и дочерние элементы. Корневой элемент находится в основании всей структуры и не имеет родительского элемента. Дочерние элементы не просто находятся внутри родительских, но и наследуют различные свойства от них.