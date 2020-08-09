# Plotting Data

**Let's take two variable and plot them in octave**

![](../../assets/plot_them.png)

**To plot on top of the current plotted data**

![](../../assets/hold_on.png)
![](../../assets/plot_on_top.png)

**Labeling**

![](../../assets/xlabel.png)
![](../../assets/ylabel.png)
![](../../assets/add_legend.png)
![](../../assets/add_title.png)

**Saving the current graph**

```
>>> print -dpng 'some_name.png'
```

**To close the current plotted data**

```
>>> close
```

**Plotting different data on different graph**

```
>>> figure(some_int)
>>> plot(x, y)
>>> close some_int
```

**Subplotting**

![](../../assets/subplotting.png)
![](../../assets/subplotting_plot.png)
![](../../assets/selecting_2nd_section.png)
![](../../assets/subplotting_plot2.png)

**Changing axis**

![](../../assets/changing_axis.png)

**Clear plotted graph**

```
>>> clf;
```

TODO: *Add details about imagesc()*