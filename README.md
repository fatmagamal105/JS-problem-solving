# JS-problem-solving

1- count the number of properties in an object
var data = {a: 1, b: 2, c: 3};

var count = 0;

for (var key in data) {

    count++;

}

console.log(count); // prints 3 to the console
