
#  ***Everything you need:*** 

# **🔥🔥🔥 Module 1 🔥🔥🔥**

# **✅What is JavaScript?**
### JavaScript (JS) е интерпретиран, многопарадигмен, слабо типизиран език за програмиране, който се използва предимно за уеб разработка. Въведен е от Netscape през 1995 г.

- ### Многопарадигмен: 
JavaScript поддържа:


1 Императивно програмиране: Пограмистът дава подробни инструкции за изпълнение на програмата. Този стил се фокусира върху това "как" трябва да се извършат действията.

2 Декларативно програмиране: Фокусира се върху "какво" трябва да бъде постигнато, без да се заботите за детайлите на изпълнението. Пример за декларативен стил включва използването на функционални конструкции като map, filter и reduce.
 
3 Обектно-ориентирано програмиране (ООП): JS е обектно-ориентиран език, където програмистите могат да създават и манипулират обекти. Обектите в JS могат да бъдат използвани като инстанции на класове или като прости обекти с ключове и стойности.

4 Функционално програмиране: JS поддържа функционални концепции като функции от по-висок ред, затваряне, рекурсия и много други. Този стил на програмиране се фокусира върху използването на функции като първокласни обекти и пр

- ### Слабо типизиран:
Променливите в JavaScript не изискват предварително задаване на тип и могат да променят своя тип по време на изпълнение. 

- ### High-level language:
Това са езици които предоставят високо ниво на абстракция и са по-близки до човешкия език, което прави програмирането по-лесно за програмистите. Тези езици се характеризират с това, че предоставят абстракции и висок степен на автоматизация, като се грижат за множество детайли и подробности от програмиста. 

- ### Aсинхронен език:
Това означава, че може да изпълнява определени задачи асинхронно, без да блокира изпълнението на останалата част от програмата. Този аспект на езика е особено важен при работата със задачи, които изискват време - например, извличане на данни от мрежата, обработка на потребителски вход и други.

- ### Node.js:
JavaScript може да се изпълнява в браузъра директно.А с Node.js, JavaScript може да бъде използван за създаване на сървърни приложения. Това позволява JavaScript да се използва и на страната на сървъра, не само на страната на клиента.

# **✅Типове данни:**

- ### Primitive (*Примитивни*): 
String , number, boolean, null, undefine, symbol, bigint.

- ### Reference(*Референтни*):
Objects: (functions, arrays)

# ✅**Functions:**
Блок от код който извършва определена задача.
- ### functions declaration: 

````
console.log(add(2, 3)); // Извикване на функцията
може да стане преди декларирането.

function add(a, b) {
return a + b;
}

````

- ### function expression:
````
const multiply = function(x, y) {
return x * y;
};
````

- ### Arrow function:
````
const add = (a, b) => a + b;

// Arrow Function with block body
const subtract = (x, y) => {
return x - y;
};
````
### **⚫ Pure function:**

а). Резултатът на функцията зависи само от входните аргументи. Това означава, че функцията не променя никакви външни данни, като глобални променливи или обекти.

б). Функцията не има странични ефекти. Това означава, че функцията не извършва никакви действия, които могат да променят състоянието на системата, като например извикване на външни библиотеки или отпечатване на резултати на конзолата.

### **⚫Higher Order Functions:**

Функция, която приема функция като аргумент или връща функция като резултат, се нарича higher-order function.
### **⚫"What is currying?"**

Последователност от функции, като всяка приема само един аргумент. Резултатът е нова функция, която може да се извиква с поредица от аргументи един по един, като произвежда същия резултат, както ако всички аргументи бяха предадени на оригиналната функция наведнъж.

### **⚫What is a callback?**

Callback е функция, която се предава като аргумент на друга функция и има за цел да се изпълни след завършването на конкретна задача.



# **✅Objects**
Структура от данни от референтен тип.
Те се състоят от ключ и стойност (Key and Value);

Те имат state and behaviou:

State(данни)-the data in the objects;

Behavior(поведение)-функциите който са свързани със данните.
- ### What do we use objects for?
*Обектите са мощен инструмент, който може да се използва за подобряване на организацията, инкапсулацията, абстракцията, повторната употреба и моделиране на реалния свят на вашия JavaScript код.*

⚪ Организация на данни: Обектите са чудесни за организиране на свързани данни заедно. Това ги прави по-лесни за управление и достъп, особено когато имате много данни.

⚪  Енкапсулация на данни: Обектите могат да инкапсулират данни и функции в тях. Това означава, че данните и функциите са достъпни само за други части на кода, които изрично са разрешени да ги достъпват. Това може да помогне за подобряване на поддържането и сигурността на вашия код.

⚪ Абстракция на данни: Обектите могат да абстрактират вътрешните детайли на данните. Това означава, че можете да взаимодействате с обект въз основа на неговите свойства и методи, без да се нуждаете да знаете как данните се съхраняват всъщност или как работят функциите. Това може да направи вашия код по-повторно използваем и по-лесен за разбиране. Например, можете да използвате обект за представяне на математическа операция, като например събиране или изваждане.

- ### Destructuring:

Техника за извличане на стойности от обект или масив.

