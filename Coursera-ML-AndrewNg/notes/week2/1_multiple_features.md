# Multiple Features

In **week1** we were taking dataset having only feature. For example we have area of the house as a feature and the price of that house as output.

| Area | Price (in 1000$) |
|------|-------|
| 500 | 100 |
| 600 | 200 |
| 700 | 300 |
| 800 | 400 |
| 900 | 500 |


But, we can have multiple features, for example area of house, age of house and all the other factors that can possibly affect the price of a house. For that our dataset will look something like this.

| Area | age (years) | Price (in 1000$) |
|------|-------|-------|
| 500 | 1 | 100 |
| 600 | 2 | 200 |
| 700 | 3 | 300 |
| 800 | 4 | 400 |
| 900 | 5 | 500 |

Here we have 2 features, area and age of house.

Here are some of the representation that we will use

m = training examples (m=5 for the above example)  
n = no. of features (n=2 for the above example)  
x<sup>(i)</sup> = Input training example  
x<sup>(i)</sup><sub>j</sub> = value of feature j for the i<sup>th</sup> training example  

## Hypothesis (with multiple feature)

Till now we were using hypothesis which only contain one feature.

h<sub>&theta;</sub>(x) =  &theta;<sub>0</sub> + &theta;<sub>1</sub>x

For multiple feature our hypothesis will be:

h<sub>&theta;</sub>(x) =  &theta;<sub>0</sub> + &theta;<sub>1</sub>x<sub>1</sub> + &theta;<sub>2</sub>x<sub>2</sub> + ... + &theta;<sub>n</sub>x<sub>n</sub>

**Let's make our hypothesis more simplestic**

let take a new feature x<sub>0</sub> = 1  
also, feature vector i.e. X = vector(x<sub>0</sub>, x<sub>1</sub>, x<sub>2</sub>, ..., x<sub>n</sub>)  
and, parameter vector i.e. &theta; = vector(&theta;<sub>0</sub>, &theta;<sub>1</sub>, &theta;<sub>2</sub>, ..., &theta;<sub>n</sub>)  

now our hypothesis will be:

h<sub>&theta;</sub>(x) =  &theta;<sub>0</sub>x<sub>0</sub> + &theta;<sub>1</sub>x<sub>1</sub> + &theta;<sub>2</sub>x<sub>2</sub> + ... + &theta;<sub>n</sub>x<sub>n</sub>

the above hypothesis can also be written as,

h<sub>&theta;</sub>(x) = &theta;<sup>T</sup>X
