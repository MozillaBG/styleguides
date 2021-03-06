# Наръчник на преводача

### Автори
Михаил Балабанов <mishob@abv.bg>
Радостин Раднев <radnev@yahoo.com>

*Адаптирано към нуждите на общността на Mozilla с разрешението на авторите.*

## Общи правила за превод

Надписите в потребителския интерфейс представляват обикновен текст, написан от автора на приложението и предназначен за четене от потребителя (а не от приложението). Можем да ги сравним например с надписите върху автомат за напитки.

На местата, където има указания за потребителя, се използва повелително наклонение. Правилният превод на „Click the button to continue“ е „Натиснете бутона, за да продължите“, а не „Натискане на бутона за продължение“. Чрез надписа авторът на приложението казва на потребителя какво да направи.

Инструкциите за потребителя винаги са в учтива форма: „Въведете име и парола“, а не „Въведи име и парола“.

В елементите, чрез които потребителят предизвиква действия на приложението (бутони и позиции от менюта), за обозначаване на тези действия се използват обикновени или отглаголни съществителни имена. „Отглаголно съществително“ е съществително, образувано от глагол чрез наставка „-не“: отваряне, затваряне, проверяване, записване. Когато е възможно, е добре вместо тях да се използват съответните обикновени съществителни - проверка, запис; в много случаи обаче - като „отваряне“ и „затваряне“ - няма такава възможност.

Например, правилният превод на „Copy“ в меню е „Копиране“, а не „Копирай“. В този случай единственият читател на надписа е потребителят, а действието няма да се извърши от него, за да бъде в повелително наклонение. От друга страна, приложението не изпълнява някаква осъзната заповед, а просто реагира логически на натискането на бутона, както машината за напитки - на бутона с надпис „Капучино“.

Препоръчва се използването на безлични изрази, за да не се създава чувство у потребителя, че компютърът е някакво интелигентно същество. Правилният превод на „Document changed. Do you want to save the changes?“ е „Документът е променен. Искате ли промените да бъдат запазени?“, без уточняване кой е променил документа и кой ще запази промените. Не се препоръчва използването на формите „Искате ли да запазя промените?“ (аз) или „Искате ли да запазите промените?“ (Вие). И двата израза не са точни, защото автор на надписа („аз“) е програмистът, а читател („Вие“) е потребителят - никой от двамата не извършва действието по запазване на промените - то се случва чрез кода на първия под влияние на действията на втория.

Когато потребителят се уведомява за нещо, се предпочитат изречения в сегашно време - набляга се върху текущото състояние на нещата: „Документът е променен“, а не „Документът бе/беше променен“. Ако все пак е нужно да се наблегне върху самото отминало събитие, се използва преизказно наклонение (на „-л“, „-ла“, „-ло“, „-ли“): „Възникнала е грешка при прехвърлянето“.

При условните изречения в указанията за потребителя първо се поставя главното изречение, а след него - условието. Препоръчва се употребата на следната форма: „Натиснете бутона, за да продължите“, а не на тази: „За да продължите, натиснете бутона“. Друг пример: „Отметнете полето, ако искате еди-какво си“, а не „Ако искате еди-какво си, отметнете полето“.

Препоръчва се да не се превежда „this“. При писането на програми и документация на английски се препоръчва използването на „this“, вместо определителния член „the“. Разбира се, не всички спазват тези препоръки и често можете да видите и употребата на „the“. При превода на български език се препоръчва да не се превежда „this“, а вместо това да се използва членувана форма на съществителното име. По-добре е „Документът е променен“, вместо „Този документ е променен“.

Препоръчва се когато е възможно в превода да се изпуска местоимението „Вие“, ако смисълът на израза е ясен и без него, например: „Трябва да въведете паролата си, преди да натиснете OK“, а не: „Вие трябва да въведете Вашата парола, преди…“. На английски местоименията се поставят задължително, тъй като английските глаголи нямат окончания, по които да си личат лицето и числото на подлога. На български те само правят изречението по-тромаво.

Освен това се препоръчва употребата на кратките форми на притежателни местоимения: „Писмото ви е достигнало до адресата“, а не „Вашето писмо е достигнало…“. При това трябва да се внимава кога е необходимо възвратно местоимение, например не се пише „Въведете името Ви“, а „Въведете името си“.

