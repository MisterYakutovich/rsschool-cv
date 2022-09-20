## **[rsschool-cv](https://MisterYakutovich.github.io/rsschool-cv/)**
---
# **PAVEL YAKUTOVICH**

## **Contacts**
---

* ### Phone: +375298842839 
* ### GitHub: [MisterYakutovich](https://github.com/MisterYakutovich)
* ### E-mail: pavelyakutovich@gmail.com
* ### Telegram: [Pavel Yakutovich](https://t.me/pashaforever1571)
* ### [Linkedln](https://www.linkedin.com/in/pavel-yakutovich-10b97a22a/)

## **About myself**
---
A novice Web developer, mainly in frontend engineering.I am looking for a job in a company where i can apply my skills in web development.
## **Education and courses**
---
* ### Belarusian Polytechnic College in Grodno
  * #### Technical and mechanical faculty
  * #### 09/2001-06/2005
* ### Step Computer Academy
  * #### Web developer courses
  * #### 02/2021-02/2022
## **Languages**
---
* ### Russian - native
* ### English - A2
## **Tech Skills**
---
* #### HTML5, CSS
* #### MySql, Sequelize
* #### JavaScript (Basic)
* #### React, Express.js
* #### Git
## **Code examples**
---
*Search for the programming language with the longest name*
```javascript
const programmingLanguage = [{
    name: 'C#',
    rating: 9,
}, {
    name: 'JS',
    rating: 8.5,
}, {
    name: 'PHP',
    rating: 3,
}, {
    name: 'Java',
    rating: 3,
},];

function findLongName(programmingLanguage) {
    let longName = 0;
    for (let i in programmingLanguage) {
        if (programmingLanguage[i].name.length > programmingLanguage[longName].name.length) {
            longName = i;
        }
    }

    return programmingLanguage[longName];
}
console.log(findLongName(programmingLanguage));
```