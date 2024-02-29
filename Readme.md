# Js lecture 6
## Theme 1. - object
![подпись](https://miro.medium.com/v2/resize:fit:700/0*1-GpzIUp7bgbDl6X.jpeg)

## - Destructuring
## 3. - sPREAD AND THIS
__Салом алейкум, бачахо ва духтаракои хуб! Мо дар ин лисия дар бораи объект чист ва чанд методҳои дар боло дидаатон маълумот медиҳам.__
__Hello, good boys and girls! In this lesson, I will tell you about what the object is and some of the methods you have seen above.__
*RAFTEM*

## [Object](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Working_with_objects)-  набор СВОЙСТВА 
![подпись](https://www.freecodecamp.org/news/content/images/2021/02/destructure.png)
### Ай,"array" чӣ фарқ дорад?-Дар массив (array), элементҳо бо индексҳо дар мавод фарз карда мешаванд, дар ҳолати ки дар объект (object), элементҳо бо калидҳо (keys) фарyod карда мешаванд.
##### primeri odi
```javascript
let person = {
   name: "Odam",
   age: 99,
     getfullname: () => {
         return "chokadi radnoy "+ person.age+" "+person.name
     }}
     person.age = 5 //ish baroi izmenit kadani 
 console.log(person.getfullname());
```

## Дар массив (array), индексҳо фақат аз навбати ададӣ (numeric) истифода мебаранд, дар ҳолати ки дар объект (object), калидҳо (keys) метавонанд аз ҳер калиди муайян (specified) истифода баранд.

Ин фарқҳо дар корбарии ду обҷект ва массив муайян аст
### In an array, elements are represented by indexes in the material, while in an object, elements are represented by keys.

### In an array, indexes use only numeric order, while in an object, keys can use any specified key.

### These differences are defined in the usage of two objects and arrays

**A keybordi ``this`` Боша - дар вақти ки да дарунӣ ягон объект омад, худша да ҳаму объект мебахшад**
**A ``this`` keyboard - when an object is entered, it automatically displays all objects**
    
**``Object.keys``-Ключоша пурра дар масив меброра**
**-`Object.keys`-The key is completely in the array**

``````javascript
 let person = {
     name: "Odam",
     age: 99,
     getfullname: () => {
         return "chokadi radnoy "+ person.age+" "+person.name
     }
    
    
 }
person.age = 5

console.log(Object.keys(person));
``````
**``Object.values``-бар зидди keys тамоми арзишро дар массив бармегардонад**
**``Object.values``-against keys returns all values in the array**




*Davay Hamada karochi ma raftm*

__you can ask me your question on socials__
**join me on social media**

- [My instagram](https://www.instagram.com/nurmuhamad1201/)
- [My GitHub](https://github.com/nurmuhamad1201)
- and [My Telegram](https://t.me/Nurmuhamad_1201)
