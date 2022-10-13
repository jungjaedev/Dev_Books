# 모던 자바스크립트 Deep Dive

## 04장 변수

### 4.1

`var result = 10 + 20`
10과 20이 별개의 메모리 공간에 들어가 있고, 그 둘을 연산한 결과인 30 또한 별개의 메모리 공간에 따로 저장함

### 4.5

변수 선언은 소스코드가 순차적으로 실행되는 시점인 런타임 이전에 먼저 실행되지만 값의 할당은 소스코드가 순차적으로 실행되는 시점인 런타임에 실행된다.

```js
console.log(score);  // undefined

var score; // 변수 선언
score = 80; 값의 할당

console.log(score); // 80
```

### 4.7

```js
// camelCase
var firstName;

// snake_case
var first_name;

// PascalCase
var FirstName;

// typeHungarianCase
var strFirstName; // type + identifier
var $elem = document.getElementById('myId'); // DOM 노드
```

## 06장 데이터 타입
