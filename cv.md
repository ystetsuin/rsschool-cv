# Yaroslav Stetsiun

Learning Frontend, want to be Junior Fronted Developer | ![Codewars stats](https://www.codewars.com/users/ystetsuin/badges/micro "Codewars stats") 
-----------|:-------: 

![My photo](https://avatars.githubusercontent.com/u/4940636 "My photo")

## Contacts

- Ukraine, Chernihiv
- +38(093) 728 2424
- yaroslav.stetsuin@gmail.com
- https://t.me/fallenhero

## About Me

I'm a SEO-specialist who wants to become Web Developer and get my first job as Junior Frontend Developer.
I want to be involved in Frontend to create huge and useful project, that solve human needs.


## Strengths

- **Decency and honesty**. Always try to keep my promises.
- **Self-discipline**. I've been successfully working remotely for over 5 years.
- **Conscientiousness**. Try to do my work quality.
- **Communicability**. I can give and listen advise if it needs. You can argue with me and come to common language.
- **Patience**. Understand that some events can take time to occur. I've been learning English (for over 1 year) and JS (for over 3 months).
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

- Higher education. Chernihiv National University of Technology. Computer network and systems engineer. 
- [The Modern JavaScript Tutorial](https://learn.javascript.ru/)
- [Udemy. Full JavaScript + React course - from beginning to result](https://www.udemy.com/course/javascript_full/)

## English

 - A2 (Pre-Intermediate)