# TIL

#### 2025-07-10
- 자바스크립트(문법)

- 1. 템플릿 리터럴 (Template Literals)

let name = "OO";
let greeting = `안녕하세요, ${name}님!`;
console.log(greeting);

- 2. 삼항 연산자 (조건 ? 참 : 거짓)
 
let age = 18;
let status = age >= 18 ? "성인" : "미성년자";
console.log(status);

- 3. 배열 메서드
  
let numbers = [1, 2, 3, 4, 5];

numbers.forEach(num => console.log(num)); 

let doubled = numbers.map(num => num * 2); 
console.log(doubled); 

let evens = numbers.filter(num => num % 2 === 0); 
console.log(evens);

let sum = numbers.reduce((acc, cur) => acc + cur, 0); 
console.log(sum);

- 4. 구조 분해 할당 (Destructuring)
  
배열

let [a, b] = [1, 2];
console.log(a);

객체

let person = { name: "OO", age: 20 };
let { name, age } = person;
console.log(name); 

- 5. 스프레드 연산자
 
let arr1 = [1, 2];
let arr2 = [...arr1, 3, 4]; 

let obj1 = { a: 1 };
let obj2 = { ...obj1, b: 2 }; 