Препоръчва се, да се съгласуват отделните елементи на ГПИ. Примерно има списък или група от превключватели с етикет „Дължина“. Правилното е опциите за избор да бъдат „Къса“, „Средна“ и „Дълга“, а не „Къс“, „Среден“ и „Дълъг“.

Не се препоръчва използването на главни букви в началото на всяка дума. Правилното е „Запис като“, а не „Запис Като“.

## Менюта

### Главно меню

При превода и при създаването на нови програми елементите на главното меню трябва да се състоят от по една дума - съществително име. Глаголите се заменят с обикновени или отглаголни съществителни.
```
File - Файл
Edit - Редактиране (а не Редактирай)
View - Изглед (а не Прегледай)
Window - Прозорец
Help - Помощ
```

### Подменюта

Елементите на менюта трябва да са съществителни или именни словосъчетания (еквивалентни на съществително). Не се използват глаголи в повелително наклонение. Не се препоръчва използването само на прилагателни имена - за предпочитане е те да бъдат придружени от съществителни.
```
New - Създаване (или Нов документ, Нов файл, Нова игра, а не само Нов)
Open - Отваряне (или Зареждане, а не Отвори или Зареди)
Save - Запис (или Записване, а не Запиши)
Quit - Изход (а не Излез)
Copy - Копиране (а не Копирай)
```

## Надписи в диалогови прозорци

### Етикети на текстови полета
Тук става дума за пояснителните надписи пред текстовите полета в диалогов прозорец, например „Password: [__________]“. Препоръчва се надписът да е съществително име или именно словосъчетание, описващо съдържанието на полето. Пред него може да се постави подкана в учтива форма от рода на „Въведете…“ или „Задайте…“. Препоръчва се използването на следните форми:
```
  Въведете парола и я потвърдете в долното поле:

              Парола: ________________
        Потвърждение: ________________


     Въведете парола: ________________
 Потвърдете паролата: ________________
```

В случая използването на отглаголни съществителни като „Въвеждане на…“ или „Задаване на…“ не е подходящо. Не се препоръчва използването на следната форма:
```
      Въвеждане на парола: ________________
   Потвърждение на парола: ________________
```

### Надписи върху бутони

Избягва се повелителното наклонение. Препоръчва се действието на бутона да се описва с отглаголно или обикновено съществително име. Българският надпис трябва да отразява смислово действието на бутона, а не да е буквален превод на оригиналния надпис.

При превода на програми преводачите нямат голям контрол над някои бутони. Например, бутонът „OK“ се използва в системната функция, която показва съобщения за грешки, информация или задава въпроси към потребителя (warning, info, error и question). Същият бутон се използва и в диалоговите прозорци за потвърждаване на направени промени. Някои програми позволяват използването на различни преводи в тези два случая. Други обаче използват една и съща функция за представянето на този бутон и е невъзможно да той да бъде преведен различно в двата отделни контекста. Затова е добре да се приеме един универсален, неутрален към контекста превод за бутона „OK“. Подобно е положението и с бутона „Cancel“.

В официалния превод на Windows бутонът „OK“ е „OK“, а „Cancel“ - „Отказ“. Други варианти за „OK“ са например „Готово“, „Добре“ или „Потвърждение“. Лошото е, че всеки от тях е подходящ само в определен контекст. Тук може би има смисъл да се съгласим с преводачите на Windows, разчитайки, че английското „о'кей“ вече е почти толкова употребяван израз в България, колкото и италианското „чао“.

В някои случаи програмата показва диалогови прозорци с информация, която не можем да променим, например диалоговия прозорец „About“. Различните автори на програми използват различни команди за затварянето на такъв диалогов прозорец. В друг случай програмата представя диалогов прозорец с възможност за промяна на информацията но без бутони „OK“ и „Cancel“, а само с един бутон за затваряне, т. е. всички промени се запазват веднага и не могат да бъдат отказани. И в този случай авторите на програми използват различни команди за затварянето на прозореца, като „Done“, „Close“ и „Quit“. Ако преводачите имат контрол над преводите в тези два случая е добре да се използва една и съща дума, например „Изход“ или „Затваряне“.

### Етикети на полета за отметка

