---
layout: post
title:  "Khai báo biến trong Javascript"
date:   2021-08-11 11:30 +0700
categories: js
tags: code
---
Phi lộ: Khai báo biến trong js sử dụng 3 từ khóa - var, let, const. Và không cần gán kiểu dữ liệu của biến khi khai báo biến.
=>
- Từ khóa: var, let,const (từ ES6)
- Không cần phải khai báo kiểu dữ liệu của biến
Phân tích sự khác nhau khi sử dụng các từ khóa var, let, const: 

#### 1. var
   
- Khi biến được khai báo trong 1 hàm -> biến đó sẽ nằm trong phạm vi của hàm
- Khi biến được khai báo trong 1 khối (block {}), hoặc bên ngoài hàm -> biến toàn cục có phạm vi toàn cục
- Biến có thể được khai báo lại và gán lại trong chương trình
- Hoisting: Khái niệm hoisting chỉ tồn tại với từ khóa var (Không tồn tại với từ khóa let, const)
Ví dụ:
```javascript
var str = "Hello World"; 
console.log(str);
```
#### 2. let
   