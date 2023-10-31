# Notes:

## Git -

I learned how to use git effectively with visual studio code. I learned how to create and clone a new repo, make changes on my machine and push it to the main branch, and resolve conflicts when making pull requests.

## Midterm

### Console

chmod -  change permissions
man - usermanual for commands
ps - process status, current processes info
wget - download from internet
sudo - superuser

ssh -i main.pem ubuntu@matchmaster.click

-a   -  all, shows hidden
-l   -  long format
-la  -  all files long

### HTML

```
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8" />
        <meta name="viewport" content="width=device-width, initial-scale=1.0" />
        <title>hi</title>
    </head>
```

forward, p, ol, ul, h1 h2 h3
```
 link
 <a href="gg.html">link text</a>

 image
 <img src="bb.jpg" alt="" style="width:%; height:%;">
```

div - spreads whole width, block level (new line). 

block level - div, h1 2 3, p, list, li, header, footer, form, table, address, blockquote, nav, section, article, pre,
css display can change it



### CSS

link css file in html header section
```
<link rel="stylesheet" type="text/css" href="path/to/your/styles.css">
```
higher speficity takes priority. later rules take priority.

content- width height
padding - between element and border. top-r-b-l
border
margin - space outside of border. in beteween elements. transparent.

-# is id selector. id is unique. only one object per id.
. is class selector. class applied to many objects

flexbox-
direction default rows, change with flex-direction
all items attempt fit one line, flex-wrap

```
html
<div class="container">
    <div class="item">Item 1</div>
    <div class="item">Item 2</div>
    <div class="item">Item 3</div>
</div>

css flex
.container {
    display: flex;
    justify-content: center; /* Horizontally center the items */
    align-items: center;     /* Vertically center the items */
    flex-direction: column;
    flex-wrap: wrap;
}
/* Styling individual items */
.item {
    padding: 20px;           /* Add some space around each item */
    margin: 10px;            /* Add some space between items */
    border: 1px solid black; /* Add a border for visualization */
    flex-grow: 1;            /* Allow items to grow and take up available space */
}


```

change color
```
div {
    background-color: red;
}

```

### JS

linked vs embed
 ```
<script src="path/to/your/script.js"></script>

 <script>
 document.getElementById('content').innerText = 'crow';
 </script>
 ```

 promises
 ```
 let myPromise = new Promise(function(resolve, reject) {
  // Asynchronous operation
  if (/* operation successful */) {
    resolve(value);  // Fulfill the promise with a value
  } else {
    reject(error);  // Reject the promise with an error
  }
});
myPromise
    .then(result => {
        console.log(result);  // "Success!"
    })
    .catch(error => {
        console.log(error);  // "Error!"
    });
```

 event listerners - element.addEventListener(event -click-, function, useCapture);


var element = document.getElementById('byu');
element.style.color = 'green'

add new value to obj - obj.newName = "jj"

json - key value pairs. keys strings, values other data types

```
const greet = function(name) {
    return "Hello, " + name + "!";
};
=
const greet = (name) => {
    return "Hello, " + name + "!";
};
=
const greet = name => "Hello, " + name + "!";
```


```
maps -- const newArray = oldArray.map(function(currentValue, index, array) {
    // Return element for newArray
});
const numbers = [1, 2, 3, 4];
const squared = numbers.map(num => num * num);
console.log(squared);  // [1, 4, 9, 16]

```



creating object - 
```
let (also use var, const) person = {
    firstName: "John",
    lastName: "Doe",
    age: 30,
    isStudent: false,
    address: {
        street: "123 Main St",
        city: "Anytown",
        zip: "12345"
    },
};
let person = new Object();
person.firstName = "John";
person.lastName = "Doe";
person.age = 30;

----

if(c){

}else if (oc){

}else{

}

for(let i = 0; i < 7; ++i){
    console.log(i);
}

while(c){

}
 o="dog"
switch(o){
    case "dog":
        console.log("bark");
        break;
    case "cat":
        break;
    default:
        break;
}


```


### DNS

banana.fruit.bozo.click
top - .click
root - bozo
sub - banana/fruit (bozo)


need cert.

A -> IP
CNAME -> A

80 - http
443 - https
22 - ssh