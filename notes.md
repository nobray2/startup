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



### CSS
padding - between element and border. top-r-b-l
margin - space outside of border. in beteween elements.


### JS
 ```
 <script>
 document.getElementById('content').innerText = 'crow';
 </script>
 ```

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