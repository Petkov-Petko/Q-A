# **_Feel free to learn just don't copy🙏_**

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

 var: Function-scoped, hoisted with initialization as undefined, can be redeclared.

 let: Block-scoped, hoisted without initialization (temporal dead zone), cannot be redeclared within the same scope.

const: Block-scoped, hoisted without initialization (temporal dead zone), cannot be redeclared or reassigned, but object properties and array elements can be modified.

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
Изключението е необичайно или ерор, който възниква по време на изпълнение, и javascript предоставя различни изрази за обработка на изключенията, като try-catch-finally и throws statements..

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
### Класовете предоставят шаблон за създаване на обекти с общи свойства и методи.


**⚫За какво можем да използваме класовете в JavaScript?**

1.Създаване на Обекти: Класовете предоставят удобен начин за създаване на обекти с консистентна структура и поведение.

2.Инкапсулация: Една от основните цели на инкапсулацията е да скрие вътрешните детайли на обекта и да предостави достъп до тях само чрез определени интерфейси (методи или свойства). Така се постига контролиран достъп и модификация на данните в обекта.

3.Наследяване: Класовете в JavaScript поддържат наследяване, позволявайки на един клас да наследи свойства и методи от друг. 


**⚫Static**

Свойства или методи, които принадлежат на самия клас, вместо на инстанции на класа. Те се споделят между всички инстанции на класа и се достъпват чрез името на класа, вместо чрез инстанция.

# **✅The 4 principles of OOP?**

⚪**Инкапсулация:**

Скрива вътрешните детайли на обекта и предоставя достъп до тях само чрез определени интерфейси (методи или свойства). Така се постига контролиран достъп и модификации в обекта.

⚪**Абстракция:**

Абстракцията е процесът на опростяване на сложни системи, като се моделират класове на базата на основните им свойства и поведения.
Позволява на програмистите да се фокусират върху съществените детайли на обекта и да игнорират ненужните сложности.

⚪**Наследяване:**

Наследяването е механизъм, който позволява на нов клас или подклас да наследи свойства и поведение от съществуващ клас. Спомага за повторната употреба на код и установява връзка между класовете, където подкласът може да наследява атрибути и методи от родителския клас, намалявайки излишествата в кода.

⚪**Полиморфизъм:**

Полиморфизмът е концепция в обектно-ориентираното програмиране, която позволява една и съща функция да се използва в различни форми.

```
class firstClass {
    add() {
        console.log("First Method")                 
    }
}
class secondClass extends firstClass {
    add() {
        console.log(30 + 40);
    }
}
class thirdClass extends secondClass {
    add() {
        console.log("Last Method")
    }
let ob = new firstClass();
let ob2 = new secondClass();
let ob3 = new thirdClass();
ob.add();
ob2.add();
ob3.add();

    Output:
First Method
70
Last Method
```

# **✅the 'is-a' and 'has-a' relationships**
⚪**IS-A**

Връзката IS-A е наследство. Класовете, които наследяват, са известни като подкласове или дъщерни класове.


⚪**HAS-A**

Връзката HAS-A е композиция.
# *❗Композицията e клас, който съдържа обекти от други класове.*

*Композиция на функции: Композицията на функции се отнася до техниката за създаване на нова функция чрез комбиниране на две или повече функции. При композицията функциите се изпълняват последователно, като изходът от едната функция се подава като вход на следващата функция, като се получава нова функция.*

# **✅Cohesion and Coupling**

⚪**Cohesion**

Степента, до която методите в определен клас или кода във функция са свързани помежду си и работят заедно към обща цел.

Стремим се към strong/ high Cohesion: 
Всеки един клас или функция да си има ясна цел.   

Пример глобалния обект Math


⚪**Coupling**

Колко тясно свързани са отделните компоненти (класове, функции) на нашата апликация.

Стремим се да имаме low cupling.   
Low cupling означава, че модулите са независими и промените в един модул имат малко влияние върху други модули.           
High cupling означава, че модулите са тясно свързани и промените в един модул могат да засегнат други модули.


