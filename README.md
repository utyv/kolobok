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

## Обзор раскладки
![layout](/layout.png)

[http://www.keyboard-layout-editor.com/#/gists/5557a0ccad7c531f38f32e39619f1eff]

__Область букв__ выделена синим цветом. Это домашняя позиция для пальцев. С левой стороны согласные, с правой - гласные. 

Часть букв вводятся одноврененным нажатием двух клавищ. Например для ввода буквы "М" надо нажать клавиши К и Т, а для ввода буквы Ю надо нажать клавищи Е и Я.

Сочетания букв также вводятся с одновременным нажатием нескольких клавиш в этой области. В некоторых случаях также задействуется область цифр и клавиша \*.

Также комбинации клавиш на левой стороне буквенной области используются для ввода знаков препинания и некоторых хоткеев. Например, комбинация КТН вводит точку, а ВТП вызывает команду вставки Ctl+V.

Кроме того на левой стороне комбинациями из двух клавиш продублированы все буквы, которые обычно набираются на правой стороне. Это делает возможным использовать только левую половину клавиатуры, а в правой руке держать мышь.

__Область цифр__ выделена зеленым цветом. Одновременное нажатие нескольких клавиш вводит цифру, равную сумме нажатых цифр.  Комбинация 28 вводит 0. Комбинации, которые дают в сумме больше 10 вводят точку, запятую и дефис - аккорды для этих символов продублированы в буквенной и цифровой областях, чтобы их было удобно вводить как в составе текста, так и при вводе чисел.

__Дополнительный ряд указательного пальца левой руки__  -  область выделена красным. Backspace, Enter, Del соответственно. 

Комбинация ENT DEL срабатывает как нажатие Esc.

Комбинация BS ENT удаляет символы, введенные последним нажатым аккордом. Отслеживается история из восьми аккордов. При навигации, и в некоторых других случаях, история очищается. Если история пуста, то нажатие BS ENT вызывает Ctl+Backspace.

__Дополнительный ряд указательного пальца правой руки__  -  область выделена красным.

Клавиша \* используется при вводе сочетаний букв. Например, комбинация ВКТ используется для ввода символа \/, и для ввода сочетания ЭТ. Если мы нажимаем ВКТ отдельно - получает слеш. Если нажимаем ВКТ вместе с клавишей О, то получаем сочетание ЭТО. Но что если нам надо ввести сочетание ЭТ без гласной, например в составе слова ЭТНОГРАФИЯ? Тогда надо нажать комбинацию клавиш ВКТ вместе с клавишей \*. Другой пример - комбинация клавиш ПН. Если на правой стороне ничего не нажато, то эта комбинация вводит букву И. Если же на правой стороне, одновременно с комбинацией ПН, ввести букву, сочетания букв, или нажать клавишу \*, то комбинация ПН будет обозначать сочетание букв ПР.

Клавиша EN переводит клавиатуру в режим транслитерации и одновременно переключает раскладку в системе. Режим транслитерации означает, что нажимая клавишу Н, мы получим букву N. Нажатие сочетания EN и \* включает транслит без переключения раскладки в системе.

Клавиша RU выключает режим транслитерации и одновременно переключает раскладку в системе. Нажатие сочетания RU и \* выключает транслит без переключения раскладки в системе.

__Тамб кластер__ - клавиши, нажимаемые большими пальцами, выделены желтым цветом. 

Shft - клавиша шифт для ввода заглавных букв. При вводе сочетания букв, заглавной вводится только первая буква в сочетании.

Spc - пробел. Допускается нажатие пробела вместе с буквами. При этом пробел вводится перед буквой или сочетанием букв.

Ctl - клавиша "контрол". Поведение клавиши в комбинации с другими клавишами переопределено. Например, нажатие букв на левой половине с клавишей Ctl вызывает команды перемещения курсора (стрелки и др.), комбинация Ctl+4 вызывает команду копирования Ctl+C, а комбинация Ctl+Ent вызывает команду переключения между окнами Alt+Tab.

Word - позволяет вводить целые слова и фразы одним аккордом. Например, "Добрый день" или "Пожалуйста". Список слов и аккордов к ним определяется индивидуально.

Cap - действует аналогично клавише "шифт", но при вводе последовательности букв, все буквы печатаются заглавными. При необходимости одновременного использования режимов Word и Cap, эти клавиши можно нажать поочередно, до того как буквенные клавиши будут отпущены.

MT - режим "multitap". Для более предсказуемого поведения аккордов, прошивка реализована так, что ввод символов осушествляется после того, как все клавиши (кроме модификаторов) будут отпущены. В результате становится недоступно стандартное поведение клавиатуры, когда мы удерживаем клавищу, и спустя какое-то время начинается повторяющийся ввод нажатой клавиши. Клавиша MT позволяет решить эту проблему. Надо сначала зажать нужную клавишу или аккорд, и не отпуская его нажать клавишу MT. Повторяющийся ввод начнется немедленно и будет продолжаться, пока вы не отпустите аккорд или клавишу MT. Если надо использовать режим multitap совместно с клавшей Ctl (например для перемещения курсора), то надо сначала зажать нужную клавищу с Ctl, затем, не отпуская основной клавиши,  отпустить Ctl и нажать MT.

Полный перечень аккордов можно посмотреть в файле [ТаблицаАккордов.xlsx](ТаблицаАккордов.xlsx)

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
- [Урок 18. Сочетания котор кр ель оль](learning/lesson018.md)
- [Урок 19. Сочетания тр дн ет от](learning/lesson019.md)

## Реализации раскладки

- Прошивка QMK для клавиатуры JORNE. [Репозитарий](https://github.com/utyv/qmk_firmware/tree/jrn-klbk/keyboards/jorne/keymaps/kolobok)

## История разработки

# 05.08.2023
Описал аккорды для всех символов и команд. [ТаблицаАккордов.xlsx](ТаблицаАккордов.xlsx)

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