Това са пояснителните надписи към полета с по две алтернативни състояния - включено и изключено. Тези полета обикновено означават включване или изключване на някакъв режим, например „[\_] Autosave every 10 minutes“ - режим на работа с автоматично запазване през 10 минути. Тези текстове се превеждат както надписите върху ключовете на „обикновена“ машина - с името на съответния режим: „[\_] автоматично запазване на 10 мин.“ Отново, вместо глаголи в повелително наклонение се препоръчва използването на обикновени или отглаголни съществителни. Препоръчва се използването на следните форми:
```
Reload Open Files on Startup
Зареждане на файловете при стартиране
```

Не се препоръчва използването на следните форми:
```
Reload Open Files on Startup
Зареди файловете при стартиране
Зарежда файловете при стартиране
```

Ако действието съвпада с положението на отметката, може да се пропусне преводът на глагола. Препоръчва се използването на следните форми:
```
Allow Multiple Instances
Разрешаване на няколко екземпляра
Много екземпляри
```

Добре е думата „Enable“ да се пропуска в превода за краткост, тъй като се подразбира. Препоръчва се използването на следната форма:
```
Enable Line Numbers
Номериране на редовете
```

Не се препоръчва използването на следните форми:
```
Enable Line Numbers
Включване на номерата на редовете
Разрешаване на номерирането на редовете
```

Не се препоръчва се авторите на оригинален софтуер да използват отрицание, както е в следващите примери. Положителната форма е по-интуитивна: има отметка - режимът е включен, няма отметка - режимът е изключен. За съжаление при превода на програми, ако авторът е употребил отрицание, това няма как да се избегне.

Ако отмятането на полето има обратно значение, т. е. то означава изключване на съответния режим, най-добре е надписът се превежда с „Без …“, последвано от името на режима. Препоръчват се следните форми:
```
Disable Line Numbers
Без номера на редове

Don't show feedback
Без обратна връзка

Don't split table
Без разделяне на таблицата
```

В някои диалогови прозорци за съобщения или въпроси има полета за отметка, които служат за подтискане на следващи показвания на същия диалогов прозорец. Обикновено тези фрази се превеждат малко тромаво с „Без…“, затова в подобни случаи се препоръчва използването на следните форми:
```
Don't warn me again
Изключване на предупреждението

Don't ask me this again
Изключване на въпроса

Warn me when other applications try to send mail as me
Предупреждение при опити от други приложения да изпращат
поща от мое име
```

Не се препоръчва използването на следните форми:
```
Don't warn me again
Не ме предупреждавай отново

Don't ask me this again
Не ме питай повече за това
Изключване на този въпрос

Warn me when other applications try to send mail as me
Предупреждавай ме, когато други приложения се опитват
да изпращат поща от мое име
```

Когато логически свързани помежду си полета за отметка са обединени под общо заглавие (например с групираща рамка), добре е в надписите им да се избягват повторенията със заглавието, а още по-добре е, ако образуват цялостно словосъчетание с него:
```
.- Aligning options -----.  .- Подравняване ---------.
| [_] Align horizontally |  | [_] хоризонтално       |
| [_] Align vertically   |  | [_] вертикално         |
`------------------------'  `------------------------'

.- Convert --------------.  .- Преобразуване на -----.
| [_] Convert comments   |  | [_] коментарите        |
| [_] Convert graphics   |  | [_] изображенията      |
`------------------------'  `------------------------'
```

### Етикети на превключватели

Превключватели наричаме всякакви елементи за управление с по няколко алтернативни състояния, при които само един от дадена група може да е включен. При тях се спазват същите правила, както и при надписите на полета за отметка: превключвателите служат за избор на един от няколко режима на работа и се надписват с имената на съответните режими.

Тъй като превключвателите винаги са групирани по два или повече, важно е да се следи за последното правило от предишния раздел - избягване на повторенията със заглавието на групата и образуване при възможност на цялостен израз с него и всеки от надписите на отделните превключватели.

Следва пример за превод на надписите на превключватели:
```
.- When a virus is found -----.  .- Действие при открит вирус: --.
| (_) Disinfect               |  | (_) премахване                |
| (_) Prompt for disinfection |  | (_) премахване с потвърждение |
| (_) Just report             |  | (_) само съобщение            |
`-----------------------------'  `-------------------------------'
```

Препоръчва се отделните елементи да се съгласуват по род и число с етикета. Това правило важи за всички случай, но най-често се правят грешки при превода на превключватели. Препоръчва се използването на следните форми:
```
.- Length: -----.  .- Дължина: --------.
| (_) Short     |  | (_) Къса          |
| (_) Middle    |  | (_) Средна        |
| (_) High      |  | (_) Дълга         |
`---------------'  `-------------------'

