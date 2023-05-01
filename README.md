# JS-FUNCTION 
    บันทึกทำความเข้าใจเรื่อง Java Script Function 

## 1. Functions

```
// กำหนดตัวแปรรับค่าให้ Function
function sum(num1, num2) {
  return num1 + num2;
}

// เรียกใช้งาน function
sum(3, 6); // 9

```
##### รูปแบบนี้จะเป็นรูปแบบการเรียกใช้งาน Function พื้นฐานที่พบได้ทั่วไป จุดประสงค์หลักๆคือการส่งค่าที่ต้องการให้ Fuction นั้นๆ ประมวลผลลัพธ์ที่ต้องการออกมา เพื่อนำไปใช้งานต่อไป / ต้องมีคำสั่ง return กำกับด้วยทุกครั้ง ถึงจะมีการส่งค่ากลับออกมา..
##### ตัวอย่างเพิ่มเติม. <a href = "https://github.com/issarapong/JS-FUCNTION/tree/main/1.Functions">1. Function</a>

## 2. Anonymous Functions

```
// ตัวอย่าง function ปกติ
function rocketToMars() {
  return 'BOOM!';
}

// Anonymous function
const rocketToMars = function() {
  return 'BOOM!';
}
```
##### ตามตัวอย่างเป็นการเปรียบเทียบระหว่าง Function ปกติ กับ Anonymous Function  จะเห็นว่า ไม่ต้องระบุชื่อฟังชั่น และสามารถนำค่าที่ Return จาก Fuction เก็บเข้าตัวแปรและนำไปใช้ต่อได้เลย

##### ตัวอย่างเพิ่มเติม. <a href = "https://github.com/issarapong/JS-FUCNTION/tree/main/2.Anonymous%20Functions">2. Anonymous Function</a>

## 3. Function Parameters

```
// The parameter is name
function sayHello(name) {
  return `Hello, ${name}!`;
}
  console.log(sayHello('ไชโย'))
```
##### Function Parameter คือ function ที่มีการส่ง รับค่า parameter เข้าไป ประมวลผล ก่อน Return ค่าออกมาใช้งาน การเรียกใช้ Function Parameter ต้องมีการระบุตัว ค่า parameter ลงไปทุกครั้งที่เรียกใช้งานเพื่ิอให้ได้ผลลัพธ์ที่ถูกต้อง 

##### ตัวอย่างเพิ่มเติม. <a href = "https://github.com/issarapong/JS-FUCNTION/tree/main/3.Function%20Parameters">3. Function Parameter</a>

## 4. Function Expressions

```
//แบบระบุ
const dog = function() {
  return 'Woof!';

  
}
// แบบไม่ระบุ
const dog = function(type) {
    return `Woof!${type}`;
  }
  console.log(dog('puddle'))
```
##### Function Expression คือ function อย่างย่อลักษณะเดียวกับ  Anonymous function โดยจะสามารถระบุ parameter เข้าไปหรือไม่ระบุเข้าไปก็ได้

##### ตัวอย่างเพิ่มเติม. <a href = "https://github.com/issarapong/JS-FUCNTION/tree/main/4.Function%20Expressions">4. Function Expression</a>


## 5. Arrow Functions

```
// Arrow function แบบระบุ 2 Parameter
const sum = (firstParam, secondParam) => { 
  return firstParam + secondParam; 
}; 
console.log(sum(2,5)); // Prints: 7 

// Arrow function แบบ ไม่ระบุ Parameter
const printHello = () => { 
  console.log('hello'); 
}; 
printHello(); // Prints: hello

// Arrow functions แบบ Parameter เดียว
const checkWeight = weight => { 
  console.log(`Baggage weight : ${weight} kilograms.`); 
}; 
checkWeight(25); // Prints: Baggage weight : 25 kilograms.


// Concise arrow functions
const multiply = (a, b) => a * b; 
console.log(multiply(2, 30)); // Prints: 60 

```
##### Arrow Function  เป็น รูปแบบ Fucntion ที่เริ่มมีการเรียกใช้ ตั้งแต่ ES6  เป็นต้นมา โดยใช้ => แยก ระหว่าง ส่วน Function Parameter และ Function Body  มีทั้งรูปแบบ ระบุ Parameter และไม่ระบุ Parameter ซึ๋ง ในการเขียนโปรแกรม ภาษา Java Script จะพบเจอได้บ่อยมาก

##### ตัวอย่างเพิ่มเติม. <a href = "https://github.com/issarapong/JS-FUCNTION/tree/main/5.Arrow%20Functions">5. Arrow Function </a>