# **✅ DRY, KISS, and YAGNI**
⚪**DRY (Don't Repeat Yourself):**

⚪**KISS (Keep It Simple, Stupid):**

⚪**YAGNI (You Aren't Gonna Need It):**


# **🔥🔥🔥 DSA (Data Structures and Algorithms) 🔥🔥🔥**


# **✅Algorithm**
### Алгоритъма е начин как да се подходи при решаването на определена задача. Като това са ясни инструкции към компютъра за да може при някакъв input да изкара желания output.

# **✅Algorithmic complexity.**
### Алгоритмичната сложност е мярка за ефективността на алгоритъм, фокусирана върху това как се променя неговата ефективност с нарастването на размера на входните данни. Тя ни показва колко време и ресурси са необходими на алгоритъма, за да изпълни задачата си. Използваме нотацията Big O (O), за да изразим алгоритмичната сложност.

## **Категории:**

![Screenshot 2024-03-02 200914](https://github.com/Petkov-Petko/Q-A/assets/141727561/5e86ac9b-af0c-47fe-83d6-7d187bf7c866)


# **✅Linear data structure(Линейни структури от данни)**
### Организация на данни, в която елементите са подредени в последователна редица. Всеки елемент има връзка само с предходния и следващия си елемент, подобно на верига.


# **✅Видове линейни структури от данни:**

## ⚪ Array List: 
Динамичен масив. Всеки елемент се достъпва с константна сложност със формулата (n + (index * size)). JS прави това вместо нас.

## ⚪ Linked List (Свързан списък): 
Структура от обекти, който имат стойност и референция към следващия обект.

### *Видове:*
1. Singly:
Държи само стойност и референция към следващия.


2. Dubly:
Държи стойност, референция към следващия и предходния.

![1_T6WwNr9LfSE3EzRACaNh7w](https://github.com/Petkov-Petko/Q-A/assets/141727561/4ac683d4-b7ad-436d-b920-c2ed7746f518)

## ⚪ Stack:
LIFO (Last In, First Out) структура от данни, при която последният добавен елемент е първият, който се премахва.

![download](https://github.com/Petkov-Petko/Q-A/assets/141727561/0631605b-31ea-46e2-8af8-db5884aa4022)

## ⚪ Queue (Опашка): 
Описание: FIFO (First In, First Out) структура от данни, при която първият добавен елемент е първият, който се премахва.

![JavaScript-Queue-Illustration](https://github.com/Petkov-Petko/Q-A/assets/141727561/fe55d222-cd10-4df7-9051-167006f6175f)

## **Сравнение:**

![Screenshot 2024-03-15 115607](https://github.com/Petkov-Petko/Q-A/assets/141727561/b8323c31-5713-4275-8c42-5316d0e5ea1e)


# **✅hash table**
### Хеш таблица е структура от данни, която съхранява двойки ключ-стойност. Тя използва техника, наречена хеширане, за да преобразува ключовете в позиции в масив. Хеш таблиците предлагат константна сложност за общите операции като вмъкване, изтриване и търсене.


**⚫Хешираща функция:**

Хеш таблиците използват хешираща функция за преобразуване на ключовете в индекси в масива. Тази функция приема ключ като вход и произвежда хеш код, който е цяло число. Хеш кодът се превръща в индекс в масива.


**⚫Колизия**

Колизиите възникват, когато два или повече ключа произвеждат същия хеш код, което води до същия индекс в масива.

# **✅Set**

### Структура от данни, която съдържа уникални елементи, които не се повтарят. 
Можем да използваме сет за премахване на дубликати от аррей, Намиране на общи елементи между масиви и др.


# **✅Map**

### Структура от данни, която съдържа ключове и стойности. Всеки ключ е уникален и се свързва със специфична стойност. Това позволява бързо търсене на стойности по ключ или добавяне/промяна/изтриване.

Можем да използваме мап за мемоизация, преброяване и др.

# **✅Recursion**

### Когато функция се извиква от самата себе си.


**⚫base case or bottom:**

Рекурсивната функция трябва да има дефиниран базов случай, който служи като крайна точка за изпълнението й. Без базов случай рекурсията ще продължи безкрайно, което може да доведе до изчерпване на стека на извикванията (stack overflow).

**⚫What problems does recursion solve?**

.Проблеми, които включват обхождане на дървовидни структури.Обхождане в дълбочина (DFS), обхождане в ширина (BFS).

.Алгоритми за Разделяне и Владей

**⚫What is backtracking?**

Обратното проследяване е основан на проба-грешка подход за решаване на изчислителни проблеми. Това включва изграждане на последователност от избори и когато се срещне задънена улица, алгоритъмът се връща към предишна точка на вземане на решение и опитва различен път. Това продължава, докато се намери решение или всички пътища бъдат изчерпани.

Примери за използване на backtracking:   
генериране на всички пермутации, намиране на пътища в лабиринт и др.


**⚫What is memoization?**

Ммоизация е техника за ускоряване на изчисленията чрез съхранение и повторна употреба на вече изчислени резултати. Тя включва кеширане на резултатите от извиквания на функции и връщане на кеширания резултат, когато се срещат същите входове отново. Това може значително да подобри производителността на рекурсивни алгоритми, като се избегне излишното изчисление на резултати.


**⚫What is tail recursion?**


Tail recursion е специална форма на рекурсия, при която рекурсивното извикване е последната операция изпълнявана от функцията преди да върне своя резултат. В опашково-рекурсивни функции няма оставащи операции за изпълнение след като рекурсивното извикване върне резултат.


# **✅Binary Tree**

Двоичната дървовидна структура на данни е йерархична структура от данни, в която всеки възел има най-много две деца, наричани ляво дете и дясно дете. Първият възел в дървото се нарича корен.  
Листа: Листата са възли без наследници     
Височина: Височината на двоично дърво е дължината на най-дългия път от корена до някой от листата.

**⚫PostOrder, PreOrder, and InOrder DFS traversal?**

1 PreOrder (предварителен обход):

В началото се посещава коренът на дървото.
След това се обхождат лявото и дясното поддървета рекурсивно в същия ред.
Поредността на обхождане е: корен, ляво поддърво, дясно поддърво.

2 InOrder (централен обход):

Първо се обхожда лявото поддърво на дървото.
След това се посещава коренът.
Накрая се обхожда дясното поддърво.
Поредността на обхождане е: ляво поддърво, корен, дясно поддърво.

3 PostOrder (обратен обход):

Първо се обхождат лявото и дясното поддървета рекурсивно.
След това се посещава коренът.
Поредността на обхождане е: ляво поддърво, дясно поддърво, корен.


# **🔥🔥🔥 Welcome to the Web Development World! 🔥🔥🔥**

# **✅HTML (_HyperText Markup Language_)**

**HTML** структурира съдържанието на уеб страници, като използва различни етикети и елементи, за да дефинира различни видове съдържание. **HTML** предоставя стандартизиран начин за форматиране и организиране на съдържанието, което прави лесно за уеб браузърите да интерпретират и показват уеб страници правилно. 

# **✅What is a browser?**
 
Браузърът е софтуерно приложение, той интерпретира HTML, CSS и JavaScript кода на уеб страниците и ги представя на потребителя във визуален формат. Браузърите обикновено имат и други функционалности като закладки, история на търсенето, управление на пароли и т.н.

Основната разлика между браузъра и Node.js е, че браузърът се използва за изпълнение на JavaScript код вътре в уеб страниците, докато Node.js се използва за изпълнение на JavaScript код извън браузъра, осигурявайки възможност за създаване на сървърни приложения и други средствата за изграждане на софтуер.

# **✅What is URL?**

URL (Uniform Resource Locator) Това е адрес, който идентифицира конкретен уеб ресурс в интернет.

Един URL адрес се състои от няколко части:

1. Протокол (Protocol)
2. Домейн (Domain)
3. Път (Path)
4. Параметри (Parameters)
5. Анкора (Anchor)


Например, в URL адреса "https://www.example.com/page1/page2?key1=value1#section3", 
протоколът е `"https://"`, домейнът е `http://www.example.com/`, пътят е `"/page1/page2"`, параметрите са `"?key1=value1"`, анкората е `"#section3"`.


 # **✅DOM  (Document Object Model)** 

**DOM, HTML и JavaScript работят заедно, за да създадат интерактивни и динамични уеб сайтове и приложения.**

HTML документът е основата на уеб страницата и дефинира нейната структура и съдържание. DOM представя този HTML документ като дървовидна структура от обекти, като всеки HTML елемент се представя като обект в дървото.

JavaScript се използва за манипулиране на DOM структурата. Той може да създава, премахва и променя HTML елементи и техните атрибути, стилове и съдържание. Това позволява на уеб разработчиците да създават динамични уеб приложения, които реагират на действията на потребителя и променям съдържанието на уеб страницата без да се налага презареждане на цялата страница.

# **✅document && window objects**

1. **⚪Обект на документа (document):**

 Обектът document представлява целия HTML документ и предоставя методи и свойства за взаимодействие със съдържанието на документа.
Той служи като входна точка за достъп и манипулиране на елементи, атрибути и съдържание в HTML документа.
  
_Разработчиците могат да използват обекта document за:_
- Достъп и модификация на HTML елементи и техните атрибути.
- Създаване, премахване или манипулиране на елементи динамично.
- Обработка на събития като кликвания, натискания на клавиши и подавания на форми.
- Търсене на документа за конкретни елементи с помощта на селектори като getElementById, getElementsByClassName, querySelector и querySelectorAll.
2.  **⚪Обект на прозореца (window):**

Обектът window представлява браузърското прозорец или раздел в който се показва уеб страницата.
Обектът window обхваща целия браузърски контекст и съдържа свойства и методи, свързани с навигацията, местоположението, историята, времето и други.

_Разработчиците могат да използват обекта window за:_
- Контрол на поведението на браузъра, като отваряне на нови прозорци или раздели (window.open), преоразмеряване на прозорци (window.resizeTo) или навигиране към нови URL адреси (window.location).
- Достъп до информация за браузърската среда, като размера на екрана на потребителя (window.screen), размерите на прегледа (window.innerWidth и window.innerHeight) или низа с информация за браузъра (window.navigator).
- Обработка на събития, свързани с браузърския прозорец или раздел, като onload, onunload, onresize и onbeforeunload.

# **✅What are events?**

Събития могат да бъдат предизвикани от различни източници, като интеракции на потребителя (щракване върху бутон или писане на клавиатурата), промени в документа (като зареждането на страница или промяната на елемент) или системни събития (като изтичане на таймер или завършване на мрежова заявка).
Когато се случи събитие, браузърът обикновено създава обект на събитие, който съдържа информация за събитието (като типа му, целевия елемент и всякакви допълнителни данни, свързани с него).

# **✅Event bubbling and event capturing**

_Разликата между тях се състои в реда, в който събитието се обработва в йерархията на DOM - от най-външния към най-вътрешния (заснемане) или от най-вътрешния към най-външния (възходящо разпространение)._

1. Event Capturing:

- В тази фаза събитието се обработва от най-външния (най-горния) елемент към най-вътрешния (най-долните) елементи в йерархията на DOM.

3. Event Bubbling:

- В тази фаза събитието се обработва от целевия елемент към най-външния (най-горния) елемент в йерархията на DOM.


# **✅❗DOM API**

_Document Object Model Application Programming Interface_  е набор от стандартизирани методи и свойства, които позволяват манипулиране на структурата, съдържанието и стила на HTML и XML документи. 


# **🔥🔥🔥 Asynchronous Programming 🔥🔥🔥**

# ✅What is asynchronous programming? 

_Асинхронното програмиране е начин за изпълнение на задачи в програма, където определени операции се изпълняват асинхронно, т.е. нечакането на завършването на една операция, преди да се премине към следващата. Това се постига чрез използване на концепции като обратно извикване (callbacks), промиси (promises) или async/await._

# ✅What is the difference between callbacks and promises? 
_Чрез Promises се осигурява по-структуриран и лесно разбираем начин за управление на асинхронни операции, като се намалява „callback hell“ и се улеснява откриването и обработката на грешки._

1. Callbacks (Обратни повиквания):

- Функцията се предава като аргумент на друга функция. Тази функция (callback) се извиква по завършване на асинхронната операция.
- Callback функциите често водят до „callback hell“ (индентиране и смесване на вложени callback функции), което затруднява разбирането и поддръжката на кода.

2.Promises (Обещания):

- Обещанията са по-нов подход, който позволява по-лесно управление на асинхронни операции. Те представляват обект, който се предлага да изпълни определена операция и да върне резултат, когато е готов.
- Promises предоставят методи като .then(), които позволяват дефинирането на код, който да се изпълни след успешното завършване на операцията, както и .catch(), за обработка на грешки.
- Promises могат да бъдат чейнати, което прави кода по-четим и по-лесен за поддръжка.


# **✅Event loop**

Event loop-ът е механизъм, използван от JavaScript за управление на асинхронни операции и осигуряване на неблокиращо изпълнение на кода. Главната му отговорност е да следи за събития (events) и да управлява изпълнението на кода.
![Javascript-event-loop](https://github.com/Petkov-Petko/Q-A/assets/141727561/fd3192f0-b1e2-4e8b-bd81-687d0e415d97)

# **✅Async & Await**

 
`async и await` се използват в JavaScript, за да се управляват асинхронните операции по-ефективно, като правят асинхронния код да изглежда и се държи като синхронен код.

1.Аsync:
 Когато декларирате функция с ключовата дума **async**, това означава, че функцията винаги ще връща обещание (promise). Това ви позволява да използвате ключовата дума await вътре във функцията, за да спрете изпълнението й, докато обещанието не бъде изпълнено (резолвирано или отхвърлено)

2.Аwait:
 Ключовата дума **await** се използва вътре в async функция, за да спре изпълнението на функцията, докато обещанието, подадено на нея, не бъде изпълнено. Това ви позволява да пишете асинхронен код, който изглежда синхронен.


 # **🔥🔥🔥 HTTP / AJAX 🔥🔥🔥**

_HTTP, или Хипертекстовият протокол за пренос, е основата за комуникация в световната мрежа. Това е протокол на приложното ниво, който позволява на уеб браузърите и уеб сървърите да комуникират и разменят данни през интернет. HTTP е протокол от типа заявка-отговор, където клиентът изпраща заявка до сървъра, и сървърът отговаря с исканата информация._

# ✅What is HTTP? How does it work? 

Клиентът изпраща заявки до сървъра, който отговаря с исканата информация. Заявките включват методи като GET и POST, а отговорите съдържат статусни кодове, указващи успешността на операцията. Комуникацията се осъществява чрез URL адреси и заглавия.

# **✅ HTTP methods, headers and status codes**

-  Методите на HTTP определят типа на заявката, която се изпраща до сървъра, като например GET, POST, PUT, DELETE и други.   
- Заглавията на HTTP съдържат метаинформация за заявката или отговора, като например Content-Type, User-Agent и други. 
-  Статусните кодове се използват за да се покаже резултатът от заявката, като например 200 за успешно завършена заявка, 404 за липсващ ресурс и други.

# **✅ What is the request body**

Тялото на заявката (request body) е данните, които се изпращат към сървъра като част от HTTP заявката. Това е често използвано при POST или PUT заявките. Примери за данни в тялото на заявката могат да бъдат JSON обекти, XML данни или формуляри.


# **✅ AJAX**

AJAX означава Асинхронен JavaScript и XML. Това е набор от техники за уеб разработка, които се използват за създаване на асинхронни уеб приложения. С AJAX уеб страници могат да изпращат и извличат данни от сървъра асинхронно, без да пречат на показването и поведението на съществуващата страница. Това позволява по-плавно и по-отзивчиво потребителско изживяване, тъй като съдържанието може да се актуализира динамично, без да се изисква пълното презареждане на цялата страница.

# **🔥🔥🔥 React  🔥🔥🔥** 

_React.js е библиотека за създаване на потребителски интерфейси в уеб приложения. Тя е разработена от Facebook и се използва за създаване на динамични, интерактивни и ефективни уеб приложения. Една от ключовите характеристики на React.js е компонентният подход към създаването на интерфейси._

# **✅React component**

В React, компонентът е основната строителна единица за създаване на потребителски интерфейси. Той представлява изолирана и многократно използваема част от интерфейса, която може да съдържа HTML елементи, други компоненти и логика за визуализация и поведение.

# **✅What is JSX?**

