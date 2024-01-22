
#  ***Everything you need:*** 

#### All answers to your questions. ✔️


# **✅What is JavaScript?**
### JavaScript (JS) е интерпретиран, многопарадигмен, слабо типизиран език за програмиране, който се използва предимно за уеб разработка. Въведен е от Netscape през 1995 г.

- ### Многопарадигмен: 
   JavaScript поддържа функционално и обектно-ориентирано. Това го прави многопарадигмен език.

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

# **functions:**
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

# **Objects**
   Структура от данни от референтен тип.
   Те се състоят от ключ и стойност (Key and Value);
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
