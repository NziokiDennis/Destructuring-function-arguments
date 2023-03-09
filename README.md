# Destructuring-function-arguments
let user = {
 name: 'Jill',
 age: 33,
 profession: 'Pilot'
} 
function greeting ({name, profession}) {
 console.log(`Hello, ${name} the ${profession}`)
}
greeting(user)
This also works for arrays:
let parts = ["Hello", "World!"];
function greeting([first, second]) {
 console.log(`${first} ${second}`);
}