.- Location: ---.  .- Местоположение: -.
| (_) Left      |  | (_) Ляво          |
| (_) Right     |  | (_) Дясно         |
| (_) Up        |  | (_) Горе          |
| (_) Down      |  | (_) Долу          |
`---------------'  `-------------------'
```

Не се препоръчва използването на следните форми:
```
.- Length: -----.  .- Дължина: --------.
| (_) Short     |  | (_) Къс           |
| (_) Middle    |  | (_) Среден        |
| (_) High      |  | (_) Дълъг         |
`---------------'  `-------------------'

.- Location: ---.  .- Местоположение: -.
| (_) Left      |  | (_) Ляв           |
| (_) Right     |  | (_) Десен         |
| (_) Up        |  | (_) Горен         |
| (_) Down      |  | (_) Долен         |
`---------------'  `-------------------'
```

### Елементи на списъци

При превода на елементите в списъци важат общите правила за превод. Избягва се повелително наклонение, ако става дума за извършвани от програмата действия. Ако е приложимо, спазва се правилото за логическо обединяване на отделните елементи и избягване на повторенията във всеки елемент от групата.

## Диалогови прозорци за съобщения (message boxes)

Обикновено чрез тези прозорци потребителят бива осведомяван за събитие, случило се в минал момент от работата на програмата или за възникването на състояние, което е в сила и в момента на показването на съобщението на екрана. Някои от прозорците със съобщения изискват потребителят да направи някакъв избор чрез набор от стандартни бутони - OK, Cancel, Retry и т. н. Дължината на текстовете в тях по правило не е толкова ограничена, колкото на останалите надписи от ГПИ, което прави превода им малко по-лесен.

Диалоговите прозорци за съобщения обикновено могат да се класифицират в някоя от следните категории:

* Уведомителни съобщения (Information): съобщават за нормално събитие (не грешка), без да подканват потребителя да направи някакъв избор. Съдържат само съобщителна част и са придружени само от бутон OK. За заглавие на такъв прозорец се препоръчва „Информация“.
* Предупреждения (Warning): съобщават за възникването на ситуация, която не може да се определи със сигурност като грешка, но би могла да доведе до нежелани последствия. Съдържат съобщителна част и понякога - въпрос или подкана към потребителя. За заглавие на такъв прозорец се препоръчва „Предупреждение“.
* Съобщения за грешка (Error): съобщават за възникването на грешка. Обикновено освен съобщителната част съдържат въпрос или подкана към потребителя за избор на ответно действие. За заглавие на такъв прозорец се препоръчва „Грешка“.
* Въпроси и заявки за потвърждение (Question и Confirmation): чрез тези прозорци се изисква потребителят да направи избор чрез стандартните бутони. Може да съдържат отделна съобщителна част преди въпроса и винаги съдържат част с въпрос или подкана. За заглавие на такъв прозорец се препоръчва „Въпрос“ (в по-общите случаи) или „Потвърждение“ (ако става дума конкретно за въпрос от вида „Сигурни ли сте, че желаете…“).

### Съобщителна част

При превода на съобщенията се спазват общите правила за превод. Не е нужно да се превежда буквално, дума по дума - важно е да се предаде точно смисълът. Препоръчва се използването на пълни прости изречения с прав словоред: подлог, сказуемо (напр. „Паролата е невалидна“, а не „Невалидна парола“). Препоръчва се безличен начин на изразяване, при който подлог не е програмата, а обектът, върху който се извършва операция или самата операция (напр. „Копирането бе извършено успешно“, а не „Завърших копирането успешно“).

Добре е при превода да се избягват излишните местоимения „Вие“ и „Ваш“, където смисълът е ясен без тях. Същото важи и за показателното местоимение „този“, напр. „Документът е бил променен“, а не „Този документ е бил променен“.

Препоръчва се използването на следните форми:
```
Operation complete
Операцията завърши.

