# Basic Operations

## Arthemic Operation

![](../../assets/arth_operation.png)

If you add *semicolon(;)* at the end, then it will not display the output.

![](../../assets/supress_operation.png)

To add comment use *percent(%)*.

## Assigning variable

![](../../assets/assignment_operation.png)

## Print / Display

```
>>> variable_name
>>> disp(variable_name)
>>> disp(sprintf('2 decimals: %0.2f', a))
```

## Changing Format

```
>>> format long  % 3.141592653589789
>>> format short % 3.1416
```

## Matrix

```
>>> A = [1,3; 4,6]
  1  3
  4  6 
>>> A = [1:1:3; 4:1:6]
  1  2  3
  4  5  6
```
*semicolon(;) tells the end of row.*  
*start_value:increment_value:end_value or start_value:end_value it will increment by one.*  

for creating a matrix of ones you can use **ones(rows, cols)**  
similarly there is function **zeros(rows, cols)** to generate matrix containing only zeros.  
**rand(rows, cols)** will generate a matrix with random values between 0 and 1.  
**eye(int)** will generate an index matrix.  
