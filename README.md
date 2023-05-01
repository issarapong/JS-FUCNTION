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

## 4. Function Expressions

```

```


## 5. Arrow Functions

```

```