*Предимства на деструктурирането:* 

⚪ Подобрена четимост: Деструктурирането прави кода по-четим, като прави по-лесно да се види какви данни се използват и как се използват.

⚪ Намаляване на дублирането на кода: Деструктурирането може да помогне за намаляване на дублирането на кода, като ви позволи да извлечете данни от обекти и масиви в именовани променливи.

⚪ По-концизен код: Деструктурирането може да помогне за опростяване на кода, като избегне необходимостта от използване на вложени цикли.

- ### Reference copy,  shallow copy and deep copy:

⚫  _Копиране по референция:_
Копие по референция създава нова променлива, която препраща към същия обект като оригиналната променлива. Това означава, че всички промени, направени в оригиналната променлива, ще се отразят и в новата променлива.

⚫   _Shallow copy:_
Копия с различна референта стойност но не и на вложените обекти.
```
const original = {
name: "John Doe",
address: {
city: "New York"
}
};
const copy = { ...original }; или  object.assign({}, original);
original.address.city = "Varna"
console.log(copy.name); // John Doe
console.log(copy.address.city);  // Varna (Променя се спрямо   оригиналния обект.)

```
⚫   _Deep copy:_
Deep copy е метод за копиране на данни, който създава нов обект, който съдържа копия на всички свойства на оригиналния обект, включително неговите вложени обекти.
Това означава, че всички промени, направени в оригиналния обект, няма да се отразят в новосъздадения обект.


Начини за правене на deep copy:

⚪ JSON метода не копира вложените функции.
```
const deepCopy = JSON.parse(JSON.stringify(originalObject));
```

⚪ With Lodash: Копира всичко включително функциите.
```
import _ from 'lodash';
const deepCopy = _.cloneDeep(originalObj);
```

# ✅**Array:**

Масивът (array) е структура от данни, която се използва за съхранение на последователност от елементи. Елементите в масива могат да бъдат от всякакъв тип данни, включително числа, обекти и други масиви. Масивите в JavaScript са динамични, т.е. дължината им може да се променя по време на изпълнение.Данните могат да бъдат достъпени от техния индекс.


# ✅**Scope:**

Пространстворо където дадена променлива е видима и достъпна.

**Видове:**

а) Глобални.

б) Локални (functional and block scope).

⚫Lexical scope? 
 
 Скоупа в който променлива е дефинирана и до който има достъп.

# ✅**Closure**
Функция дефинирана в друга функция. Вътрешната функция има доступ до скоупа на външната функция. Те позволяват създаването на privite variables във скоупа, който не могат да бъдат достъпени отвън.


# ✅**expression and Statemant**

- ### Expression: 

Код който връща стойност.


````
1 + 2;
"Hello, world!";
true;

````

- ### Statemant:
Единица от код, която извършва действие
````
x = 10;
console.log("Hello, world!");
const person = { name: "John Doe" };
````
*Основната разлика между expression и statement е, че expression винаги връща стойност, докато statement не винаги. Например, изразът 1 + 2 връща стойността 3, докато изявлението x = 10 не връща стойност.*
# ✅**Imperative and Declarative programming:**
- ### Imperative: 

С императивния код даваме точни указания на компютъра какви действия да предприеме, за да изпълни задача.
- ### Declarative:
Декларативният код описва какво трябва да се постигне, без да се определя как да се постигне. Ползват се методи.



# ✅**Try-catch blocks:**

try-catch блокът  ви позволява да обработвате потенциални грешки или изключения, които могат да възникнат по време на изпълнението на програмата. Чрез try-catch блокът предотвратяваме неочаквано прекъсване на програмата при грешка.

```
try {
  // Код, който искате да изпълните
} catch (error) {
  console.error("Хвърлен exception:", error.message);
} finally {
  // По избор: Изпълнение на задачи за почистване
}
```


*Throwing exception*:
```
throw new Error('Error message');
```

# ✅**Exceptions:**
Когато нашия код срещне някакъв пробем exception бива хврърлен от JS за да пакаже къде е проблема.
Ексепшъните не са предвидени да бъдат видяни от крайния потребител.
Можем да дефинираме Ексепшъните както желаем.

# ✅**ЕCMAScript**

ЕCMAScript е стандарт. Представлява набор от правила кйто JS трябва да следва.

# ✅**Node.js**

Node.js е runtime environment(среда за изпълнение на JS код извън браузура).Той е основаван на V8 JavaScript Engine на Google.

Node.js е асинхронна среда за изпълнение, което означава, че тя може да обработва множество заявки едновременно без да блокира изпълнението на кода. Това я прави подходяща за създаване на приложения, които трябва да обработват голям брой заявки, като например уеб сървъри, чат приложения и приложения за обработка на данни.

# ✅**NPM**

NPM (Node Package Manager) е мениджър на пакети за Node.js.
Пакетите за Node.js са модули, които съдържат код, който може да бъде използван от други програми. Те могат да бъдат написани на JavaScript, TypeScript, C, C++ или други езици.

### ⚫**What is the package.json file?**

Този файл съдържа основна информация за проекта, като име, версия, автор, лиценз и други важни настройки. Всъщност, package.json е JSON форматиран конфигурационен файл.

