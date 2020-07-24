[![CraigDoesData][logo]][link]

[logo]: https://www.craigdoesdata.de/img/logo/logo.png
[link]: https://www.craigdoesdata.de/


# Making Bar Chart Races in Matplotlib using 'gif' and 'bar-chart-race' packages
Data visualisation project aiming to create an animated Bar Chart Race.

## Introduction
After seeing lots of this type of visualisation going around on Twitter, I wanted to learn how it was done. I decided to use data from the [Gapminder Foundation](https://www.gapminder.org/) because their data is usually clean and easy to access and start playing around with. I used GDP per capita data for countries from 1800-2020.

My first attempt is uploaded as [this gif](https://github.com/thecraigd/Bar_Chart_Race/blob/master/race%20top%2010%20100ms%20ggplot-style.gif), based on the code in the workbook [income_self.ipynb](https://github.com/thecraigd/Bar_Chart_Race/blob/master/Income_self.ipynb). This version is rudimentary but effective. It shows clearly the trend over time and communicates clearly enough the main points, but it is jerky and lacks the smooth animations when one country overtakes another.

The day I posted mine on [twitter](https://twitter.com/craigdoesdata/status/1255228501248151556) I saw that [Ted Petrou](https://twitter.com/TedPetrou) had released a new package, bar-chart-race, to make it easy to do the same thing. So I gave it a try using that. 

This resulted in [this video](https://github.com/thecraigd/Bar_Chart_Race/blob/master/income.mp4), based on the code in the notebook [income-bar-chart-race-package.ipynb](https://github.com/thecraigd/Bar_Chart_Race/blob/master/income-bar-chart-race-package.ipynb) This creates a nice animation with smooth transitions when countries change places, with significantly less effort on the part of the user.

This is undoubtedly a more polished end product, but I found the process of creating my own bar chart race (of sorts, there is some argument about the criteria that must be met to merit the title) extremely useful in giving practice creating a function which produces a chart based on data, then looping over it to create each frame of the animation. 

I enjoyed this project, and hope you have fun playing with the code too.

#### Project status - Complete


### Methods used
* Data visualisation

### Technologies used
* Jupyter Notebook
* [bar-chart-race](https://pypi.org/project/bar-chart-race/)
* pandas
* [gif](https://pypi.org/project/gif/) (python package)


### Data Sources

Inflation-adjusted GDP per capita data sourced from [Gapminder](www.gapminder.org), stored in the root folder of [this repoistory](https://github.com/thecraigd/Bar_Chart_Race) as [income_per_person_gdppercapita_ppp_inflation_adjusted.csv](https://github.com/thecraigd/Bar_Chart_Race/blob/master/income_per_person_gdppercapita_ppp_inflation_adjusted.csv)


### Getting started

1. Clone this repo (for help see this [tutorial](https://help.github.com/articles/cloning-a-repository/)).
2. Raw Data is kept in the CSV file in the root folder of this repo.
3. All code is contained within the 'Featured Notebooks' listed below.


## Featured Notebooks
* [income_self](https://github.com/thecraigd/Bar_Chart_Race/blob/master/Income_self.ipynb)
* [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/thecraigd/Bar_Chart_Race/master?filepath=https%3A%2F%2Fgithub.com%2Fthecraigd%2FBar_Chart_Race%2Fblob%2Fmaster%2FIncome_self.ipynb)


* [income-bar-chart-race-package](https://github.com/thecraigd/Bar_Chart_Race/blob/master/income-bar-chart-race-package.ipynb)
* [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/thecraigd/Bar_Chart_Race/master?filepath=https%3A%2F%2Fgithub.com%2Fthecraigd%2FBar_Chart_Race%2Fblob%2Fmaster%2Fincome-bar-chart-race-package.ipynb)



## Contact
All feedback is warmly received. Craig Dickson can be contacted via [Twitter](https://twitter.com/craigdoesdata) as @craigdoesdata.
Visit www.craigdoesdata.de or follow me here on GitHub to see my other projects.

