## We have following steps:

## First you need to install typescript

npm install -g typescript
## Create one file helloworld.ts

function hello(person){
   return "Hello, " + person;
}
let user = "Aamod Tiwari";
const result = hello(user);
console.log("Result", result)
## Open command prompt and type the following command

tsc helloworld.ts
## Again run the command

node helloworld.js
## Result will display on console