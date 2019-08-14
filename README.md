## Animated Graphs

This repository has been created to explore some ways to animate data graphs. This is a very interesting way to visualize certain type of phenomena which involve time as a key variable, such as trading prizes or temperature changes over the years.

The code can be seen in this same repository, written in this [jupyter notebook](https://github.com/carlosdavila91/animating_graphs/blob/master/animating-scatterplot.ipynb).

### Data

Data has been created randomly for this purpose. Some `numpy.random` methods and functions were used for learning purposes.

### Method 1 and 2: using `pyplot.express` and `bubbly.bubbleplot`.

Those two methods are based on `pyplot` and give a nice-looking animated figure. All the aesthetics are implemented and are easy to play with.

### Method 3: using `matplotlib.pyplot`

This a common library used to animate plots. As you can see, the [matplotlib website](https://matplotlib.org/api/animation_api.html#examples) documents several examples of how to do this.

### Conclusions

#### Methods 1 and 2
* They are really similar one of each other
* Animated figures created with these extensions of `Pyplot` cannot be exported to a format as `png` or `gif` which leads to less control of the result.

#### Method 3
* It may require a little bit more code than the other two.
* It is easier to control the result. In this case, the set of `.png` images were easily transformed into a `.gif` document.