Congratulations, you won!
Поздравления, Вие спечелихте!

Hardware installation completed with no errors.
Инсталирането на хардуера завърши без грешки.

Your kernel configuration has been saved. You need to
run "make symlinks dep" now.
Конфигурацията на ядрото е запазена. Сега е необходимо
да изпълните "make symlinks dep".

Unable to save file XYZ.
Файлът XYZ не може да се запише.

Unable to print document.
Документът не може да се отпечата.
Отпечатването на документа е невъзможно.

Cannot Synchronize.
Синхронизирането е невъзможно.
```

Не се препоръчва използването на следните форми:
```
Operation Completed
Операцията завършена
Операцията свърши
Завърших операцията

Congratulations, you won!
Поздравявам Ви, Вие спечелихте!

Your kernel configuration has been saved. You need to
run "make symlinks dep" now.
Вашата конфигурация за ядрото е запазена. Вие е необходимо
е да изпълните командата "make symlinks dep" сега.

Unable to save file XYZ.
Не можах да запиша файла XYZ.
Не може да се запише файла XYZ.

Unable to print document.
Документът не можа да се отпечата.
Не мога да отпечатам документа.

Cannot Synchronize.
Невъзможна синхронизация.
Не може да се синхронизира.
```

Когато в съобщението става дума за отминало събитие, особено ако то е зависело от фактори, външни за програмата, се препоръчва използването на преизказно наклонение (на „-л“, „-ла“, „-ло“, „-ли“), например: „Възникнала е грешка при декодиране“, или „Писмото не е било доставено“.

Когато се съобщава за току-що отминало събитие, може да се използват безлични изрази в минало свършено време: „Файлът не бе намерен“, „Форматирането завърши успешно“.

Когато се съобщава за състояние, което е в сила и в момента на издаване на съобщението, се използва сегашно време: „Въведените от Вас данни са невалидни“, „Осъществяването на връзка е невъзможно“.

### Въпросителна част

Въпросите към потребителя са в учтива форма. Те не се задават от името на програмата, а безлично. Препоръчва се за подлог да се използва обектът или извършваната върху него операция, а не програмата или потребителят, напр. „Желаете ли запис на данните?“ а не „Да запиша ли данните?“ или „Желаете да запишете данните?“. Препоръчва се при превода да се пропускат „you“ и „your“, когато смисълът е достатъчно ясен и без тях. Препоръчва се използването на следните форми:
```
Do you want to save the changes you made to document?
(This document has been modified.) Do you want to save the changes?
(The document has been modified.) Do you want to save your changes?
Save changes?
(Документът е променен.) Искате ли промените да бъдат запазени?
(Документът е променен.) Искате ли да бъде запазен?
Желаете ли запазване на промените?

Do you really want to exit?
Наистина ли желаете изход от програмата?
Желаете ли изход от програмата?
```

Не се препоръчва използването на следните форми:
```
The document has been modified. Do you want to save your changes?
Документът беше променен. Искате ли да го запазите?
Този документ беше променен. Желаете ли да запазите промените?
Документът бе променен. Желаете ли да запазя промените?

Do you really want to exit?
Наистина ли искате да излезете?
```

### Подкани към потребителя

Ако от потребителя се очаква да направи нещо, се използва учтива форма на повелително наклонение, например „Проверете дали принтерът е включен правилно и опитайте отново“, или „Моля, въведете паролата си отново“. Препоръчва се използването на следните форми:
```
Correct the problem and try again.
[Моля,] Отстранете проблема и опитайте отново.

Enter a path:
Въведете път:
```

Не се препоръчва използването на следните форми:
```
Correct the problem and try again.
Отстрани проблема и опитай пак.

