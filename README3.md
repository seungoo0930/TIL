# TIL
#### 2025-07-11

1. 클래스 (Class)

class Animal {
  constructor(name) {
    this.name = name;
  }

  speak() {
    console.log(`${this.name}가 소리칩니다.`);
  }
}

let dog = new Animal("강아지");
dog.speak(); 

2. try...catch (에러 처리)

try {
  let result = someFunction(); 
} catch (error) {
  console.log("에러 발생:", error.message);
}

3. 모듈 (import / export)

export function sayHello() {
console.log("안녕!");
}

import { sayHello } from './hello.js';
sayHello();****

4. 비동기 처리 (async/await)

async function getData() {
  let response = await fetch("https://api.example.com/data");
  let data = await response.json();
  console.log(data);
}
