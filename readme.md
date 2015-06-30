# Exercise: Temperature Converter

Goal: create a program that can convert a temperature in Fahrenheit, Celsius or Kelvin to the other two units.
- Try the bonus goal if you have extra time!

## Setup

- Fork and clone this repo to your computer.
- Open this repo's `temp_converter.js` file.

or  

- In your inclass folder, create a file for this exercise: `touch temp_converter.js`
- Copy the code found in this repo's `temp_converter.js` file into the file on your computer.

## PART 1

### Instructions

1. Set the `fahrenheit` variable to a starting temperature.
2. Below that, write Javascript code that converts `fahrenheit` to its equivalent Celsius and Kelvin values.
  - Conversion formulae: [http://www.csgnetwork.com/temp2conv.html](http://www.csgnetwork.com/temp2conv.html)
3. Below that, `console.log` the starting and converted temperatures.
4. Repeat steps 1-3 for starting `celsius` and `kelvin` temperatures.
5. Test your program by running `$ node FILENAME` in the command line.
6. When you're done, save your code as a gist and post it in the Slack classroom channel.

Your program will look something like this for each starting temperature...

  ```javascript
  // Starting temperature
  var fahrenheit = STARTING_TEMP;

  // Conversion code
  var fahrenheitToCelsius = ...;
  var fahrenheitToKelvin = ...;

  // Print to console
  console.log( "Fahrenheit: " + ... );
  console.log( "Celsius: " + ... );
  console.log( "Kelvin: " + ... );
  ```

Your command line output will look something like this...

  ```
  Fahrenheit: STARTING_TEMP F
  Celsius: CONVERTED_TEMP C
  Kelvin: CONVERTED_TEMP K
  ```

### Bonus

Use conditionals so that your program only prints out the converted temperatures for one starting value.

## PART 2

Change you code from Part I so that when you convert a temperature, that new value is stored in an array. You will create an array for each temperature.

When you `console.log` the temperatures, do that by accessing values in the array.

### Bonus 1

Use a `for` or `while` loop to print out the conversion results for each temperature. It's OK if you need to simplify your `console.log` statements and remove strings.

### Bonus 2

Implemenent the conditionals from the Part I bonus if you haven't already!
