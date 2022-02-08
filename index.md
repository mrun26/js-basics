```js
//1st problem
let marks;
function score(marks){
    if(marks>=90 && marks<=100){
    console.log("The Score represented as a letter grade : A")
}else if(marks>=80 && marks<=89){
    console.log("The Score represented as a letter grade : B ")
}else if(marks>=70 && marks<=79){
    console.log(" The Score represented as a letter grade : C ")
}else if(marks>=60 && marks<=69){
    console.log("The Score represented as a letter grade : D")
}else if(marks>=0 && marks<=59){
    console.log("The Score represented as a letter grade : F ")
}else{
    console.log("Enter the Marks between 0-100")
}
}

//2nd Problem
function dogAge( age){
    let calc = age*7;
console.log("Your doggie is "+calc+"years old in dog years!")
}
function dogAge(age){
    let calc = age*7;
console.log("Your doggie is "+calc+"years old in dog years!")
}
function conRate(rate)
{
 let conversion = rate/7;
    console.log("Conversion rate of human is " +conversion+ " years to dog years")
}
```