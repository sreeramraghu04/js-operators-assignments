# Javascript 

## Operators Assignment

1. What are operators in JavaScript?

   - Operators in JavaScript are special symbols used to perform operations on variables and values. They allow you to manipulate data and perform calculations.

2. Types of Operators in JavaScript?

   **Arithmetic Operators** – Perform mathematical calculations.

      - `+` (Addition)-> add values
      - `-` (Subtraction)-> subtract values
      - `*` (Multiplication)-> multiply values
      - `/` (Division)-> divide values
      - `%` (Modulus)-> remainder after division
      - `++` (Increment)-> increment value
      - `--` (Decrement)-> decrement value

   **Assignment Operators** – Assign values to variables.

      - `=` (Assign)-> assign value to variable
      - `+=` (Add and assign)-> add value to variable
      - `-=` (Subtract and assign)-> subtract value from variable
      - `*=` (Multiply and assign)-> multiply value to variable
      - `/=` (Divide and assign)-> divide value from variable
      - `^=` (Exponentiation assign)-> exponentiation value to variable

   **Comparison Operators** – Compare two values and return a boolean (`true` or `false`).

      - `==` (Equal to)-> check both are equal or not
      - `===` (Strict equal to)-> check with their data type
      - `!=` (Not equal to)-> check both are not equal or equal
      - `!==` (Strict not equal to)-> check with their data type
      - `>` (Greater than)-> check first value is greater than second value
      - `<` (Less than)-> check first value is less than second value
      - `>=` (Greater than or equal to)-> check first value is greater than or equal to second value
      - `<=` (Less than or equal to)-> check first value is less than or equal to second value
      - `?` (Ternary Operator)-> check condition is true or false

   **Logical Operators** – Used for logical operations.

      - `&&` (AND)-> check both are true
      - `||` (OR)-> check at least one is true
      - `!` (NOT)-> check condition is true or false

   **Order of Precedence** – The order in which operators are evaluated in an expression.

      - `()`-> Parentheses
      - `* / %`-> Multiplication, Division, Modulus
      - `+ -`-> Addition, Subtraction

   ***

# JavaScript Simple Quiz on Operators

1. The value of num1=?

   ``` js
   let num1 = 12;
   num1 /= 3;
   ```

   - Answer: 4

2. What does 'a' equal?

   ``` js
   let a = 17 % 4;
   ```

   - Answer: 1

3. What does x++ equal?

   ``` js
   let x=3;
   x++;
   ```

   - Answer: 4

4. Create a Fahrenheit to Celsius converter

   ``` js    
   c=((f-32)*5)/9;
   ```

   - Answer:
  
    ``` js
    let f = prompt('Enter the temperature in Fahrenheit: ');
    let c = ((f-32)*5)/9;
    console.log(`The temperature in Celsius is: ${c}`);
    ```

5. Create a discount percentage calculator

   ``` js
   discountpercentage=((mrp-sellingprice)*100)/mrp;
   ```

   - Answer:
  
    ``` js
    let mrp = prompt('Enter the MRP of the product: ');
    let sellingprice = prompt('Enter the selling price of the product: ');
    let discountpercentage = ((mrp-sellingprice)*100)/mrp;
    console.log(`The discount percentage is: ${discountpercentage}`);
    ```

6. Create a BMI calculator

   ``` js
   bmi=weight(kg)/(height(m)*height(m));
   ```

   - Answer:
  
    ``` js
    let weight = prompt('Enter your weight in kilograms: ');
    let height = prompt('Enter your height in meters: ');
    let bmi = weight/(height*height);
    console.log(`Your BMI is: ${bmi}`);
    ```
