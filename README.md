# kolobok
## Слоговая раскладка клавиатуры "КОЛОБОК"
___

## чт.о   так.ое   сл.о г.о в.ая   рас.* кл.а дк.а   к.о л.о б.ок?

Раскладка КОЛОБОК предлагает метод ввода текстов на русском языке с использованием [эрго-сплит клавиатуры](https://habr.com/ru/companies/dododev/articles/511664/). В общем случае ввод осуществляется одновременным нажатием нескольких клавиш (аккордом), при этом за одно нажатие (удар) может быть введено несколько букв. В широком смысле раскладка является [теорией стенотайпинга](https://www.openstenoproject.org/plover/) (в стенотайпинге подобные системы ввода текста принято называть "теориями").

Для русского языка в открытом доступе существует только одна теория, поддерживающая компьютерную расшифровку ввода - за авторством Priscilla E. Trillo. Создание альтернативной системы мотивировано желанием упростить освоение аккордового ввода. В системе КОЛОБОК текст вводится более короткими порциями, уделяется большое внимание принципам  разделения текста на порции, с учетом фонетики и морфологии русского языка. В системе Трилло используется 11 колонок по 2 клавиши для фингеров (так принято называть пальцы кроме больших), 5 клавиш для тамбов (так принято называть большие пальцы), и предлагается за один удар вводить как можно большую часть слова. В системе колобок для ввода текста используется 8 колонок по 2 клавиши для фингеров, тамбы не используются, и слова вводятся порциями, сформированными по интуитивно понятным правилам. 

Такие порции состоят из двух частей - одна часть вводится левой рукой, другая - правой. Эти части будем называть "кубиками", подразумевая, что слово складывается из них, как игрушечный домик из кубиков. Каждый кубик всегда вводит одну и ту же определенную последовательность букв (в частном случае это может быть одна буква). При одновременном вводе левого и правого кубика, в текст вводится последователность из букв обоих кубиков, правого вслед за левым. Пример разбиения слов на кубики приведен в заголовке к этому разделу. Точка соединяет левый и правый кубик в единый аккорд. Звездочка означает отсутствие одного из кубиков в аккорде. 

В отличие от стенотайпинга, где пробелы и заглавные буквы расставляются автоматически, в системе КОЛОБОК их надо вводить явно. Шифт и пробел нажимаются тамбами, и могут использоваться как традиционным способом, так и в составе аккорда. Если одновременно с аккордом, вводящим несколько букв за раз, нажать шифт, то первая буква в последовательности будет заглавная, остальные - строчные. Если одновременно с аккордом нажать пробел, то пробел будет добавлен перед последовательностью букв.

Освоение классичекого стенотайпинга осложнено тем, что его надо применять сразу полностью. Ввод по буквам (фингерспеллинг) в стенотайпинге возможен, но требует нажимать не самые простые аккорды, и поэтому медленно работает. 

В отличие от стенотайпинга, система КОЛОБОК позволяет вводить отдельные буквы, не перегружая при этом пользователя сложными аккордами. Это позволяет осваивать аккордовый ввод постепенно. После изучения алфавита, можно применять раскладку в повседневной работе, шаг за шагом добавляя в свой арсенал новые аккорды. Небесполезным бонусом является возможность вводить любые буквы левой рукой, при этом в правой руке можно держать мышь. 

Простота системы (по сравнению с традиционным стенотайпингом) позволяет реализовать ее на стороне клавиатуры в виде прошивки, избавляя от необходимости устанавливать программное обеспечение на компьютер. 

## Обзор раскладки
![layout](/layout.png)

[http://www.keyboard-layout-editor.com/#/gists/5557a0ccad7c531f38f32e39619f1eff]

__Область букв__ выделена синим цветом. Это домашняя позиция для пальцев. С левой стороны согласные, с правой - гласные. 

Часть букв вводятся одновременным нажатием двух клавиш. Например, для ввода буквы "М" надо нажать клавиши К и Т, а для ввода буквы Ю надо нажать клавиши Е и Я.

Сочетания букв также вводятся с одновременным нажатием нескольких клавиш в этой области.

__Область цифр__ выделена зеленым цветом. Одновременное нажатие нескольких клавиш вводит цифру, равную сумме нажатых цифр.  Комбинация 28 вводит 0. Комбинации, которые дают в сумме больше 10 вводят точку, запятую и дефис - аккорды для этих символов продублированы в буквенной и цифровой областях, чтобы их было удобно вводить как в составе текста, так и при вводе чисел. Квадратные и фигурные скобки не вошли в область символов и вводятся в области цифр с шифтом.

__Область символов__ выделена фиолетовым цветом. Аккорры этой области в комбинации с шифтом позволяют вводить до 30 различных символов. Рекомендуется настраивать эту область в зависимости от индивидуальных потребностей и предпочтений.

__Дополнительный ряд указательного пальца левой руки__  -  область выделена красным. Backspace, Enter, Del соответственно. 

Комбинация ENT DEL срабатывает как нажатие Esc.

__Дополнительный ряд указательного пальца правой руки__  -  область выделена красным.

Клавиша UND удаляет символы, введенные последним нажатым аккордом. Отслеживается история из восьми аккордов. При навигации, и в некоторых других случаях, история очищается. Если история пуста, то нажатие UND вызывает Ctl+Backspace.

В этой области есть модификаторы Alt и Win.

__Тамб кластер__ - клавиши, нажимаемые большими пальцами, выделены желтым цветом. 

Shft - клавиша шифт для ввода заглавных букв. При вводе сочетания букв, заглавной вводится только первая буква в сочетании.

Spc - пробел. Допускается нажатие пробела вместе с буквами. При этом пробел вводится перед буквой или сочетанием букв.

wCtl - клавиша "слабый контрол". При работе мышью эта клавиша ведет себя как обычный контрол, а в  сочетании с другими клавишами - как слоефикатор. Например, нажатие букв на левой половине с клавишей Ctl вызывает команды перемещения курсора (стрелки и др.), комбинация Ctl+4 вызывает команду копирования Ctl+C, а комбинация Ctl+Ent вызывает команду переключения между окнами Alt+Tab.

Word - позволяет вводить целые слова и фразы одним аккордом. Например, "Добрый день" или "Пожалуйста". Список слов и аккордов к ним определяется индивидуально.

Cap - действует аналогично клавише "шифт", но при вводе последовательности букв, все буквы печатаются заглавными. При необходимости одновременного использования режимов Word и Cap, эти клавиши можно нажать поочередно, до того как буквенные клавиши будут отпущены.

Ctl - обычный контрол. В отличие от клавиши wCtl не включает слой.

Полный перечень аккордов можно посмотреть в файле [ТаблицаАккордов.xlsx](ТаблицаАккордов.xlsx)

## Тренировочные примеры

### Уровень 0

- [Урок 1. Буквы с в е о](learning/lesson001.md)
- [Урок 2. Буквы к т а и](learning/lesson002.md)
- [Урок 3. Буквы д б ы у](learning/lesson003.md)
- [Урок 4. Буквы п н я ь](learning/lesson004.md)
- [Урок 5. Буквы р л ю э](learning/lesson005.md)
- [Урок 6. Буквы м г сочетания ей ой](learning/lesson006.md)
- [Урок 7. Буквы ч з сочетания ай ий](learning/lesson007.md)
- [Урок 8. Буквы ж х сочетания ель оль](learning/lesson008.md)
- [Урок 9. Буквы ш ц сочетания ать ить](learning/lesson009.md)
- [Урок 10. Буквы щ ф сочетания ый уй](learning/lesson010.md)
- [Урок 11. Буквы ъ й ё сочетание яй](learning/lesson011.md)

### Уровень 1

- [Урок 12. Сочетания ст пр ел ол](learning/lesson012.md)
- [Урок 13. Сочетания как он ал ил](learning/lesson013.md)
- [Урок 14. Сочетания чт был его ого](learning/lesson014.md)
- [Урок 15. Сочетания эт вс от ер](learning/lesson015.md)
- [Урок 16. Сочетания сл ск ем ом](learning/lesson016.md)
- [Урок 17. Сочетания так котор ен он](learning/lesson017.md)
- [Урок 18. Сочетания кр тр ет али](learning/lesson018.md)
- [Урок 19. Сочетания дн ств ая ала](learning/lesson019.md)
- [Урок 20. Сочетания зн стр ан или](learning/lesson020.md)
- [Урок 21. Сочетания из гд ов ое](learning/lesson021.md)
- [Урок 22. Сочетания вн бр ает од](learning/lesson022.md)
- [Урок 23. Сочетания др гр ее ые](learning/lesson023.md)
- [Урок 24. Сочетания жн мн им ие](learning/lesson024.md)
- [Урок 25. Сочетания гл дв ор ам](learning/lesson025.md)
- [Урок 26. Сочетания чн об ех ую](learning/lesson026.md)
- [Урок 27. Сочетания вр см ых ять](learning/lesson027.md)
- [Урок 28. Сочетания кт -т ул ым](learning/lesson028.md)
- [Урок 29. Сочетания вл тн ед ах](learning/lesson029.md)
- [Урок 30. Сочетания дл кл ыть ыл](learning/lesson030.md)
- [Урок 31. Сложные слова](learning/lesson031.md)

### Уровень 2

- [Урок 32. Сочетания спр сч их оз](learning/lesson032.md)
- [Урок 33. Сочетания зд св ами ение](learning/lesson033.md)
- [Урок 34. Сочетания сказ говор ему аль](learning/lesson034.md)
- [Урок 35. Сочетания раз вст ит ила](learning/lesson035.md)
- [Урок 36. Сочетания дел буд ар ому](learning/lesson036.md)
- [Урок 37. Сочетания сн пер ения ели](learning/lesson037.md)
- [Урок 38. Сочетания вш вид ость ин](learning/lesson038.md)
- [Урок 39. Сочетания ср каз ия есть](learning/lesson039.md)
- [Урок 40. Сочетания сам пл аю ут](learning/lesson040.md)
- [Урок 41. Сочетания жд сп ез ило](learning/lesson041.md)
- [Урок 42. Сочетания одн скольк ас ял](learning/lesson042.md)
- Урок 43. Сочетания хорош бл еть уть
- Урок 44. Сочетания кн чк иль ите
- Урок 45. Сочетания вств встр ои ае
- Урок 46. Сочетания бн скр ете аете
- Урок 47. Сочетания скл сх аем ают

## Реализации раскладки

- Прошивка QMK для клавиатуры JORNE. [Репозитарий](https://github.com/utyv/qmk_firmware/tree/jrn-klbk/keyboards/jorne/keymaps/kolobok)
- Прошивка QMK для клавиатуры DACTYL MANUFORM 4x5. [Репозитарий](https://github.com/utyv/qmk_firmware/tree/dactyl_klbk/keyboards/handwired/dactyl_manuform/4x5/keymaps/klbk)

## Автор

Если вас заинтересовала раскладка КОЛОБОК и появились какие-либо вопросы, напишите мне в телеграм [https://t.me/vlad_utyumov](https://t.me/vlad_utyumov)

## История разработки

# 23.01.2024
Выбрал кубики и аккорды для второго уровня

# 14.12.2023
Отказался от использования клавиши "звездочка". Ранее эта клавиша обеспечивала одновременную доступность однорукого и двурукого режимов ввода. Теперь однорукий ввод включается специальной командой.

# 25.09.2023
Отказался от идеи сразу осваивать набор аккордов КОЛОБОК 200. Вместо этого отобрал набор легких аккордов "Уровень 1". Задним числом выделил минимальный набор "Уровень 0".
Начал тренировать "Уровень 1" с целью 300 знаков в минуту.

# 24.09.2023
Кубик "ъ" перенес с правой стороны па левую
Заменил аккорд в кубиках "оль", "ель", "ье"

# 22.09.2023
Заменил аккорд в кубиках "ин", "ить"
Добавил кубик "ыть"
Удалил левый кубик "от"

# 21.09.2023
Добавил кубик "ыл"
Удалил кубик "ек"

# 18.09.2023
Добавил кубики "уй", "яй".
Заменил аккорды для кубиков "ения", "ую".
Удалил кубики "ог", "ою"

# 17.08.2023
Для кубиков "ас", "аз", "ед", "стр" сделал менее логичные но более удобные аккорды

# 16.08.2023
Автор перешел на повседневное использование раскладки 

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