Enter a path:
Въведи път:
```

## Пояснителни текстове и указания

### Подсказки

Подсказки (hints) са кратки пояснения към елементите на потребителския интерфейс, които обикновено се показват по два начина: в лентата за състоянието или в малки прозорчета близо до показалеца на мишката (tooltips), когато той се задържи върху съответния елемент.

Тъй като по смисъл подсказките представляват просто разширени варианти на надписите пред или върху съответните елементи, те се превеждат по същите правила. Например пояснението към бутона „Копиране“ е „Копиране на маркираната област в системния буфер“. Няма нужда от уточняване от рода на „Този бутон служи за…“, тъй като потребителят и без това вече е посочил съответния елемент с мишката и очевидно вниманието му е насочено към него.

Препоръчва се „this“ да не се превежда като „това“, когато се отнася за обекта, върху който се извършва операцията, а да се заменя с членуване. Същото важи и за „your“, ако така няма да се загуби смисъла на надписа.

### Указания за потребителя

Често в страниците на помощниците или в диалоговите прозорци има кратки указания, които насочват потребителя към определени действия. Те се превеждат в учтива форма на повелително наклонение, като се използват наименованията на действията на потребителя, описани в началото на този текст, например „Натиснете бутона Х“ вместо „Щракнете върху бутона Х“ и т. н. Препоръчва се използването на следните форми:
```
Click the button "Advanced Settings" if you want
to modify all settings.
Натиснете бутона „Допълнителни настройки“, ако
искате да променяте всички настройки.

Check the option "Receive notification" if you want to
receive notification about errors in the system via e-mail.
then click the "Next" button.
Отметнете полето „Получаване на съобщения“, ако искате да
бъдете известявани за грешките в системата чрез електронна поща.
След това натиснете бутона „Напред“.
```

## Съобщения за хода на операция

Това са надписи, уведомяващи потребителя за хода на продължителна операция, например копиране на файлове, установяване на връзка с Интернет и пр. Тези надписи се превеждат чрез изрази с отглаголни съществителни (евентуално предшествани от „Извършва се… “) или чрез просто изречение в сегашно време, в което подлог е обектът, върху който се извършва операцията. Препоръчва се използването на следните форми:
```
Copying files…
Копиране на файловете…
Извършва се копиране на файловете…

Connecting to the Internet…
Свързване с Интернет…
Установяване на връзка с Интернет…
```

Не се препоръчва използването на следните форми:
```
Copying files…
Копира файловете…
Копирам файловете…

Connecting to the Internet…
Свързва се с Интернет…
Свързвам се с Интернет…
```

## Имена на програми, фирми и автори

Имената на програми, фирми и хора не се превеждат. По правило в книжовния български език имената се транскрибират (например „президентът Джордж Буш“, а не „президентът George Bush“, или „фирмата ‘Мицубиши’“, а не „фирмата ‘Mitsubishi’“). Това важи и за фирми, чиито имена са съкращения (например „Ай Би Ем“).

В много случаи обаче е важно и оригиналното изписване на името, за да може потребителят да го търси в Интернет или в други справочни материали на английски. Затова се препоръчва имената на хора и фирми се изписват при първо срещане в текста успоредно на кирилица и латиница, например „Линус Торвалд (Linus Torvald)“. Така е ясно и произношението, и оригиналният правопис на името.

От друга страна, имената на програми, ОС и библиотеки се изписват на латиница, ако представляват същевременно команди, идентификатори или съкращения на английски (например make, libpng, KDE), но могат да бъдат и транскрибирани (например Уиндоус, Юникс), когато горните съображения не важат. Преди изписани на латиница имена винаги се поставя българско съществително за пояснение, например „библиотеката wxWindows“ или „приложението telnet“. Изключение може да се направи в меню, например менюто Start на Windows, в което е ясно, че всички позиции са имена на програми.

Препоръчва се използването на следните форми:
```
KPoker
Покер KPoker

Kate
Текстов редактор Kate

KPPP
Връзка с Интернет KPPP
```

Не се препоръчва използването на следните форми:
```
KPoker
Покер - недопустимо, защото обикновено има няколко подобни програми.
KDE Покер - недопустимо, защото може всички програми в менюто да започват с KDE.
КПокер - недопустимо - съдържа съкращение на английски.

Kate
Текстов редактор - същинското име е пропуснато.
KDE Текстов редактор - името трябва да е след пояснението.
Кате - транскрибирането се прави по изговора, а не по изписването.

KPPP
Връзка с Интернет - същинското име е пропуснато.
KDE Връзка с Интернет
КППП - недопустимо - английско съкращение.
```
