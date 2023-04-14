# План подготовки к собеседованию

## Просмотр видео-собеседование

вебдев [веб-дев](https://www.youtube.com/watch?v=ycYp7CYOnO0&list=PLNkWIWHIRwMFSLI9wBuHxuGI5lAZ7QNUg&index=3).  
hr-позвонит [hr-позвонит](https://www.youtube.com/results?search_query=hr+%D0%BF%D0%BE%D0%B7%D0%B2%D0%BE%D0%BD%D0%B8%D1%82)  
Подготовка к собеседованию по JavaScript в
2021.[Подготовка к собеседованию по JavaScript в 2021.](https://www.youtube.com/watch?v=H5wnkRJBfA8).

## Сайты тренажеры

[js-тренажор](https://github.com/lydiahallie/javascript-questions).
[Набор задач](https://bigfrontend.dev/)
[Набор алгосов по js](https://leetcode.com/problemset/javascript/)

## Решение задач/практика

codewars
freecodecamp // ES6,  
Regular Expressions/  
Debugging/  
Basic Data Structures/  
Basic Algorithm Scripting/  
Object Oriented Programming/
Functional Programming/  
Intermediate Algorithm Scripting/  
JavaScript Algorithms and Data Structures Projects

## Книги

YDKJS - get started v2 на русском  
YDKJS - scopes and closures   
YDKJS - про приведение типов

## Статьи

[Ликбез из тачилы ](https://www.youtube.com/playlist?list=PLcvhF2Wqh7DMGR08yA6oNKJ7WCM0tGd4z)  
[Собес Дена Абрамова](https://www.youtube.com/watch?v=XEt09iK8IXs&t=647s)  
[Как работает JavaScript: массивы и хэш-таблицы](https://nuancesprog.ru/p/14613/)  
[Front-end. Вопросы на собеседовании](https://github.com/YauhenKavalchuk/interview-questions)
[300+ ВОПРОСОВ ПО JAVASCRIPT НА СОБЕСЕДОВАНИИ](https://itvdn.com/ru/blog/article/300-js)    
[70 ВОПРОСОВ ПО JAVASCRIPT НА СОБЕСЕДОВАНИИ](https://habr.com/ru/post/486820/)    
[35 ВОПРОСОВ ПО JAVASCRIPT НА СОБЕСЕДОВАНИИ](https://habr.com/ru/post/578370/)    
[Яндекс-фронтенд](https://www.youtube.com/c/%D0%A4%D1%80%D0%BE%D0%BD%D1%82%D0%B5%D0%BD%D0%B4/videos)    
[33 Concepts Every JavaScript Developer Should Know](https://github.com/leonardomso/33-js-concepts).

1) [Как парсит браузер](https://webdevblog.ru/kak-brauzer-renderit-veb-stranicu/)  , [вторая статья как работает браузер](https://habr.com/ru/post/484900/)
2) Вопросы по css
3) [Прото и прототипы](https://www.youtube.com/watch?v=b55hiUlhAzI&list=RDCMUCTW0FUhT0m-Bqg2trTbSs0g&start_radio=1&t=3s)
4) Конструктор и this.
5) [SOLID](https://www.youtube.com/watch?v=WMO9aarO390&list=PLz_dGYmQRrr8rWKkoB3BtxF7JpCzUKny_)
6) http/https
7) crud + хедеры
8) Оптимизации + кеши
9) Более подробно евентлуп
10) DNS
11) [Паттерны](https://www.youtube.com/watch?v=bTiAfLbmsnY&t=3s)
12) [Preload,Preconnect,Prefetch](https://nitropack.io/blog/post/resource-hints-performance-optimization)

## Алгосы

[grind75](https://www.techinterviewhandbook.org/grind75)
[Качаем литкод](https://www.linkedin.com/feed/update/urn:li:activity:7001142282578010112/)

# Собеседование

**5 минут** Приветствие, small talk, план собеседования

- Предупредить, что буду делать записи
- Могу прервать, если не будет хватать времени

**10 минут** Расскажите о себе ()

- о своем опыте
- об ожиданиях и желаемой роли, 
- самая сложная задача или серьезный факап  
- что изучили за последнее время 

**15 минут** Live coding

**15 минут**  Теория по JS, TS

**15 минут**  Frameworks - React / State managers / CSS in JS / Webpack / Mfe

**20 минут**  ООП, дизайн принципы и паттерны, Rest, GraphQL, способы интеграции, тестирование, troubleshooting, CI/CD,
leadership

**5 минут** Церемонии в скрам, как проходит эстимация + ретроспектива от кандидата

**5 минут** Вопросы от кандидата

### Задачи на собес

#### Проверка на палиндром

A palindrome is a word, phrase, number, or other sequence of characters which reads the same backward as forward.
Examples of numerical palindromes are:   
2332  
110011   
54322345   
For a given number num, write a function to test if it's a numerical palindrome or not and return a boolean (true if it
is and false if not).
Return "Not valid" if the input is not an integer or less than 0.

```js
const palindrome = 110011
const noPalindrome = 543212345

function isPalindrome(num) {

}
```

//Решение

```js
function palindrome(num) {
    if (typeof num !== 'number' || num < 0) return 'Not valid'
    return String(num).split('').reverse().join('') === String(num)
}
```

#### Проверка на наличие дубликатов

Given an integer array nums, return true if any value appears at least twice in the array, and return false if every
element is distinct.

```js
const nums = [1, 2, 3, 1]
var containsDuplicate = function (nums) {

};
```

//Решение

```js
const containsDuplicate = (nums) => {
    return new Set(nums).size !== nums.length
};
```

## React задачи

[Среднее время](https://codesandbox.io/s/stupefied-cache-sepkql).    
[Получение данных](https://codesandbox.io/s/eager-gianmarco-xdvo9h)

### JS + TS

Какие существуют типы данных в JS?
JS имеет следующие типы данных: числа (number), строки (string), логические значения (boolean), объекты (object), массивы (array), null и undefined.

Как проверить, является ли объект массивом?
Можно использовать метод Array.isArray(obj), который вернет true, если объект является массивом, и false в противном случае.

Сравните ключевые слова var, let, const.
var - объявление переменных, имеет область видимости функции или глобальной области видимости.
let - объявление переменных, имеет блочную область видимости и не может быть переопределена в рамках одного блока.
const - объявление констант, имеет блочную область видимости и не может быть переопределена.

Что такое деструктуризация?
Деструктуризация - это способ извлечения значений из объектов и массивов и присваивания их переменным.

Чем JS отличается при работе на front-end и back-end?
JS на front-end используется для написания скриптов на стороне клиента (например, для работы с DOM, обработки событий и валидации данных), а на back-end - для написания серверных приложений и API.

Для чего предназначены методы setTimeout и setInterval, есть ли они в JS?
Методы setTimeout и setInterval используются для выполнения заданного кода через определенный интервал времени. setTimeout вызывает функцию один раз, а setInterval вызывает ее многократно. Да, эти методы есть в JS.

Сравните подходы работы с асинхронным кодом: callbacks vs promises vs async / await.
Callback - функция, которая вызывается после выполнения асинхронной операции.
Promise - объект, который представляет результат асинхронной операции и может иметь три состояния: ожидание (pending), выполнено успешно (resolved) и выполнено с ошибкой (rejected).
Async/await - специальный синтаксис, который позволяет писать асинхронный код в синхронном стиле.

Назовите методы массивов, какие помните, и скажите, для чего они нужны.
Методы массивов:

push - добавляет элемент в конец массива.
pop - удаляет последний элемент массива.
shift - удаляет первый элемент массива.
unshift - добавляет элемент в начало массива.
splice - изменяет содержимое массива, удаляя или заменяя существующие элементы.
slice - возвращает новый массив, содержащий копию части исходного массива.
Опишите назначение и принципы работы с коллекциями Map и Set.

Map и Set - это две встроенные коллекции в JavaScript, которые позволяют хранить уникальные значения и быстро их искать.

Set - это коллекция уникальных значений, где каждое значение может встречаться только один раз. Set может содержать любые значения, включая примитивы и объекты. Для добавления элемента в Set используется метод add, для удаления элемента - метод delete. Также в Set есть метод has, который проверяет, содержится ли элемент в коллекции.

Map - это коллекция ключ-значение, где каждое значение связано с уникальным ключом. Ключ может быть любым значением, включая примитивы и объекты. Для добавления элемента в Map используется метод set, для удаления элемента - метод delete. Также в Map есть метод get, который возвращает значение по ключу, и метод has, который проверяет, содержится ли ключ в коллекции.

Глубокая (deep) и поверхностная (shallow) копия объекта - это два разных способа создания копии объекта. Поверхностная копия объекта создает новый объект, который содержит ссылки на те же объекты, что и исходный объект. Глубокая копия создает новый объект и рекурсивно копирует все вложенные объекты.

Для создания поверхностной копии объекта можно использовать методы Object.assign или spread оператор (...). Например:

javascript
Copy code
const obj1 = { a: 1, b: { c: 2 } };
const obj2 = Object.assign({}, obj1);
const obj3 = { ...obj1 };
Для создания глубокой копии объекта можно использовать метод JSON.stringify в сочетании с JSON.parse или использовать библиотеку Lodash. Например:

javascript
Copy code
const obj1 = { a: 1, b: { c: 2 } };
const obj2 = JSON.parse(JSON.stringify(obj1));
const obj3 = _.cloneDeep(obj1);
Какая разница между декларацией функции (function declaration) и функциональным выражением (function expression)? Что такое анонимная функция?

Функция может быть объявлена двумя способами: как функциональное выражение (function expression) или как декларация функции (function declaration).

Function Declaration (декларация функции) - это объявление функции в основном потоке кода. Она начинается с ключевого слова function, за которым следует имя функции и список параметров в круглых скобках. Функция может быть вызвана до её определения.

javascript
Copy code
function sum(a, b) {
  return a + b;
}
Декларация функции (function declaration) - это объявление функции в коде, которое начинается со слова "function", за которым следует имя функции, а затем круглые скобки с параметрами функции и тело функции в фигурных скобках. Функция, объявленная таким образом, доступна во всем блоке кода и может вызываться в любом месте программы.

Функциональное выражение (function expression) - это создание функции как объекта в контексте какого-то выражения. Оно начинается со слова "function", за которым следует необязательное имя функции (в этом случае функция называется именованной функцией), затем круглые скобки с параметрами функции и тело функции в фигурных скобках. Функция, объявленная как выражение, не будет доступна до тех пор, пока выражение не будет выполнено.

Анонимная функция - это функция, которой не задано имя при объявлении. Вместо имени она обычно используется в качестве параметра другой функции или присваивается переменной.

Стрелочные функции (arrow functions) - это сокращенный синтаксис функционального выражения, который использует стрелку (=>) вместо ключевого слова "function". Они обычно используются для создания кратких, однострочных функций.

Отличия стрелочных функций от обычных:

В стрелочных функциях отсутствует собственный контекст выполнения (this) и они используют контекст родительской функции.
Стрелочные функции не имеют своих собственных объектов arguments, но они могут получать доступ к аргументам родительской функции.
Стрелочные функции не могут быть использованы для создания конструкторов.
IIFE (Immediately Invoked Function Expression) - это функция, которая объявляется и немедленно вызывается в том же выражении. Она используется для создания локальной области видимости и избежания конфликтов имен переменных в глобальной области видимости. Пример:

Hoisting - это механизм в JavaScript, который перемещает объявления переменных и функций вверх в текущей области видимости перед выполнением кода. Переменные, объявленные с помощью ключевого слова var, будут подняты в начало области видимости, но значения не будут определены. Функции, объявленные с помощью ключевого слова function, будут подняты в начало области видимости и могут быть вызваны до объявления.

Замыкание (closure) - это функция, которая запоминает значения переменных внешней функции, даже после того, как внешняя функция завершена. Таким образом, замыкание имеет доступ к переменным внешней функции, даже если они были объявлены в другой области видимости. Замыкания могут быть использованы для создания частных переменных и методов, которые не могут быть доступны извне.

Пример замыкания:

scss
Copy code
function createCounter() {
  let count = 0;
  return function() {
    count++;
    console.log(count);
  }
}

const counter = createCounter();
counter(); // 1
counter(); // 2
В этом примере функция createCounter возвращает другую функцию, которая имеет доступ к переменной count внешней функции createCounter. Таким образом, переменная count сохраняет свое значение между вызовами функции counter.

Замыкания могут быть использованы для создания модульной структуры кода, кэширования данных, обеспечения безопасности данных и решения других задач.

Как я понимаю замыкания: замыкание - это функция, которая имеет доступ к переменным внешней функции, даже после того, как внешняя функция завершила свое выполнение. Замыкание сохраняет значения переменных внешней функции и использует их при вызове.

Рекурсия - это процесс, в котором функция вызывает саму себя. Рекурсия может использоваться для решения задач, которые могут быть разбиты на более простые подзадачи. Она может быть использована для обхода иерархических структур данных, поиска путей в графах и других задач. Важно, чтобы рекурсивная функция имела базовый случай, который завершает рекурсивный процесс, чтобы избежать бесконечного цикла.
Ключевое слово this в JavaScript относится к текущему объекту, в контексте которого вызывается функция. Значение this определяется в момент вызова функции и может изменяться в зависимости от контекста вызова.

Потеря контекста происходит, когда значение this не указывает на ожидаемый объект, что может привести к ошибкам в коде. Это происходит, когда функция вызывается в глобальной области видимости или в контексте другого объекта. Например, если объект person имеет метод sayName, и этот метод передается в качестве параметра другой функции, контекст this потеряется.

Для предотвращения потери контекста можно использовать метод bind, который создает новую функцию с указанным контекстом this, а также может привязывать аргументы функции. Методы call и apply могут использоваться для вызова функции с указанным контекстом this и передачей аргументов в виде списка или массива соответственно.

Метод bind:

javascript
Copy code
const person = {
  name: 'John',
  sayName() {
    console.log(this.name);
  }
};

const sayName = person.sayName.bind(person);
sayName(); // 'John'
Метод call:

javascript
Copy code
const person = {
  name: 'John',
  sayName() {
    console.log(this.name);
  }
};

person.sayName.call({ name: 'Jane' }); // 'Jane'
Метод apply:

javascript
Copy code
const person = {
  name: 'John',
  sayName() {
    console.log(this.name);
  }
};

person.sayName.apply({ name: 'Jane' }); // 'Jane'
Разница между методами call и apply заключается в способе передачи аргументов. Call принимает аргументы в виде списка, а apply принимает аргументы в виде массива.
Garbage Collector (сборщик мусора) - это механизм, который автоматически освобождает память, занимаемую объектами, которые больше не используются в программе. Сборщик мусора отслеживает ссылки на объекты в программе и удаляет объекты, на которые не осталось ссылок. Это позволяет избежать утечек памяти и повышает безопасность программы.

Promise - это объект, который представляет результат асинхронной операции и может находиться в одном из трех состояний: ожидание (pending), выполнено успешно (fulfilled) или выполнено с ошибкой (rejected). Promise позволяет выполнять асинхронные операции и обрабатывать результаты этих операций в удобной форме.

При последовательном выполнении асинхронных функций каждая функция выполняется только после того, как предыдущая функция завершится. Это может быть полезно, например, если результат выполнения одной функции нужен для выполнения следующей функции.

Пример последовательного выполнения асинхронных функций с помощью Promise:

javascript
Copy code
async function fetchData(url) {
  const response = await fetch(url);
  const data = await response.json();
  return data;
}

fetchData('https://api.example.com/data1')
  .then((data1) => {
    return fetchData('https://api.example.com/data2');
  })
  .then((data2) => {
    console.log(data2);
  })
  .catch((error) => {
    console.error(error);
  });
При параллельном выполнении асинхронных функций несколько функций выполняются одновременно, без ожидания завершения друг друга. Это может ускорить выполнение программы, если функции независимы друг от друга и могут выполняться параллельно.

Пример параллельного выполнения асинхронных функций с помощью Promise.all:

javascript
Copy code
async function fetchData(url) {
  const response = await fetch(url);
  const data = await response.json();
  return data;
}

Promise.all([
  fetchData('https://api.example.com/data1'),
  fetchData('https://api.example.com/data2'),
])
  .then(([data1, data2]) => {
    console.log(data1, data2);
  })
  .catch((error) => {
    console.error(error);
  });
Метод Promise.all принимает массив Promise и возвращает новый Promise, который будет выполнен, когда все Promise из массива будут выполнены. В результате будет массив со значениями, возвращаемыми каждым Promise. Если хотя бы один Promise из массива завершится с ошибкой, возвращаемый Promise также завершится с ошибкой.

Преимущества генераторов:

Управление потоком выполнения: генераторы позволяют остановить выполнение функции на определенном моменте, сохранить ее состояние и вернуть значение. Позже, выполнение функции может быть возобновлено с того места, где оно остановилось.

Ленивый расчет: генераторы позволяют генерировать значения по мере необходимости, вместо того, чтобы генерировать все значения сразу. Это может быть полезно, например, когда мы работаем с большими объемами данных.

Асинхронность: генераторы могут быть использованы для реализации асинхронных операций.

Чистая функция - это функция, которая возвращает результат, зависящий только от ее входных параметров и не имеет побочных эффектов, то есть не изменяет состояние программы или делает какие-то другие действия, кроме вычисления результата. Чистые функции могут быть проще для понимания, тестирования и оптимизации.

Пример чистой функции на JavaScript:

css
Copy code
function sum(a, b) {
  return a + b;
}
Event Loop (евент-петля) - это механизм, используемый JavaScript для управления асинхронным выполнением кода. Все задачи, которые должны быть выполнены, помещаются в очередь. Event Loop занимается обработкой этой очереди и выполняет задачи в порядке их поступления. Если задача занимает слишком много времени, она может блокировать выполнение других задач, поэтому важно писать код так, чтобы он не блокировал Event Loop. Один из способов решения этой проблемы - использование асинхронных функций и колбэков.

RAF - это сокращение от "requestAnimationFrame". Это метод, который браузер использует для планирования анимаций и обновления экрана. Он предлагает более плавное и эффективное обновление экрана, чем другие методы, такие как setTimeout или setInterval. Он также автоматически учитывает многие важные факторы, такие как энергосбережение и уменьшение нагрузки на процессор.

Прототип в JavaScript - это механизм наследования, который позволяет объектам наследовать свойства и методы других объектов. Каждый объект имеет свойство прототипа (proto), которое ссылается на другой объект. Если свойство или метод не найден в объекте, JavaScript ищет его в его прототипе. Если свойство не найдено в прототипе, поиск продолжается в прототипе его прототипа и так далее, пока не будет найдено свойство или не будет достигнут конец цепочки прототипов (Object.prototype).

Прототипы в JavaScript являются ключевым механизмом наследования в языке. Они позволяют создавать объекты, которые наследуют свойства и методы других объектов, что упрощает их создание и поддержку.

Generics - это механизм, который позволяет создавать функции и классы, которые работают с разными типами данных. Они позволяют создавать обобщенный код, который может работать с различными типами данных, не определяя эти типы заранее. Generics используются для создания более гибкого, переиспользуемого и безопасного кода.

Разница между any и unknown заключается в том, что any позволяет присваивать переменной любое значение, без проверки типа. В то время как unknown - это более безопасный тип, который используется для переменных, значение которых неизвестно. При работе с типом unknown требуется проверка типа, прежде чем использовать значение переменной.

Type guard - это механизм, который позволяет проверять тип данных в TypeScript и позволяет изменять тип переменной в зависимости от проверки. Type guard используется для проверки типа переменной во время выполнения программы. Это позволяет программистам создавать более гибкий код и предотвращать ошибки типа во время выполнения программы. Type guard можно использовать в различных ситуациях, например, при работе с условными операторами и циклами, при проверке типа аргументов функций и т.д.

Ключевое слово interface в TypeScript используется для определения формата объекта. Интерфейсы могут определять свойства, методы и индексные типы, но они не могут определять типы объединения (union) или пересечения (intersection).

Ключевое слово type в TypeScript используется для создания пользовательских типов данных. Типы могут определяться как простые типы, так и сложные типы данных, такие как объекты, объединения и пересечения.

Utility типы - это вспомогательные типы в TypeScript, которые предоставляют множество полезных функций для работы с типами данных. Некоторые из самых часто используемых Utility типов включают в себя:

Partial<T> - создает тип, который делает все свойства объекта необязательными.
Readonly<T> - создает тип, который делает все свойства объекта доступными только для чтения.
Record<K, T> - создает тип, который определяет объект с ключами типа K и значениями типа T.
Pick<T, K> - создает тип, который выбирает только определенные свойства из объекта T на основе типов K.
Omit<T, K> - создает тип, который удаляет определенные свойства из объекта T на основе типов K.


### React / State manager

- Ознакомлены ли вы с хуками? В чем их преимущества? Приходилось ли делать свои и с какой целью?
- Знакомы ли вы с фрагментами и порталами? Зачем они нужны?
- Когда и для чего используют рефы?
- В чем разница useRef и useState?
- Какие вы знаете методы жизненного цикла компонента?
- В каком методе жизненного цикла компонента лучше делать запросы на сервер? Почему?
- В каком методе жизненного цикла компонента лучше делать подписку и отписку от листенера? Почему? Зачем отписываться?
- Был ли опыт работы с контекстом? Когда его стоит использовать
- В чем особенность PureComponent?
- В чем видите преимущества библиотеки React?
- Что такое Virtual DOM и Shadow DOM?
- Зачем в списках ключи? Можно ли делать ключами индексы элементов массива? Когда это оправдано?
- Приходилось ли вам настраивать проект React с нуля? С помощью каких инструментов вы это делали?
- Что самое сложное вам приходилось реализовывать с помощью React?

### Common

- Как обрабатываются ошибки? В каком случае можно перезаписать return в функции?
- Какие методики отпимизации приложения и метрики вы знаете?
- Что вы знаете про доступность?
- Как клиент взаимодействует с сервером? - socket/rest/graphql/sse/long poling 
- Что значит HTTP?
- Какие методы HTTP-запросов вы знаете?
- Какая разница HTTP vs HTTPS?
- Какие знаете коды ответа (состояния) HTTP?
- Что такое CORS?
- Что такое cookie?
- Что такое REST?
- Объяснить понятие мутабельность/иммутабельность? Какие типы являются мутабельными и наоборот?
- Как искать ошибки в коде? Используете ли вы дебаггер?
- Назовите способы хранения данных в браузере.
- Какие паттерны знаете и используете в работе?
- Что такое ci/cd
- Для чего нужен package-lock.json?
- Можете ли вы описать суть методологии git flow/Trunk Based в двух словах?
- SOLID
- WebWorkers
- ServiceWorkers
- SSR/SSG/CSR/SPA/PWA
- Что такое микросервисы?
- Что знаете про тестирование? Какие типы тестов есть? Что такое пирамида тестирования? Как и что тестируете?   
  Подходы: {
    - TDD -это методология разработки ПО, которая основывается на повторении коротких циклов разработки:
      изначально пишется тест, покрывающий желаемое изменение, затем пишется программный код,
      который реализует желаемое поведение системы и позволит пройти написанный тест.
      Затем проводится рефакторинг написанного кода с постоянной проверкой прохождения тестов.
    - BDD — behaviour-driven development — это разработка, основанная на описании поведения.
      Определенный человек(или люди) пишет описания вида "я как пользователь хочу когда нажали кнопку пуск
      тогда показывалось меню как на картинке" (там есть специально выделенные ключевые слова).
      Программисты давно написали специальные тулы, которые подобные описания переводят в тесты (иногда совсем прозрачно
      для
      программиста). А дальше классическая разработка с тестами.

    - DDD - это набор принципов и схем, направленных на создание оптимальных систем объектов.
      Процесс разработки сводится к созданию программных абстракций, которые называются моделями предметных областей.
      В эти модели входит бизнес-логика, устанавливающая связь между реальными условиями области применения продукта и
      кодом.
      }
- С чего начинается создание фичи/компонента/проекта
- Как выбирать библиотеки?
