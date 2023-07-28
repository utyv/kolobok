# kolobok
## Слоговая раскладка клавиатуры "КОЛОБОК"
___

## чт.о   так.ое   сл.о г.о в.ая   рас.* кл.а дк.а   к.о л.о б.ок?

Раскладка КОЛОБОК предлагает метод ввода текстов на русском языке с использованием [ортолинейной сплит-клавиатуры](https://habr.com/ru/companies/dododev/articles/511664/). В общем случае ввод осуществляется одновременным нажатием нескольких клавиш (аккордом), при этом за одно нажатие (удар) может быть введено несколько букв. В широком смысле раскладка является [теорией стенотайпинга](https://www.openstenoproject.org/plover/) (в стенотайпинге подобные системы ввода текста принято называть "теориями").

Для русского языка существует только одна теория, поддерживающая компьютерную расшифровку ввода - за авторством Priscilla E. Trillo. Создание альтернативной системы мотивировано желанием упростить освоение аккордового ввода. В системе КОЛОБОК текст вводится более короткими порциями, уделяется большое внимание принципам  разделения текста на порции, с учетом фонетики и морфологии русского языка. В системе Трилло используется 27 клавиш, из которых 5 нажимаются большими пальцами (тамбы), и предлагается за один удар вводить как можно большую часть слова. В системе колобок для ввода текста используется 24 клавиши, которые нажимаются обычными пальцами (фингерами), и слова вводятся порциями, сформированными по интуитивно понятным правилам. 

Такие порции состоят из двух частей - одна часть вводится левой рукой, другая - правой. Эти части будем называть "кубиками", подразумевая, что слово складывается из них, как игрушечный домик из кубиков. Каждый кубик всегда вводит одну и ту же определенную последовательность букв (в частном случае это может быть одна буква). При одновременном вводе левого и правого кубика, в текст вводится последователность из букв обоих кубиков, правого вслед за левым. Пример разбиения слов на кубики приведен в заголовке к этому разделу. Точка соединяет левый и правый кубик в единый аккорд. Звездочка означает отсутствие одного из кубиков в аккорде. 

В отличие от стенотайпинга, где пробелы и заглавные буквы расставляются автоматически, в системе КОЛОБОК их надо вводить явно. Шифт и пробел нажимаются тамбами, и могут использоваться как традиционным способом, так и в составе аккорда. Если одновременно с аккордом, вводящим несколько букв за раз, нажать шифт, то первая буква в последовательности будет заглавная, остальные - строчные. Если одновременно с аккордом нажать пробел, то пробел будет добавлен перед последовательностью букв.

Освоение классичекого стенотайпинга осложнено тем, что его надо применять сразу полностью. Ввод по буквам (фингерспеллинг) в стенотайпинге возможен, но требует нажимать не самые простые аккорды, и поэтому медленно работает. 

В отличие от стенотайпинга, система КОЛОБОК позволяет вводить отдельные буквы, не перегружая при этом пользователя сложными аккордами. Это позволяет осваивать аккордовый ввод постепенно. После изучения алфавита, можно применять раскладку в повседневной работе, шаг за шагом добавляя в свой арсенал новые аккорды. Небесполезным бонусом является возможность вводить любые буквы левой рукой. 

Простота системы (по сравнению с традиционным стенотайпингом) позволяет реализовать ее на стороне клавиатуры в виде прошивки, избавляя от необходимости устанавливать программное обеспечение на компьютер. 

## Деление клавиатуры на области
```
+---+---+---+---+---+               +---+---+---+---+---+
| А | А | А | А | Д |               | Е | Б | Б | Б | Б |
+---+---+---+---+---+               +---+---+---+---+---+
| А | А | А | А | Д |               | Е | Б | Б | Б | Б |
+---+---+---+---+---+               +---+---+---+---+---+
| В | В | В | В | Д |               | Е | Г | Г | Г | Г |
+---+---+---+---+---+---+       +---+---+---+---+---+---+
                | К | Л |       | М | Н |
                +---+---+       +---+---+
```
- __Область А__. Это домашняя позиция для пальцев левой руки. Эта область преимущественно используется для ввода согласных.
- __Область Б__. Это домашняя позиция для пальцев правой руки. Эта область преимущественно используется для ввода гласных.
- __Области В и Г__ используются преимущественно для ввода цифр. Все цифры доступны для ввода одной рукой, правой и левой.
- __Область Д__. Это дополнительный ряд указательного пальца левой руки. На эту область назначены такие клавиши, как Enter, Backspace, Del, Tab, Esc.
- __Область Е__. Это дополнительный ряд указательного пальца правой руки. Назначение этой области пока не определено. Возможно тут будут продублированы клавиши области Д, или назначены другие клавиши, которые не нужны при работе одной левой рукой.
- __Клавиша К__. Шифт.
- __Клавиша Л__. Включение слоя навигации с одновременным зажатием Ctrl.
- __Клавиша М__. Режим ввода по словарю.
- __Клавиша Н__. Пробел.

## Способы ввода текста

__Ввод одной левой рукой__ используется, если в правой руке держим мышь. Буквы вводятся отдельными клавишами и аккордами области А. Пробел вводится аккордом в области А. 

__Ввод по одной букве двумя руками__. Буквы вводятся отдельными клавишами и аккордами областей А и Б. Пробел вводится клавишей Н. 

__Ввод по две буквы за удар__. Двумя руками одновременно нажимаются две клавиши (или аккорда). В тексте появляется последовательность из двух букв: сначала согласная буква, введенная левой рукой, затем гласная (а также буквы й, ь, ъ) введенная правой рукой.

__Ввод по слогам__. Основной способ ввода "кубиками", описанный во введении. Левой рукой вводятся левые кубики в области А, возможно с задействованием в области В. Одновременно правой рукой вводятся правые кубики в области Б, возможно с задействованием области Г. Заход в цифрую область может выполняться так: один палец одновременно нажимает клавишу в нижнем ряду области А (Б) и соседнюю клавишу в области В (Г). Таким образом при вводе текста пальцы либо целиком находятся внутри области А (Б), либо смещаются на пол клавиши вниз. Если в аккорде используются такие сдвинутые вниз сочетания, то верний ряд клавиш не задействуется.  

__Ввод по словарю__. Для часто употребляемых слов могут быть назначены аккордовые сокрашения. Нажимая такой аккорд вместе с клавишей М, вводим такое слово за один удар. 

## Использование одинаковых аккордов различным способом

В области А есть аккорды для ввода гласных, для ввода знаков препинания, для различных хоткеев. Эти аккорды занимают пространство на клавиатуре, которое также необходимо для ввода большого количества левых кубиков. Чтобы эффективно использовать это пространство, вводим следующее правило. Если нажаты клавиши одновременно на правой и левой стороне, то аккорд на левой стороне трактуем как левый кубик. Если на правой стороне ничего не нажато, то аккорд на левой стороне трактуем как гласную, знак препинания или хоткей. 

Может возникнуть ситуация, когда левый кубик нужен, а правый нет. Чтобы прошивка обработала ввод как левый кубик, надо ввести _пустой правый кубик_. Для этого надо нажать среднюю клавишу в области Е. 

## Тренировочные примеры

- [Урок 1. Буквы с в е о](learning/lesson001.md)
- [Урок 2. Буквы к т а и](learning/lesson002.md)
- [Урок 3. Буквы д б ы у](learning/lesson003.md)
- [Урок 4. Буквы п н я ь](learning/lesson004.md)
- [Урок 5. Буквы р м ю э](learning/lesson005.md)
- [Урок 6. Буквы л ч ъ ё](learning/lesson006.md)
- [Урок 7. Буквы з г сочетания ел ол](learning/lesson007.md)
- [Урок 8. Буквы ж ш сочетания ал ил](learning/lesson008.md)
- [Урок 9. Буквы х ц сочетания ей ой](learning/lesson009.md)
- [Урок 10. Буквы щ ф сочетания ай ий](learning/lesson010.md)
- [Урок 11. Буква й сочетания ст ем ом](learning/lesson011.md)
- [Урок 12. Сочетания пр эт ам им](learning/lesson012.md)
- [Урок 13. Сочетания ск чт ен он](learning/lesson013.md)
- [Урок 14. Сочетания как он ан ин](learning/lesson014.md)
- [Урок 15. Сочетания был буд его ого](learning/lesson015.md)
- [Урок 16. Сочетания вс сл ать ить](learning/lesson016.md)
- [Урок 17. Сочетания от так ер ор](learning/lesson017.md)

## История разработки
# 08.07.2023
Добавил кубики "ель", "оль", "аль". Удалил кубики "ец", "оей", "ич"

# 06.07.2023
Добавил аккорды для работы одной рукой [ТаблицаАккордов.xlsx](ТаблицаАккордов.xlsx).

# 05.07.2023
Удалил из раскладки кубик "ив", добавил значительно более частотный "ого"

# 13.06.2023
Реализована учебная прошивка для клавиатуры JORNE. [Репозитарий](https://github.com/utyv/qmk_firmware/tree/jrn-klbk/keyboards/jorne/keymaps/kolobok)

# 12.06.2023
Добавлены более длинные кубики: некоторые корни и окончания. Отобраны 200 кубиков для построения раскладки. Выполнена переразбивка [словаря](Словарь200.xlsx) с учетом этого списка кубиков.

Собрана [статистика кубиков (набор 200)](СтатистикаКубиков200.md) по этому словарю.

Выбраны аккорды для этих кубиков [ТаблицаАккордов.xlsx](ТаблицаАккордов.xlsx).

# 04.06.2023
Добавлен [слоговый словарь](Словарь.xlsx). Словарь собран по набору текстов из раздела "Современная русская проза". Объем текстов 150 Мб. В этих текстах найдено около 500 000 различных словоформ, из которых в словарь взято 50 000 наиболее частотных. 

Далее словоформы были разбиты на слоги в соответствии с правилами фонетики. Из этих правил сделаны исключения:
- Приставки отделяются от остальной части слова. Приставки алгоритм находил по простому совпадению подстроки, без учета семантики, это внесло погрешность в статистику.
- Двойные согласные разделяются на два слога

После алгоритмической разбивки словарь был отредактирован вручную.

По этому словарю собрана [статистика кубиков](СтатистикаКубиков.md), которую можно использовать для создания раскладки.