1.name: Името на проекта.

2.version: Версия на проекта, която се увеличава, когато се правят промени в кода.

3.description: Кратко описание на проекта.

4.main: Основен файл или модул на проекта.

5.scripts: Обект, който дефинира команди, които могат да се изпълняват с помощта на npm. Например, npm start или npm test.

6.dependencies: Зависимости, които са необходими за стартиране на проекта. Когато използвате npm install, тези зависимости се инсталират в проекта.

7.devDependencies: Зависимости, които са необходими само по време на разработка. Те не се инсталират при използване на проекта в продукционна среда.

8.author: Автор на проекта.

9.license: Лиценз, под който е разпространяван проектът.

10.repository: Информация за хранилището на кода (URL към система за управление на версиите).

# ✅**What are ES Modules?**


ES модулите са нов модулен систем за JavaScript. ES модулите осигуряват по-структуриран и организиран начин за импортиране и експортиране на код от различни файлове.

Основни характеристики на ES модулите:

1-   Импортиране и експортиране: ES модулите ви позволяват да импортирате код от други модули и да експортирате код от вашите собствени модули.

2-Лено зареждане: ES модулите могат да се зареждат лено, което означава, че те не се зареждат, докато не са действително необходими.

3-Имена пространства: ES модулите осигуряват начин за създаване на имена пространства за вашия код.
# ✅**Hoisting:**


Декларациите на променливи и функции се преместват най-отгоре на техния scope по време на компилация, преди изпълнението на кода. 

*Вдига се:*  
*Декларации на променливи (с използване на var, let или const).
Декларации на функции.  
Не се вдига:  
Инициализации на променливи (само декларацията се вдига).
Декларации на let и const се вдигат, но не се инициализират до тяхната фактическа декларация в кода.*

⚫Temporal Dead Zone - TDZ: 

 Това е период в кода, където променливата съществува, но не може да бъде достъпвана.


# ✅"**Use strict**"

Задаване на по-строг режим на кода. Когато "use strict" е добавено в началото на скрипта или на функция, JavaScript интерпретаторът превключва в строг режим.

Строгият режим предоставя по-строги правила за писане на код и предпазва от някои обичайни грешки.

# ✅**Git**


Git е система за управление на версиите. Тя позволява на разработчиците да проследяват промените в кода на проекта, да сътрудничат и да управляват различни версии на своя софтуер. Git поддържа ефективно разклоняване и сливане на код, което улеснява съвместната работа на различни екипи.

Ето някои от основните понятия в Git:

⚪Репозиторий (Repository): Git репозиторият е мястото, където се съхранява цялата информация за проекта, включително историята на промените.

⚪Комит (Commit): Комитът представлява конкретна промяна в кода. Той включва нови файлове, променени файлове или изтрити файлове. Всеки комит съдържа уникален идентификатор, наречен хаш.

⚪Бранч (Branch): Бранчът е линия на развитие, която съдържа последователност от комити. Той позволява на разработчиците да работят паралелно върху различни функционалности, като по този начин поддържа отделна хронология на промените.

⚪Мердж (Merge): Мерджът е процесът на сливане на промените от един бранч в друг. Това се използва, когато разработчиците завършат работа върху определен бранч и искат да обединят тези промени в друг бранч.


# **🔥🔥🔥 Module 2(OOP) 🔥🔥🔥**

# **✅Classes**
### Класовете предоставят шаблон или форма за създаване на обекти с общи свойства и методи.


**⚫За какво можем да използваме класовете в JavaScript?**

1.Създаване на Обекти: Класовете предоставят удобен начин за създаване на обекти с консистентна структура и поведение.

2.Инкапсулация: Една от основните цели на инкапсулацията е да скрие вътрешните детайли на обекта и да предостави достъп до тях само чрез определени интерфейси (методи или свойства). Така се постига контролиран достъп и модификация на данните в обекта.

3.Наследяване: Класовете в JavaScript поддържат наследяване, позволявайки на един клас да наследи свойства и методи от друг. 


**⚫Static**

Свойства или методи, които принадлежат на самия клас, вместо на инстанции на класа. Те се споделят между всички инстанции на класа и се достъпват чрез името на класа, вместо чрез инстанция. В 

# **✅The 4 principles of OOP?**


Четирите принципа на Обектно-Ориентираното Програмиране (ООП) са:

⚪**Инкапсулация:**

Скрива вътрешните детайли за това как един обект работи и излага само необходимото. Инкапсулацията помага за контролиране на достъпа до състоянието и поведението на обекта.

⚪**Абстракция:**

Абстракцията е процесът на опростяване на сложни системи, като се моделират класове на базата на основните им свойства и поведения.
Позволява на програмистите да се фокусират върху съществените детайли на обекта и да игнорират ненужните сложности.

⚪**Наследяване:**

Наследяването е механизъм, който позволява на нов клас или подклас да наследи свойства и поведение от съществуващ клас. Спомага за повторната употреба на код и установява връзка между класовете, където подкласът може да наследява атрибути и методи от родителския клас, намалявайки излишествата в кода.

⚪**Полиморфизъм:**
