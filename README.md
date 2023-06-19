# javaScript_tutorial

 <html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Assignment</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet"
        integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" crossorigin="anonymous">
</head>

<body>
    <div class="container">

        <div class="row">
            <div>
                //useful string method
                // 1. trim()
                <!-- <script>
                    let firstName = "  Krishna  ";
                    console.log(firstName.length);
                    let newString = firstName.trim();
                    console.log(newString);
                    console.log(newString.length);
                    console.log(newString);
                </script> -->

                // 2. toUpperCase()
                <!--<script>
                    let fName = "krishna";
                    console.log(fName);
                    fName = fName.toUpperCase();
                    console.log(fName);
                </script> -->

                // 3. toLowerCase()
                <!-- <script>
                    let fName = "KRISHNA";
                    console.log(fName);
                    fName = fName.toLowerCase();
                    console.log(fName);
                </script> -->

                // 4. slice(start index, end index)
                <!--<script>
                    let fName = "KRISHNA";
                    console.log(fName);
                    let newString = fName.slice(1,3);
                    console.log(newString);
                </script> -->

                // typeof Method
                <!-- <script>
                    let age =28;
                    console.log(typeof age);
                </script> -->

                // convert number to string data type
                <!-- <script>
                    let age =28;
                    console.log(typeof (age + ""));
                </script> -->
                //OR
                <!-- <script>
                    let age = 28;
                    age = String(age)
                    console.log(typeof age);
                </script> -->

                // convert string to number data type
                <!-- <script>
                    let name = +"Krishna";
                    console.log(typeof name);
                </script> -->
                //OR
                <!-- <script>
                    let name ="krishna";
                    name=Number(name);
                    console.log(typeof name);
                </script> -->

                // string concatenation
                <!-- <script>
                    let fName = "krishna";
                    let lName = "Deshmukh";
                    let fullName = fName + " " + lName;
                    console.log(fullName);
                </script> -->

                // Template string
                //My Name is Krishna and my age is 12
                <!-- <script>
                    let fName = "krishna";
                    let age = "15";
                    let about = `My Name is ${fName} and my age is ${age*2}`;
                    console.log(about);
                </script> -->

                // if else condition
                <!-- <script>
                    let age = 16;
                    if(age>=18){
                         console.log("yehhh...krishna you are eligible for vot");
                    }else{
                        console.log("oho...you are not eligible");
                    };
                </script> -->
                // OR
                <!-- <script>
                    let num= prompt("Please enter Number");
                    //prompt takes allways string input                    
                    if(num%2===0){
                        console.log(`${num} is Even Number`);
                    }else{
                        console.log(`${num} is Odd Number`);
                    }
                </script> -->

                // Turnary Oprator or Conditional Oprator
                <!-- <script>
                    let age = 15;
                    let drink ;
                    if (age >= 16) {
                        drink = "Coffee";
                    } else {
                        drink = "Tea";
                    }
                    console.log(drink);
                </script> -->

                // OR standard way
                <!-- <script>
                    let age=17;
                    let drink= age>=16? "coffee" : "Tea";
                    console.log(drink);
                </script> -->

                // Logical AND Oprator
                <!-- <script>
                    let name="Krishna";
                    let age="18";
                    if(name[0]==="K" && age>=18){
                        console.log("Name starts with 'K' and age above 18");
                    }else{
                        console.log("insider else");
                    }
                </script> -->

                // Logical OR Oprator
                <!-- <script>
                    let name="Krishna";
                    let age="10";
                    if(name[0]==="K" || age>=18){
                        console.log("Name starts with 'K' and age above 18");
                    }else{
                        console.log("insider else");
                    }
                </script> -->

                // if else if
                <!-- <script>
                    let temp=40;

                    if(temp<5){
                        console.log("it's extremely cold!!");
                    }else if(temp<10){
                        console.log("it's chilled");
                    }else if(temp<25){
                        console.log("it's Normal");
                    }else if (temp<36){
                        console.log("it's warm");
                    }else if (temp<45){
                        console.log("it's hot");
                    }else{
                        console.log("it's extremely Hot!!");
                    }
                </script> -->

                // Switch Statement
                <!-- <script>
                    let day = 5;

                    switch (day) {
                        
                        case 0:
                        console.log("Monday");
                        break;
                        case 1:
                        console.log("Teusday");
                        break;
                        case 2:
                        console.log("Wednesdy");
                        break;
                        case 3:
                        console.log("Tursday");
                        break;
                        case 4:
                        console.log("Friday");
                        break;
                        case 5:
                        console.log("Saturday");
                        break;
                        case 6:
                        console.log("Sunday");
                        break;
                        default :
                        console.log("Invalid day");
                    }
                </script> -->

                // While loop
                <!-- <script>
                    let i= 0;

                    while(i<=5){
                        console.log(i);
                        i++;
                    }
                    console.log(`current value of i is ${i}`);
                </script> -->

                //OR
                <!-- <script>
                    let num = 10;
                    let total = 0; //1+2+3+4+5+6+7+8+9+10
                    let i = 0;

                    while (i <= num) {
                        total = total + i
                        i++;
                    }
                    console.log(total);
                </script> -->

                // for loop
                <!-- <script>
                    let i=0;
                    let num= 11;
                    for(let i = 0; i <= num; i++) {
                        console.log(i);
                    }
                    console.log("value of i is", i);
                    //here let are block scope thats why we do not get value of i after this block 
                    //we can get value only by using var variable
                </script> -->

                //example
                <!-- <script>
                    let num = 10;
                    let total = 0;
                    for (let i = 0; i <= num; i++) {
                        total = total + i;
                    }
                    console.log(total);
                </script> -->

                // break Keyword
                <!-- <script>
                    for(let i=0; i <= 10; i++){
                        if(i===5){
                            break;
                        }
                        console.log(i);
                    }
                </script> -->

                // continue Keyword
                <!-- <script>
                    for(let i=0; i <= 10; i++){
                        if(i===5){
                            continue;
                        }
                        console.log(i);
                    }
                </script> -->

                // do while loop
                <!-- <script>
                    let i= 6;

                    do{
                        console.log(i);
                        i++;
                    }while(i<=5);

                    console.log(`current value of i is ${i}`);
                </script> -->

                // Arrays
                //array is reference type or object
                //array is ordered collection of items

                <!-- <script>
                    let fruits=["apple","banana","mango"];
                    console.log(fruits);
                    fruits[1]="orange"; //mutable type
                    console.log(fruits);
                    console.log(typeof fruits);
                    console.log(Array.isArray(fruits));

                    obj={} //literal object
                    console.log(typeof obj);
                    console.log(Array.isArray(obj));
                </script> -->

                //Array add remove method
                // push(), pop()
                <!-- <script>
                    //push()
                    let fruits=["apple","banana","mango"];
                    // console.log(fruits);
                    // fruits.push("orange"); //it add itemes in last position
                    // console.log(fruits);

                    // //pop()
                    //  //it remove itemes in last position
                    // let poppedItems = fruits.pop(); //it return deleted array item
                    // // console.log(fruits);
                    // console.log("popped fruit is", poppedItems);
                     
                    //unshift()
                    //it add item to first position
                    console.log(fruits);
                    fruits.unshift("coconut"); //mutable type
                    console.log(fruits);

                    //shift()
                    //it remove item to first position
                    fruits.shift();
                    console.log(fruits);
                </script> -->

                // primitive vs reference data type
                <!-- <script>
                    //primitive
                    // let num1 = 7;
                    // let num2 = num1;
                    // console.log(num1);
                    // console.log(num2);
                    // num1++;
                    // console.log(num1);
                    // console.log(num2); //it stoare sperate in stack memory

                    //referenc
                    let array1 = ["item1", "item2"];
                    let array2 = array1;
                    console.log(array1);
                    console.log(array2);
                    array1.push("item3")
                    console.log(array1);
                    console.log(array2);// it takes item from heap address to stack memory
                </script> -->

                //how to clone Array
                // sprade operator in Array
                <!-- <script>
                    let array1=["krishna","ganesh", "sachin"];
                    console.log(array1);
                    let array2=[...array1];
                    console.log(array2);
                    console.log(array1===array2);
                    array1.push("sunny");
                    console.log(array1);
                    console.log(array2);
                </script> -->

                // for loop in arrary
                <!-- <script>
                    let fruits = ["apple", "orange", "banana", "grapes"];
                    let fruits2 = [];
                    for (let i = 0; i < fruits.length; i++) {
                        console.log(fruits[i]);
                        fruits2.push(fruits[i].toUpperCase());
                    }
                    console.log(fruits2);
                </script> -->

                // while loop in array
                <!-- <script>
                    let fruits = ["apple", "orange", "banana", "grapes"];
                    let fruits2 = [];

                    let i = 0;
                    while (i < fruits.length) {
                        fruits2.push(fruits[i].toUpperCase());
                        i++;
                    }
                    console.log(fruits2);
                </script> -->

                // for of loop in array
                <!-- <script>
                    let fruits = ["apple", "orange", "banana", "grapes"];
                    let fruits2 = [];

                    for (let fruit of fruits) {
                        console.log(fruit);

                        fruits2.push(fruits.toUpperCase());
                    }
                    console.log(fruits2);
                </script> -->


                // for in loop in array
                <!-- <script>
                    let fruits = ["apple", "orange", "banana", "grapes"];
                    let fruits2 = [];

                    for (let index in fruits) {
                        fruits2.push(fruits[index].toUpperCase());
                    }

                    console.log(fruits2);
                </script> -->

                // arrary destructuring
                <!-- <script>
                    const myArray = ["value1", "value2", "value3", "value4"];
                    console.log(myArray);
                    var [myArray1, myArray2] = myArray;                 //method 1
                    console.log("value of myArray1 is", myArray1);
                    console.log("value of myArray2 is", myArray2);

                    var [myArray1, , myArray2] = myArray;               //method 2
                    console.log("value of myArray1 is", myArray1);
                    console.log("value of myArray2 is", myArray2);

                    var [myArray1, myArray2, ...myNewArray] = myArray;  //method 3 rest operator
                    console.log("value of myArray1 is", myArray1);
                    console.log("value of myArray2 is", myArray2);
                    console.log("value of myNewArray is", myNewArray)
                </script> -->

                // object
                <!-- <script>
                    //it has reference type
                    //arrays are good but not sufficient
                    //it used for real world data
                    //it stoar key value pairs
                    //it don't have index

                    /*how to create object*/
                    let person = {
                        name: "Krishna",
                        age : 28,
                        hobbis:["reading","swiming","driving"]
                    }
                    console.log(person);

                    //how to access data from object
                    console.log(person.name);
                    //OR
                    console.log(person["age"]);

                    //how to add key pairs in object
                    person.gender = "male";
                    //or
                    person["car"] ="Kia";
                    console.log(person);
                </script> -->

                // diff between dot and bracket notation in object
                <!-- <script>
                    key = "email";
                    let person = {
                        name: "Krishna",
                        age: 28,
                        "person hobbis": ["reading", "swiming", "driving"]
                    }
                    console.log(person["person hobbis"]);
                    person[key]="krishna@gmail.com";   //here compute value of key
                    console.log(person);
                </script> -->

                // how to iterate object
                <!-- <script>
                    let person = {
                        name: "Krishna",
                        age: 28,
                        hobbis: ["reading", "swiming", "driving"]
                    }

                    //for in loop
                    for (let key in person) {
                        console.log(key, ":", person[key]);
                    }

                    //object.keys
                    console.log(Object.keys(person));
                </script> -->

                // computed properties
                <!-- <script>
                    const key1 = "objKey1";
                    const key2 = "objKey2";

                    const value1 = "myValue1";
                    const value2 = "myValue2";

                    //output expected result
                    // const obj={
                    //     objKey1:myValue1,
                    //     objKey2:myValue2
                    // }

                    const obj = {
                        [key1]: value1,
                        [key2]: value2
                    }
                    console.log(obj);
                    //OR
                    let obj1 = {}
                    obj1[key1]=value1,
                    obj1[key2]=value2
                    console.log(obj);
                </script> -->

                // sprade operator in Object
                <!-- <script>
                    const obj1 = {
                        key1: 'value1',
                        key2: 'value2'
                    }
                    const obj2 = {
                        key1: 'uniqueValue',
                        key3: 'value3',
                        key4: 'value4'
                    }
                    const newObj = { ...obj1, ...obj2, key5: 'value5' }
                    console.log(newObj);
                </script> -->

                // Object destructuring
                <!-- <script>
                    const car={
                        name:'kia',
                        color:'white',
                        type:'auto',
                        wheel:'alloy'
                    }
                    const{name, color,...restProp}=car;
                    console.log(name);
                    console.log(restProp);
                </script> -->

                // Object inside Array
                //very useful in real world application
                <!-- <script>
                    const users = [
                        { userid: 1, name: 'krishna', mob: '8806866' },
                        { userid: 2, name: 'ganesh', mob: '000000' },
                        { userid: 3, name: 'sunny', mob: '999999' }

                    ]
                    
                    for(let user of users){
                        console.log(user);
                        console.log(user.name );

                    }
                </script> -->

                // nested destructuring
                <!-- <script>
                    const users = [
                        { userid: 1, name: 'krishna', mob: '8806866' },
                        { userid: 2, name: 'ganesh', mob: '000000' },
                        { userid: 3, name: 'sunny', mob: '999999' }
                    ]
                    const [{ userid}, ,{mob}]=users
                    console.log(userid);
                    console.log(mob);
                </script> -->

                // Functions
                // function decleration
                <!-- <script>
                    function happyBirthday() {
                        console.log("happy Birthday to you..");
                    }
                    happyBirthday();
                    //
                    function addition(num1, num2) {
                        return num1 + num2;
                    }
                    const returnValue = addition(4, 6)
                    console.log(returnValue);
                    //
                    //isEvenNumber
                    //input:1 number
                    //output: true, false

                    function isEven(number) {
                        if (number % 2 === 0) {
                            return true
                        } else {
                            return false
                        }
                    }
                    console.log(isEven(7));
                    //OR
                    function isEven(number) {
                        return (number % 2 === 0);
                    }
                    console.log(isEven(10));
                    //
                    //function
                    //input: string
                    //output: firstCharactor
                    function firstCharactor(string) {
                        return string[0];
                    }
                    console.log(firstCharactor("Krishna"));
                    //
                    //function
                    //input: array, target (number)
                    //output: index of target if target present in array
                    function findTarget(array, target) {
                        for (let i = 0; i < array.length; i++) {
                            if (array[i] === target) {
                                return i;
                            }
                        }
                        return -1;
                    }
                    const myArray = [4, 7, 2, 9, 3];
                    const ans = findTarget(myArray, 7);
                    console.log(ans);
                </script> -->

                // function expression or anonymous function
                <!-- <script>
                    const happyBirthday = function () {
                        console.log("happy Birthday to you..");
                    }
                    happyBirthday();
                    //
                    const addition = function (num1, num2) {
                        return num1 + num2;
                    }
                    const returnValue = addition(4, 6)
                    console.log(returnValue);
                    //
                    //isEvenNumber
                    //input:1 number
                    //output: true, false

                    let isEven = function (number) {
                        return (number % 2 === 0);
                    }
                    console.log(isEven(10));
                    //
                    //function
                    //input: string
                    //output: firstCharactor
                    const firstCharactor = function (string) {
                        return string[0];
                    }
                    console.log(firstCharactor("Krishna"));
                    //
                    //function
                    //input: array, target (number)
                    //output: index of target if target present in array
                    const findTarget = function (array, target) {
                        for (let i = 0; i < array.length; i++) {
                            if (array[i] === target) {
                                return i;
                            }
                        }
                        return -1;
                    }
                    const myArray = [4, 7, 2, 9, 3];
                    const ans = findTarget(myArray, 3);
                    console.log(ans);
                </script> -->

                // arrow function
                <!-- <script>
                    const happyBirthday =  () =>{
                        console.log("happy Birthday to you..");
                    }
                    happyBirthday();
                    //
                    const addition =  (num1, num2) =>{
                        return num1 + num2;
                    }
                    const returnValue = addition(4, 6)
                    console.log(returnValue);
                    //
                    //isEvenNumber
                    //input:1 number
                    //output: true, false

                    let isEven =  number => (number % 2 === 0);
                    
                    console.log(isEven(11));
                    //
                    //function
                    //input: string
                    //output: firstCharactor
                    const firstCharactor =  (string) =>{
                        return string[0];
                    }
                    console.log(firstCharactor("Krishna"));
                    //
                    //function
                    //input: array, target (number)
                    //output: index of target if target present in array
                    const findTarget =  (array, target)=> {
                        for (let i = 0; i < array.length; i++) {
                            if (array[i] === target) {
                                return i;
                            }
                        }
                        return -1;
                    }
                    const myArray = [4, 7, 2, 9, 3];
                    const ans = findTarget(myArray, 3);
                    console.log(ans);
                </script> -->

                //hoisting
                <script>

                </script>


                // functions inside function
                <!-- <script>
                    const app = () => {
                        const myFunc = () => {
                            console.log("function from myFunc");
                        }
                        const add = (num1, num2) => {
                            return num1 + num2;
                        }
                        const multply = (num3, num4) => {
                            return num3 * num4;
                        }
                        console.log("inside app");
                        myFunc();
                        console.log(add(6, 6));
                        console.log(multply(6, 10));
                    }
                    app();

                </script> -->

                // Lexical Scope or chaining
                <!-- <script>
                    const myVar = "value1";

                    const myApp = () => {
                        const myFunc = () => {
                            // const myVar = "value156567";
                            const myFunc2 = () => {
                                console.log("inside function", myVar);
                            };
                            myFunc2();
                        };
                        console.log(myVar);
                        myFunc();
                    };

                    myApp();
                </script> -->

                // block scope vs function Scope
                // let and const are block scope
                //var is function scope

                // default parameter function
                <!-- <script>
                    const add = (a, b) => {
                        if (typeof b === "undefined") {
                            b = 0;
                        }
                        return a + b;
                    };
                    const ans = add(8)
                    console.log(ans);
                    //or

                    const addition = (a, b = 0) => {
                        return a + b;
                    };
                    const ans1 = addition(8,5);
                    console.log(ans1);
                </script> -->

                // rest parameter
                <!-- <script>
                    const myFunc = (a, b, ...c) => {
                        console.log(`a is ${a}`);
                        console.log(`b is ${b}`);
                        console.log(`c is ${c}`);
                    }
                    myFunc(5, 6, 7, 8, 9, 2, 3);
                    //e.g

                    const addAll = (...numbers) => {
                        total = 0;
                        for (let number of numbers) {
                            total = total + number;
                        }
                        return total;
                    }
                    const ans = addAll(2, 3, 4, 5, 6, 7, 8);
                    console.log(ans);
                </script> -->

                // param destructuring in object
                <!-- <script>
                    const person = {
                        firstName: 'krishna',
                        gender: 'male',
                        age:'28'
                    }
                    // const printAll = (obj) => {
                    //     console.log(obj.firstName);
                    //     console.log(obj.gender);
                    // };
                    // printAll(person);
                    //OR
                    const printAll = ({firstName, gender, age}) => {
                        console.log(firstName);
                        console.log(gender);
                        console.log(age);

                    };
                    printAll(person);
                </script> -->

                // callback function
                <!-- <script>
                    function myFunc1(name){
                        console.log("inside func 1");
                        console.log(`your name is ${name}`);
                    }
                    function myFunc2(callback){
                        console.log("hello here i am myFunc2");
                        callback("Krishna")
                    }
                    myFunc2(myFunc1);

                </script> -->

                // function returning function
                <!-- <script>
                    const myfunc=()=>{
                        const hello=()=>{
                            return "hello world";
                        }
                        return hello;
                    }
                    const ans= myfunc();
                    console.log(ans); 
                    console.log(ans()); 
                </script> -->

                // inportant array method

                //forEach()
                //map()
                //filter()
                //reduce()

                // forEach() method
                //it takes input allways callback function
                //it gives index in output

                <!-- <script>
                    // const numbers = [2, 3, 4, 5, 6, 7, 8];
                    // const myfunc = (number, index) => {
                    //     console.log(`number is ${number} and index is ${index}`);
                    // }
                    // numbers.forEach(myfunc);
                    // //OR

                    // const numbers = [2, 3, 4, 5, 6, 7, 8];

                    // numbers.forEach((number, index) => {
                    //     console.log(`number ${number}*2 = ${number*2} and index is ${index}`);
                    // });
                    ////OR
                    
                    const users = [
                        { userid: 1, name: 'krishna', mob: '8806866' },
                        { userid: 2, name: 'ganesh', mob: '000000' },
                        { userid: 3, name: 'sunny', mob: '999999' }
                    ]
                    users.forEach((user,index)=>{
                        console.log(user.name, index);
                    });
                </script> -->

                // map() method---array ka method
                //it takes input allways callback function
                //it's callback allways return somthing
                //it gives in output one array
                <!-- <script>
                    const numbers = [3, 4, 5, 6, 7, 8, 9, 10, 11, 12];
                    const sqare = (number) => {
                        return number * number;
                    }
                    squareNumber = numbers.map(sqare);
                    console.log(squareNumber);
                    ////OR

                    const users = [
                        { userName: 'krishna', mob: '8806866' },
                        { userName: 'ganesh', mob: '000000' },
                        { userName: 'sunny', mob: '999999' }
                    ]
                    const ans = users.map((user) => {
                        return user.userName;
                    });
                    console.log(ans);
                </script> -->

                // filter()
                //it takes input as allways callback function
                //it allways return boolean value true or false
                <!-- <script>
                    // const numbers = [4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16];
                    // const isEven = (number) => {
                    //     return number % 2 === 0;
                    // }
                    // const evenNumbers = numbers.filter(isEven); 
                    // console.log(evenNumbers);  
                    // //OR
                    
                    const numbers = [4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16];
                    
                    const evenNumbers = numbers.filter(isEven = (number) => {
                        return number % 2 === 0;
                    }); 
                    console.log(evenNumbers);  
                    
                </script> -->

                // reduce() ==> sum of all numbers
                // it takes input allways callback function
                //

                <!-- <script>
                    const numbers = [4, 5, 6, 7, 8, 9, 10];
                    //aim: sum of all 
                    
                    const sumAllNumber = numbers.reduce((accumulator, curentValue) => {
                        return accumulator + curentValue;
                    },0); 
                    console.log(sumAllNumber);  
                    //explination(how it is work)

                    //  accumulator,  currentValue,  return
                    //   4                  5           9
                    //   9                  6           15
                    //  15                  7           22
                    //  22                  8           30
                    //  30                  9           39
                    //  39                  10          49
                
                    //Example

                    const userCart=[
                        {userId:1,  productName:"laptop",   price:30000},
                        {userId:2,  productName:"keyboard",  price:2000},
                        {userId:3,  productName:"headphone",  price:5000}         
                    ]

                    const totalAmount =userCart.reduce((totalPrice, currentProduct)=>{
                        return totalPrice + currentProduct.price;
                    },0);
                    console.log(totalAmount);
                </script> -->

                // sort()==> a-b/b-a ==>lowToHigh / highToLow
                //it takes input allways callback function
                //it give allways new array
                <!-- <script>
                    const numbers = [4, 5, 8, 7, 6, 9, 10];
                     numbers.sort((a,b)=>{
                        return a-b;
                     });
                     console.log(numbers);
                     ////OR
                     const product=[
                        {userId:1,  productName:"laptop",   price:30000},
                        {userId:2,  productName:"mouse",  price:1000},        
                        {userId:3,  productName:"smartWatch",  price:3000},        
                        {userId:4,  productName:"charger",  price:1500},       
                        {userId:5,  productName:"keyboard",  price:2000},
                        {userId:6,  productName:"headphone",  price:5000}

                    ]
                    //loToHigh and clone by using slice() method
                    const loToHigh = product.slice(0).sort((a, b)=>{
                        return a.price-b.price;
                    });
                    // const array=[...loToHigh];
                    console.log(loToHigh);

                    //HighToLow
                    product.sort((a, b)=>{
                        return b.price-a.price;
                    });
                    console.log(product);

                    //maintain original & clonning array by using spred operator method
                    const highToLowPrice = product.sort((a, b)=>{
                        return b.price-a.price;
                    });
                    const newArray=[...highToLowPrice]// <---clone array method
                    console.log(newArray);
                </script> -->

                // find(string)==> length
                //it takes input allways callback function
                //it takes input as string
                //it gives output as length

                <!-- <script>
                    const myArray = ["Krishna","cat","dog","jyoti","lion"]
                    
                    const ans = myArray.find((string)=>string.length===7);
                    console.log(ans);
                    //OR

                    const users=[
                        {userId:1,  productName:"laptop",   price:30000},
                        {userId:2,  productName:"mouse",  price:1000},        
                        {userId:3,  productName:"smartWatch",  price:3000},        
                        {userId:4,  productName:"charger",  price:1500},       
                        {userId:5,  productName:"keyboard",  price:2000},
                        {userId:6,  productName:"headphone",  price:5000}

                    ]
                    const findUserId = users.find((user)=>user.userId===3);
                    console.log(findUserId);
                </script> -->

                // every() method
                //it takes input allways callback function
                //callback returns boolean value
                //if all number is even then it gives==>true
                //every method gives boolean value as output
                <!-- <script>
                    const numbers=[2,4,6,8,10];
                    const evenNumber = numbers.every((number)=>number % 2 === 0);
                    console.log(evenNumber);

                    //OR
                    const userCart=[
                        {userId:1,  productName:"laptop",   price:30000},
                        {userId:2,  productName:"keyboard",  price:2000},
                        {userId:3,  productName:"headphone",  price:5000}         
                    ];
                    const ans = userCart.every((cartItem)=>cartItem.price < 40000);
                    console.log(ans);
                </script> -->

                // some() method
                //it takes input allways callback function
                //if all of one number is even then it gives==>true

                <!-- <script>
                    const numbers=[1,3,5,7,9,10];
                    const evenNumber = numbers.some((number)=>number % 2 === 0);
                    console.log(evenNumber);

                    //OR
                    const userCart=[
                        {userId:1,  productName:"laptop",   price:30000},
                        {userId:2,  productName:"keyboard",  price:2000},
                        {userId:3,  productName:"headphone",  price:5000},
                        {userId:4,  productName:"macBook",  price:50000},

                    ];
                    const ans = userCart.some((cartItem)=>cartItem.price > 40000);
                    console.log(ans);
                </script> -->

                // fill (value, startIndex, endIndex) method
                // it change original array and give new array in output.

                <!-- <script>
                    const myArray = [1, 2, 3, 4, 5, 6, 7, 8, 9];
                    const ans = myArray.fill(0, 3, 6);
                    console.log(ans);
                </script> -->

                // splice(startIndex, howManyDeleteItems, addNevValue) method
                //it gives return deleted value
                <!-- <script>
                    const array = ["item1", "item2", "item3", "item4"];
                    //delete

                    // const deletedItem = array.splice(1, 1);
                    // console.log(array);
                    // console.log(deletedItem);

                    //insert new value
                    array.splice(1, 0, "newItem");
                    console.log(array);
                </script> -->

                // iterables
                //we used on for of loop
                //string , array are iterables

                <!-- <script>
                    //string
                    const firstName = "Krishna";
                    for(let char of firstName){
                        console.log(char);
                    }
                    //arrary
                    const items = ["item1", "item2", "item3", "item4"];
                    for(let item of items){
                        console.log(item);
                    }
                </script> -->

                // array like object
                //who have lenght property
                //we have access by index
                //example:- string
                <!-- <script>
                    const firstName = "Krishna";
                    console.log(firstName.length);
                    console.log(firstName[3]);
                </script> -->

                // Sets (it is iterable)
                //it stoar data
                //sets it also have own method
                //no index-based access
                //ordered is not guaranteed
                //unique itemes only (no duplicates allowed)
                <!-- <script>
                    // const numbers = new Set([1, 2, 3]);
                    // console.log(numbers);
                    //or
                    const numbers = new Set();
                    numbers.add(1);
                    // numbers.add([2,3]);
                    // numbers.add('abcda');
                    numbers.add(5);
                    numbers.add(6);
                    numbers.add(7);
                    numbers.add(8);
                    numbers.add(9);
                    console.log(numbers);

                    if (numbers.has(5)) {
                        console.log("5 is present");
                    } else {
                        console.log("5 is not present");
                    }
                    //applied for of loop

                    for (let number of numbers) {
                        console.log(number);
                    }
                    //or

                    const myArray = [1, 2, 2, 3, 4, 4, 5, 6, 7];
                    const uniqueElements = new Set(myArray);
                    // console.log(uniqueElement);
                    let lenght = 0;
                    for (let element of uniqueElements) {
                        length++;
                    }
                    console.log(lenght);
                </script> -->

                // Map() object
                //Map is an iterable
                //store data in ordered fashion
                //store key value pairs (like object)
                //duplicates keys are not allowed like objects
                //difference between map and objects

                //objects can only have string or symbol
                //as key

                //in Maps you can use anything as key
                //like array, number, string
                <!-- <script>
                    //// key value pairs
                    // const person = new Map();
                    // person.set('firstName', 'Krishna');
                    // person.set('age', '28');
                    // person.set('1', 'one');
                    // person.set([1, 2, 3], 'onetwoThree');
                    // person.set({ 1: 'one' }, 'oneTwoThree');
                    // // console.log(person);

                    // for (let key of person.keys()){
                    //     console.log(key);
                    // }

                    // for (let [key, value] of person){
                    //     console.log(key, value);
                    // }

                    //or

                    // const person = new Map([['firstName', 'krishna'],['age', '26']]);
                    //     console.log(person);

                    const person1 = {
                        id: 1,
                        firstName: 'Krishna'
                    }
                    const person2 = {
                        id: 2,
                        firstName: 'Jyoti'
                    }
                    const extraInfo = new Map();
                    extraInfo.set(person1, { age: 27, gender: 'male' });
                    extraInfo.set(person2, { age: 23, gender: 'female' });

                    // console.log(extraInfo);
                    console.log(person1.id);
                    console.log(extraInfo.get(person1).gender);

                    console.log(person2.firstName);
                    console.log(extraInfo.get(person2).age);
                </script> -->

                //clone using Object.assign

                <!-- <script>
                    //heap memory
                    const obj = {
                        key1: 'value1',
                        key2: 'value2'
                    }
                    const obj2 = { ...obj };   //new method for cloning--sprade operator
                    const obj3 = Object.assign({}, obj); //old method for cloning
                    obj.key3 = 'value3'
                    console.log(obj);
                    console.log(obj2);
                    console.log(obj3);
                </script> -->

                // Optional Chaining --> ?.
                <!-- <script>
                    const user={
                        firstName: 'Krishna',
                        // address:{houseNumber: '301'}
                    }
                    console.log(user?.firstName);
                    console.log(user?.address?.houseNumber);
                </script> -->

                // methods
                //function inside object

                <!-- <script>
                    // const person = {
                    //     firstName: 'Krishna',
                    //     age: 28,
                    //     about: function () {
                    //         console.log(`my name is ${this.firstName} and my age is ${this.age}`);
                    //         console.log(this);

                    //     }

                    // }
                    // person.about();
                    // console.log(person);
                    ////OR

                    function personInfo() {
                        console.log(`my name is ${this.firstName} and my age is ${this.age}`);

                    }
                    const person1 = {
                        firstName: 'Krishna',
                        age: 28,
                        about: personInfo

                    }
                    const person2 = {
                        firstName: 'Balaji',
                        age: 26,
                        about: personInfo

                    }
                    const person3 = {
                        firstName: 'Ganesh',
                        age: 24,
                        about: personInfo

                    }
                    person1.about();
                    person2.about();
                    person3.about();
                </script> -->

                //call, apply & bind() methods

                // call()
                <!-- <script>
                    const person1 = {
                        firstName: 'Krishna',
                        age: 28,
                        about: function (hobby, favActor) {
                            console.log(this.firstName, this.age, hobby, favActor);

                        }
                    }
                    const person2 = {
                        firstName: 'Balaji',
                        age: 26,

                    }
                    person1.about.call(person2, "Swimming", "Nagraj");

                    ////OR
                    // function about(hobby, favActor) {
                    //     console.log(this.firstName, this.age, hobby, favActor);

                    // }
                    // const person3 = {
                    //     firstName: 'Krishna',
                    //     age: 28,

                    // }
                    // const person4 = {
                    //     firstName: 'Balaji',
                    //     age: 26,

                    // }
                    // about.call(person3, "Swimming", "Nagraj");
                </script>-->

                // apply()
                <!-- <script>
                    function about(hobby, favActor) {
                        console.log(this.firstName, this.age, hobby, favActor);

                    }
                    const person3 = {
                        firstName: 'Krishna',
                        age: 28,

                    }
                    const person4 = {
                        firstName: 'Balaji',
                        age: 26,

                    }
                    about.apply(person3, ["Swimming", "Nagraj"]);
                </script> -->

                //bind()
                // it retun function in output
                <!-- <script>
                    function about(hobby, favActor) {
                        console.log(this.firstName, this.age, hobby, favActor);

                    }
                    const person5 = {
                        firstName: 'Krishna',
                        age: 28,

                    }
                    const person6 = {
                        firstName: 'Balaji',
                        age: 26,

                    }
                    const ans = about.bind(person6, "Swimming", "Nagraj");
                    ans();
                    console.log(ans); // in ans stoared function
                </script> -->

                // arrow function behaviour on this keyword
                //it has no own 'this' keyword
                //it takes 'this' from surrounding function i.e one level up
                //it never change
                <!-- <script>
                    const person7 = {
                        firstName: 'Krishna',
                        age: 28,
                        about: () => {
                            console.log(this);
                            console.log(this.firstName, this.age);
                        }
                    }
                    console.log(this);
                    person7.about();
                </script> -->

                //proto, prototype, class
                // analysis of Object Oreinted
                //1.function (that function create object) i.e constructor function
                //2.add key value pairs
                //3.it retun key value pairs to Object
                <!-- <script>
                    function createUser(fName, lName, email, age, address) {
                        const user = {};
                        user.fName = fName;
                        user.lName = lName;
                        user.email = email;
                        user.age = age;
                        user.address = address;
                        user.about = function () {
                            return (`my name is ${this.fName} and my age is ${this.age}`);
                        };
                        user.is18 = function () {
                            return this.age >= 18;
                        };
                        return user;
                    }

                    const user1 = createUser("Krishna", "Deshmukh", "krishna@gmail.com", 18, "pune");
                    console.log(user1);
                    const is18 = user1.is18();
                    console.log(is18);
                    const about = user1.about();
                    console.log(about);
                </script> -->

                //modification 01
                <!-- <script>
                    const userMethods = {
                        about: function () {
                            return (`my name is ${this.fName} and my age is ${this.age}`);
                        },
                        is18: function () {
                            return this.age >= 18;
                        }
                    }
                    function createUser(fName, lName, email, age, address) {
                        const user = {};
                        user.fName = fName;
                        user.lName = lName;
                        user.email = email;
                        user.age = age;
                        user.address = address;
                        user.about = userMethods.about;
                        user.is18 = userMethods.is18;


                        return user;
                    }

                    const user2 = createUser("Krishna", "Deshmukh", "krishna@gmail.com", 18, "pune");
                    const user3 = createUser("sunny", "Kalaskar", "sunny@gmail.com", 18, "satara");
                    const user4 = createUser("Ganesh", "patil", "ganesh@gmail.com", 18, "kolhapur");

                    console.log(user3.about());
                    console.log(user4.is18());
                </script> -->

                //create {} empty object by using --proto--
                <!-- <script>
                    const obj1 = {
                        key1: "value1",
                        key2: "value2"
                    }
                    const obj2 = Object.create(obj1);  //{}
                    //tere is one more way to create empty object
                    obj2.key3 = "value3";
                    console.log(obj2);
                    console.log(obj2.key1);
                    //this is happening
                    console.log(obj2.__proto__);
                </script> -->

                //modification 02--add Object.create() method
                <!-- <script>
                    const userMethods = {
                        about: function () {
                            return (`my name is ${this.fName} and my age is ${this.age}`);
                        },
                        is18: function () {
                            return this.age >= 18;
                        },
                        sing: function () {
                            return 'ohh ohhh jane jana';
                        }
                    }
                    function createUser(fName, lName, email, age, address) {
                        const user = Object.create(userMethods);
                        user.fName = fName;
                        user.lName = lName;
                        user.email = email;
                        user.age = age;
                        user.address = address;

                        return user;
                    }

                    const user2 = createUser("Krishna", "Deshmukh", "krishna@gmail.com", 18, "pune");
                    const user3 = createUser("sunny", "Kalaskar", "sunny@gmail.com", 18, "satara");
                    const user4 = createUser("Ganesh", "patil", "ganesh@gmail.com", 18, "kolhapur");

                    console.log(user3.about());
                    console.log(user4.is18());
                    console.log(user2);
                </script> -->

                //in javaScript function treat as function===> function + Object
                //javaScript function allways give .name property i.e hello.name
                //you can add your own properties in function
                //function has provide us free space in function i.e Empty Object {}
                //and this empty Object called prototype
                //only function provide prototype property not __proto__/[[Protorype]]
                //__proto__ or [[Protorype]] is chaining or referenc but, prototype is simple one object
                <!-- <script>
                    function hellow() {
                        console.log("Hello world!");

                    }
                    hellow();
                    console.log(hellow.name);

                    hellow.myOwnProperty = "hi i am Krishna";
                    console.log(hellow.myOwnProperty);

                    console.log(hellow.prototype);

                    hellow.prototype.abc = "aba";
                    hellow.prototype.xyz = "xyz";
                    console.log(hellow.prototype);

                    hellow.prototype.sing = function () {
                        return "lalalala";
                    };
                    console.log(hellow.prototype.sing());
                </script> -->

                //modification 03-- remove all methods and add in to prototype
                // Prototype
                <!-- <script>
                    function createUser(fName, lName, email, age, address) {
                        const user = Object.create(createUser.prototype);
                        user.fName = fName;
                        user.lName = lName;
                        user.email = email;
                        user.age = age;
                        user.address = address;


                        return user;
                    }

                    createUser.prototype.about = function () {
                        return (`my name is ${this.fName} and my age is ${this.age}`);
                    };
                    createUser.prototype.is18 = function () {
                        return this.age >= 18;
                    };
                    createUser.prototype.sing = function () {
                        return 'ohh ohhh jane jana';
                    };

                    const user2 = createUser("Krishna", "Deshmukh", "krishna@gmail.com", 18, "pune");
                    const user3 = createUser("sunny", "Kalaskar", "sunny@gmail.com", 18, "satara");
                    const user4 = createUser("Ganesh", "patil", "ganesh@gmail.com", 18, "kolhapur");

                    console.log(user3.about());
                    console.log(user4.is18());
                    console.log(user4.sing());
                    console.log(user2);
                </script> -->

                //new keyword
                //new keyword how is work
                //1. it create this === empty Object {} i.e this==={}
                //2. it return val in {} i.e return this
                //3. it set proto value equal to prototype i.e no need of "Object.create(createUser.prototype);"
                <!-- <script>
                    function createUser1(fName, age) {
                        this.fName = fName;
                        this.age = age;
                    }
                    createUser1.prototype.about = function () {
                        console.log(this.fName, this.age);
                    };

                    const user1 = new createUser1("Krisna", 28);
                    console.log(user1); // because of new keyword "user" converted to into object 

                    user1.about();
                </script> -->

                //modification 04-- remove "Object.create(createUser.prototype);" and put new keyboard
                // impliment new keyword
                // rule:- naming convention of func is firstLatter should Capital
                // hasOwnProperty() used at bellow
                <!-- <script>
                    function CreateUser(fName, lName, email, age, address) {
                        this.fName = fName;
                        this.lName = lName;
                        this.email = email;
                        this.age = age;
                        this.address = address;

                    }

                    CreateUser.prototype.about = function () {
                        return (`my name is ${this.fName} and my age is ${this.age}`);
                    };
                    CreateUser.prototype.is18 = function () {
                        return this.age >= 18;
                    };
                    CreateUser.prototype.sing = function () {
                        return 'ohh ohhh jane jana';
                    };

                    const user2 = new CreateUser("Krishna", "Deshmukh", "krishna@gmail.com", 18, "pune");
                    const user3 = new CreateUser("sunny", "Kalaskar", "sunny@gmail.com", 18, "satara");
                    const user4 = new CreateUser("Ganesh", "patil", "ganesh@gmail.com", 15, "kolhapur");

                    console.log(user3.about());
                    console.log(user4.is18());
                    console.log(user4.sing());
                    console.log(user2);

                    // hasOwnProperty()

                    for (let key in user2) {
                        // console.log(key); 
                        if (user2.hasOwnProperty(key)) {
                            console.log(user2[key]);
                        }
                    };
                </script> -->

                //let's analysis
                <!-- <script>
                    // const numbers = [1, 2, 3];
                    // console.log(numbers);

                    ////internaly created this way
                    const numbers = new Array(1, 2, 3);
                    console.log(Array.prototype);
                    ////check prototypes of numbers
                    console.log(Object.getPrototypeOf(numbers));
                </script> -->

                //modification 05-- remove prototype and method paste in class directly
                // impliment class keyword
                //without new keyword we can't call constructor.
                // rule:- naming convention of obj is firstLatter should Capital


                <!-- <script>
                    class CreateUser {
                        constructor(fName, lName, email, age, address) {
                            this.fName = fName;
                            this.lName = lName;
                            this.email = email;
                            this.age = age;
                            this.address = address;

                        }
                        about() {
                            return (`my name is ${this.fName} and my age is ${this.age}`);
                        };
                        is18() {
                            return this.age >= 18;
                        };
                        sing() {
                            return 'ohh ohhh jane jana';
                        };
                        func(b) {
                            console.log(b);
                        };

                    }

                    const user2 = new CreateUser("Krishna", "Deshmukh", "krishna@gmail.com", 18, "pune");
                    const user3 = new CreateUser("sunny", "Kalaskar", "sunny@gmail.com", 18, "satara");
                    const user4 = new CreateUser("Ganesh", "patil", "ganesh@gmail.com", 15, "kolhapur");

                    console.log(user4.about());
                    console.log(user3.is18());
                    console.log(user2.sing());
                    console.log(user2);
                    console.log(Object.getPrototypeOf(user4));
                    user2.func("Krishna");
                </script> -->

                // class and extends , super()--parent class
                // class and extends example
                <!-- <script>
                    class Animal {
                        constructor(name, age) {
                            this.name = name;
                            this.age = age;
                        }
                        eat() {
                            return `${this.name} is eating`
                        }
                        isSuperCute() {
                            return this.age <= 2;
                        }
                        isCute() {
                            return true;
                        }
                    };
                    const animal1 = new Animal("tom", 4);
                    console.log(animal1);
                    console.log(animal1.eat());
                    console.log(animal1.isCute());

                    //new class for cat

                    class Cat {
                        constructor(name, age) {
                            this.name = name;
                            this.age = age;
                        }
                        eat() {
                            return `${this.name} is eating`
                        }
                        isSuperCute() {
                            return this.age <= 2;
                        }
                        isCute() {
                            return true;
                        }
                    };
                    const mickey = new Cat("kanya", 4);
                    console.log(mickey);
                    console.log(mickey.eat());
                    console.log(mickey.isSuperCute());

                </script> -->

                // use extends keyword
                <!-- <script>
                    class Animal {
                        constructor(name, age) {
                            this.name = name;
                            this.age = age;
                        }
                        eat() {
                            return `${this.name} is eating`
                        }
                        isSuperCute() {
                            return this.age <= 2;
                        }
                        isCute() {
                            return true;
                        }
                    };

                    class Cat extends Animal {
                    
                    };
                    const mickey = new Cat("kanya", 4);
                    console.log(mickey);
                    console.log(mickey.eat());
                    console.log(mickey.isSuperCute());
                </script> -->

                // super() keyword
                // super()class===>parent class()
                // use extends keyword
                // same method call from base class/sub class
                <!-- <script>
                    class Animal {
                        constructor(name, age) {
                            this.name = name;
                            this.age = age;
                        }
                        eat() {
                            return `${this.name} is eating`
                        }
                        isSuperCute() {
                            return this.age <= 2;
                        }
                        isCute() {
                            return true;
                        }
                    };

                    class Cat extends Animal {
                        constructor(name, age, speed) {
                            super(name, age);
                            this.speed = speed;
                        };
                        run() {
                            return `${this.name} is running at ${this.speed} kmph`;
                        };
                    };
                    const mickey = new Cat("kanya", 4, 20);
                    console.log(mickey.speed);
                    console.log(mickey.eat());
                    console.log(mickey.run());
                </script> -->

                //getter and setters===> call func witout ()
                // by using get keyword before func method then no need of use () for func calling
                // using get we can use function as properties.
                // by using set keyword we can set properties in function method

                <!-- <script>
                    class Person {
                        constructor(firstName, lastName, age) {
                            this.firstName = firstName;
                            this.lastName = lastName;
                            this.age = age;
                        };
                        get fullName() {
                            return `${this.firstName} ${this.lastName}`;
                        }
                        set fullName(fullName) {
                            const [firstName, lastName] = fullName.split(" ");
                            this.firstName = firstName;
                            this.lastName = lastName;

                        };
                    };
                    const person1 = new Person("Krishna", "Deshmukh", 28);
                    console.log(person1.fullName);
                    person1.fullName = "Ganesh Patil";
                    console.log(person1);
                    console.log(person1.firstName);
                </script> -->

                //ststic methods and properties===>direct access from class to method and prop
                <!-- <script>
                    class Person {
                        constructor(firstName, lastName, age) {
                            this.firstName = firstName;
                            this.lastName = lastName;
                            this.age = age;
                        };
                        static classInfo() {
                            return `this is Person class from ststic method`;
                        };

                        static desc = "ststic property access from class";

                        get fullName() {
                            return `${this.firstName} ${this.lastName}`;
                        }
                        set fullName(fullName) {
                            const [firstName, lastName] = fullName.split(" ");
                            this.firstName = firstName;
                            this.lastName = lastName;

                        };
                    };
                    const person1 = new Person("Krishna", "Deshmukh", 28);
                    console.log(person1.fullName);
                    console.log(Person.classInfo());
                    console.log(Person.desc);
                </script> -->

            </div>
        </div>
    </div>
    <script src="script/jquery-3.6.1.min.js"></script>
    <!-- <script src="./Script/side.js"></script> -->
</body>

</html>
