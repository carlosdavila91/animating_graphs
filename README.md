## Animated Graphs

This repository has been created to explore some ways to animate data graphs. This is a very interesting way to visualize certain type of phenomena which involve time as a key variable, such as trading prizes or temperature changes over the years.

The code can be seen in this same repository, written in this [jupyter notebook](https://github.com/carlosdavila91/animating_graphs/blob/master/animating-scatterplot.ipynb).

### Data

Data has been created randomly for this exercise. Some `numpy.random` methods and functions were used for learning purposes.

### Method 1: using `matplotlib.pyplot`

This a common library used to animate plots. As you can see, the [matplotlib website](https://matplotlib.org/api/animation_api.html#examples) documents several examples of how to do this.

### Method 2: using `pyplot.express`

This method give a nice-looking animated figure. All the aesthetics are implemented and are easy to play with.

### Conclusions

#### Method 1
* It may require a little bit more code than the other.
* It offers more options to customize the result.
* It is not interactive

#### Method 2
* With few code you get a nice data visualization
* Higher cost to place the result in a blog post
* Allows interacting with the plot