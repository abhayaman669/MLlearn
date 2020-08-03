# Feature Scaling

In feature scaling we make sure that all the features are on a similar scale.

for example,

let, x<sub>1</sub> = size of house = 0 - 2000
and, x<sub>2</sub> = no. of bedroom = 0 - 5

If we plot cost function graph for this the graph will be very skinny as given in the image below. If we run gradient descent on this cost function, it will take long time to find the minimum value.

![](../../assets/steep_cost_func_graph.png)

To fix this issue we can scale the feature. for that we can use this fourmular

![](../../assets/feature_scaling_fourmulae.png)

where

x<sub>i</sub> = particular traniee input value  
s = size of range of values

for the above example s for x<sub>1</sub> will be 2000 and for x<sub>2</sub> will be 5.

So, our goal in feature scaling should be to get every feature into apporiximate of  
-1 &#8804; x<sub>i</sub> &#8804; 1

We can also use **mean normalisation** to scale feature.

![](../../assets/mean_norm_eq.png)

here

&#956; is the average of all the values for feature x<sub>i</sub>

