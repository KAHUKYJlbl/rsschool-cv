![Iurii Pototskii](img/myFace.jpg)

---

# Iurii Pototskii

**Junior frontend developer**

---
### In touch
  
**Telegram:** [@KAHUKYJlbl](https://t.me/KAHUKYJlbl)  
**LinkedIn:** [Iurii Pototskii](https://www.linkedin.com/in/iuriipototskii/)  
**GitHub:** [KAHUKYJlbl](https://github.com/KAHUKYJlbl)  
**Phone:** [+7 (921) 768-73-68](tel:+79217687368)  
**Email:** [IuriiPototskii@gmail.com](mailto:iuriipototskii@gmail.com)  

---
### Milestones
After 10 years in logistics business I'm looking for a new Ways.  
I'm good in getting along well with colleagues and clients.  
My strengths is hard working skills and great production discipline.

For now I'm sudying in Rolling Scopes School, learning Javascript.  
I'm going to be a well-skilled front-end developer.

---
### My skills
+ HTML & CSS
+ BEM
+ Javascript
+ Figma
+ Bootstrap
+ Git / GitHub

---
### My code
1) codewars kata **The museum of incredible dull things**

*Given an array of integers, remove the smallest value. __Do not mutate the original array/list.__  
If there are multiple elements with the same value, remove the one with a lower index.  
If you get an empty array/list, return an empty array/list.  
Don't change the order of the elements that are left.*

```javascript
function removeSmallest(numbers) {
  let indexMin = numbers.indexOf(Math.min(...numbers));
  let arr = numbers.filter((x, i) => i !== indexMin);
  return arr;
}
```

2) codewars kata **Sum of odd numbers**

*Given the triangle of consecutive odd numbers:*

||||||1||||||
---|---|---|---|---|---|---|---|---|---|---
|||||3||5|||||
||||7||9||11||||
|||13||15||17||19|||
||21||23||25||27||29
...||...||...||...||...||...

*Calculate the sum of the numbers in the n-th row of this triangle (starting at index 1) e.g.:  
1 -->  output 1  
2 --> 3 + 5 = output 8*

```javascript
function rowSumOddNumbers(n) {
  
  let nthRowFirst = (n*(n-1)) + 1;
  let sum = 0;
  for (i = 0; i < n; i++) {
    sum += nthRowFirst;
    nthRowFirst += 2;
  };
  
  return sum;
};
```

---
### My experience
I have just student experience for now.  
Here you can see one of my school projects: [GitHub](https://github.com/KAHUKYJlbl/htmlacademy-technomart) and [GitHub Pages](https://kahukyjlbl.github.io/htmlacademy-technomart/)

---
### My education
I am engineer in service and exploitation of vehicle, tractors and agritechnical machines.  
I studied at the Saint Petersburg State Agrarian University from 2009 to 2015.

---
### My languages
+ Russian - native speaker  
+ English - [C2](https://efset.org/cert/kxyjek) by [EF SET](https://www.efset.org/) / A2 by EPAM examinator test