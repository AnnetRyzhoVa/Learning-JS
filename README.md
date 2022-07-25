# Learning-JS
// const numbers = [45, 4, 2, 1, -50, 300, 0];
// console.log (numbers.sort())

// const numbers = [2, 5, 7, 9];
// const results = numbers.map(n=> n**5);
// console.log (results)

// const characters = ['d', 'z', 'a', 'c', 'y'];
// console.log (characters.sort()) 

// const numbers = [45, 4, 2, 1, -50, 300, 0];
// function compare(a=number, b=number) {
//     if (a > b) return 1;
//     if (a === b) return 0;
//     if (a < b) return -1;
// };
// console.log (numbers.sort(compare));

// const numbers = [45, 4, 2, 1, -50, 300, 0];
// numbers.sort((a, b) => a-b);
// console.log (numbers);

// const languages = ['pyton', 'java', 'js'];
// languages.splice(0,2);
// console.log(languages);

// const languages = ['pyton', 'java', 'js'];
// languages.splice(0, 2, 'php', 'c#', 'c++');
// console.log(languages);

// const languages = ['java', 'pyton', 'php', 'c++', 'js', 'sql'];
// const newList = languages.slice(0, 6);
// console.log(newList);

// a
 
// const fruits =['apple', 'pineapple', 'grape'];
// const additionalFruits = ['tomatoes', 'cucumbers', 'onion'];
// const summary = fruits.concat(additionalFruits);
// console.log(summary);

// const cars = [
//     {id: 1, model: 'Ferrary'},
//     {id: 2, model: 'Audi'},
//     {id: 3, model: 'Toyota'}
// ];
// const audi = cars.find(function(item, index, arr) {
//     return item.model === 'Audi';
// });
// console.log(audi);


// const cars = [
//     {id: 1, model: 'Ferrary'},
//     {id: 2, model: 'Audi'},
//     {id: 3, model: 'Toyota'}
// ];
// const audi = cars.find(item => item.model === 'Audi');
// console.log(audi);


// const cars = [
//     {id: 1, model: 'Ferrary'},
//     {id: 2, model: 'Audi'},
//     {id: 3, model: 'Toyota'},
//     {id: 4, model: 'Suzuki'}];
// const filterCars = cars.filter(item => item.id%2 === 0);
// console.log(filterCars);

// const fruits = ['apples', 'bananas', 'oranges', 'melons'];
// fruits.reverse();
// console.log)(fruits);
 
// const str ='Katerina';
// const arr = str.split();
// console.log(arr);

// function hello(){
//     console.log('Hello');
// }
// setInterval(hello, 3000);

// function hello(){
//     console.log('Hello');
// }
// const intervalId = setInterval(hello,1000);
// clearInterval(intervalId);

// let counter = 0;

// function hello(){
//     console.log('Hello, world!');
//     counter +=1;
//     if (counter===3) {
//         clearInterval(intervalId);
//     }
// }
// let a = 3;
// let b = 7;
// function test(a, b) {
// let x;
//        if (a > b) {
//         x = a + b;
//     }
//     else {
//     x = a * b;
//     }
//     return x;
// }
// const catVasya = {
// name: 'Vasya',
// age: 6,
// color: 'grey', 
// weight: 4, 
// mew: function() { 
// console.log('мяу-мяу');
// }
// }
// catVasya.mew();
// sayAge.function(); {
//     console.log('Hello, I am ' + this.age + ' years old');
// }
// catVasya.sayAge()


// function hi() {
//     console.log('Man')}
// const man = {
//     name: 'Andrey',
//     lastName: 'Bogdan', 
//     age: 34,
//     sayHi: hi
// };
// man.sayHi();

// function hi() {
//     console.log('Woman!')}
// const women = {
//     name: 'Kateryna',
//     lastName: 'Ryzhova',
//     age: 20,
//     sayHi: hi
// };
// women.sayHi();

// const Logger = {
//     info: function(sex) {
//     console.log('Name:' , this.name);
//     console.log('LastName:' , this.lastName);
//     console.log('Age:' , this.age);
//     console.log('Sex:' , sex)
//     }
// };

// const loggerMan = Logger.info.bind(man);
// loggerMan('Man');

// const loggerWomen = Logger.info.bind(women);
// loggerWomen('Women');

// function hi(name) {
//     return function() {
//         console.log(`Hello, ${name}`);
//     }
// }
// const sayHiPetya = hi('Petya');
// const sayHiKatya = hi('Katya');
// const sayHiAnna = hi('Anna');
// sayHiPetya();
// sayHiKatya();
// sayHiAnna();

// function createSocLink(socialNetwork) {
//     return function(nickname){
//         return `https://${socialNetwork}/${nickname}`;
//     }
// }
// const createInstagramLink = createSocLink('Instagram.com');
// const createFacebookLink = createSocLink('Facebook.com');
// console.log(createInstagramLink('ilchikolga.desserts'));
// console.log(createFacebookLink('profile.php?id=100004562075897'));

const cat = new Object ({
    name: 'Vasya',
    age: 6,
    color: 'grey', 
    weight: 4, 
    meow: function() { 
    console.log('Meow!!!');
    }
});

console.log(cat);

