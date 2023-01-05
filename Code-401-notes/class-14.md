# Class 14 - Data Visualization

## Reading

### Matplotlib Tutorial
[Matplotlib Tutorial](https://github.com/rougier/matplotlib-tutorial)
- a library for making 2d plots in Python
- steps to get started
1. initialize
    
    ```
    import numpy as np
    import matplotlib.pyplot as plt
    ```

2. Prepare

    ```
    x = np.linspace(0, 4*np.pi, 1000)
    y = np.sin(x)
    ```

3. Render

    ```
    fig, ax = plt.subplots()
    ax.plot(x, y)
    fig.show()
    ```

4. Observe - "cool graph here

- kinds of plots available
    - scatter plot - ax.scatter(x,y)
    - bar - ax.bar(x, y)
    - ax.imshow(z)
    - ax.contourf(Z)
    - ax.pie(Z)
    - ax.hist(Z)
    - ax.errorbar(x, y, y/4)
    - ax.boxplot(Z)

## Bookmark and review
[Seaborn Tutorial](https://seaborn.pydata.org/tutorial.html)

[Bokeh Tutorial](https://mybinder.org/v2/gh/bokeh/bokeh-notebooks/master?filepath=tutorial%2F00%20-%20Introduction%20and%20Setup.ipynb)

## Cheat Sheet
[Seaborn Cheat Sheet](https://s3.amazonaws.com/assets.datacamp.com/blog_assets/Python_Seaborn_Cheat_Sheet.pdf)

[Matplotlib for beginners cheatsheet](https://matplotlib.org/cheatsheets/_images/handout-beginner.png)

## Things I want to know more about
- still have a lot to learn about matplot and how to manipulate datasets