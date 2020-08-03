# Polynomial Regression

Let's take an example of housing price.  
so, in the data we have given the **width** and **height** of the houses and we need to predict the price. Here, we can create a new feature **area** whose value we can get using the above two features i.e. width and length.  

so, in this case  
x<sub>3</sub> = x<sub>1</sub> * x<sub>2</sub>  

Sometime, by defining new feature you can get a better model.  

Also in case if the normal hypothesis function dosen't fit the data well you can also change the behaviour or curve of your hypothesis function by making it a qudratic, cubic or square root func<sup>n</sup>

let, our hypothesis func<sup>n</sup>

h(&theta;) = &theta;<sub>0</sub> + &theta;<sub>1</sub>x<sub>1</sub>  

qudratic func<sup>n</sup> for this hypothesis  

h(&theta;) = &theta;<sub>0</sub> + &theta;<sub>1</sub>x<sub>1</sub> + &theta;<sub>1</sub>x<sub>1</sub><sup>2</sup>  

Cubic function for this hypothesis  

h(&theta;) = &theta;<sub>0</sub> + &theta;<sub>1</sub>x<sub>1</sub> + &theta;<sub>1</sub>x<sub>1</sub><sup>2</sup> + &theta;<sub>2</sub>x<sub>1</sub><sup>3</sup>  

>NOTE: If you choose your features this way then feature scaling will become very impostant
