# Cost Function

Cost function helps in figuring out how to fit the best possible straight line to our data.

As we know:
h<sub>&theta;</sub>(x) =  &theta;<sub>0</sub> + &theta;<sub>1</sub>.x

where &theta;<sub>i's</sub> are the parameters.

## How to choose &theta;<sub>i's</sub>

For different value of &theta;<sub>i's</sub> you will have different hypothesis function here are some examples of hypothesis functions.

TODO: *Add examples for different hypothesis function with their graph*

We need to choose &theta;<sub>0</sub> and &theta;<sub>1</sub> so that h<sub>&theta;</sub>(x) is close to y for our training examples (x, y)

```
minimize &theta;<sub>0</sub> &theta;<sub>1</sub> = h<sub>&theta;</sub>(x) - y
```

lets try to minimize the square difference

```
minimize &theta;<sub>0</sub> &theta;<sub>1</sub> = (h<sub>&theta;</sub>(x) - y)<sup>2</sup>
```

To represent a particular training example

```
minimize &theta;<sub>0</sub> &theta;<sub>1</sub> = (h<sub>&theta;</sub>(x<sup>(i)</sup>) - y<sup>(i)</sup>)<sup>2</sup>
```

Let's add up all the training examples

```
minimize &theta;<sub>0</sub> &theta;<sub>1</sub> = (m&Sigma;i=1)(h<sub>&theta;</sub>(x<sup>(i)</sup>) - y<sup>(i)</sup>)<sup>2</sup>
```

Finally, let's take it's average and make it half

```
minimize &theta;<sub>0</sub> &theta;<sub>1</sub> = 1/(2m)(m&Sigma;i=1)(h<sub>&theta;</sub>(x<sup>(i)</sup>) - y<sup>i</sup>)<sup>2</sup>
```

here h<sub>&theta;</sub>(x<sup>(i)</sup>) =  &theta;<sub>0</sub> + &theta;<sub>1</sub>.x<sup>(i)</sup>

```
So **Cost Function** = J(&theta;<sub>0</sub>, &theta;<sub>1</sub>) = minimize &theta;<sub>0</sub> &theta;<sub>1</sub> = 1/(2m)(m&Sigma;i=1)(h<sub>&theta;</sub>(x<sup>(i)</sup>) - y<sup>(i)</sup>)<sup>2</sup>
```

This cost function is also known as the **Square Error Function**.