# kelvin
The second
// The forecast today is 293 Kelvin
const kelvin = 240;
// celsius is kelvin minus 273
const celsius = kelvin - 273;
// fahrenheit is let variable because it will need to be reassigned/changed later
let fahrenheit = celsius * ( 9 / 5 ) + 32;
//Math.floor rounds down the fahrenheit.
fahrenheit = Math.floor(fahrenheit);
console.log(`The temperature is ${fahrenheit} degrees Fahrenheit.`)

let newton = celsius * ( 33 / 100 );
newton = Math.floor(newton);
console.log(`If you want it in Newtons, the temperature is ${newton}.`)
