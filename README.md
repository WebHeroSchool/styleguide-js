# styleguide-js

### 1. Выравнивание

Для выравнивания блоков кода используются табуляции (1 табуляция на 1 уровень выравнивания), знаки табуляции не используются.

Плохо:
```css
(function() {
let name = 'Web Hero';
return name;
})()
```
Хорошо:
```css
(function() {
  let name = 'Web Hero';
  return name;
})();
```

### 2. Создание переменной

Всегда используйте let или const для объявления каждой переменной.

Плохо:
```css
var user = "Kate"; //устаревшее объявление переменной, может встречаться в коде до ES-2015.
number = 15; //объявление переменной нет, ошибка.
```
Хорошо:
```css
let user = "Kate";
const number = 15;
```

### 3. Имя переменной

+ Имя переменной должно содержат только буквы, цифры или символы $ и _.
+ Первый символ не должен быть цифрой
+ Если в имени необходимо написать несколько слов, то каждое следующее слово доллжно начинаться с заглавной буквы (правило CamelCase)
+ Избегать кратких названий (a,p,c,asf и тд) Это может в будущем вас запутать и вы не вспомните что и для чего была объявлена та или иная переменная.

Плохо:
```css
let 1a; // не может начинаться с цифры
let my-dog; // не может включать дефис
```
Хорошо:
```css
let userName;
let test123;
```
