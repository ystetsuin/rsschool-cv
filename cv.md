# Yaroslav Stetsiun

Learning Frontend, want to be a Junior Fronted Developer | ![Codewars stats](https://www.codewars.com/users/ystetsuin/badges/micro "Codewars stats") 
-----------|:-------: 

![My photo](https://avatars.githubusercontent.com/u/4940636 "My photo")

## Contacts

- Ukraine, Chernihiv
- +38(093) 728 2424
- yaroslav.stetsuin@gmail.com
- https://t.me/fallenhero

## About Me

I'm a SEO-specialist who wants to become a Web Developer and get my first job as a Junior Frontend Developer.
I want to be involved in Frontend to create huge and useful projects that solve human needs.

## Skills:

- HTML&CSS
- Git
- JS
    - Basics
        - Operators
        - Scope / Closure
        - Data types / structures
        - Functions
        - Event loop
        - DOM
        - ES6+

## Strengths

- **Decency and honesty**. Always keep my promises.
- **Self-discipline**. I've been successfully working remotely for over 5 years.
- **Conscientiousness**. Do my work effectively.
- **Communicability**. I'm happy to give some advice. Build consensus easily with people.
- **Patience**. Understand that achieving goals needs time. I've been learning English (for over 1 year) and JS (for over 3 months).
- **Punctuality**. Fulfill my obligations on time.


## JS code example

**Task**:

Given an array of integers, find the one that appears an odd number of times.
There will always be only one integer that appears an odd number of times.

[Source](https://www.codewars.com/kata/54da5a58ea159efa38000836)

**Code**:

```
function findOdd(arr) {
    if (arr.length == 1) return arr[0];

    const unique = [...new Set(arr)];
    
    for (let i = 0; i < unique.length; i++) {
        let odd = [];
        for (let k = 0; k < arr.length; k++) {
            (arr[k] == unique[i]) ? odd.push(arr[k]) : null;
        }
        if (odd.length % 2) {
            return odd[0]
        }
    }
}
```

## Education and Courses

- Higher education. Chernihiv National University of Technology. Computer Network and Systems Engineer. 
- [The Modern JavaScript Tutorial](https://learn.javascript.ru/)
- [Udemy. Full JavaScript + React course - from beginning to result](https://www.udemy.com/course/javascript_full/)

## English

 - A2 (Pre-Intermediate)