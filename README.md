# Project Guru

 Project Guru wanted to explore the world! Our project was to study the impact of migration on a countries GDP. While conducting our initial research, we were able to find the amount of cash remittances and percentage in relation to the country's GDP. Our hypothesis: The impact of cash remittances to GDP is more significant in countries with higher numbers of migration. Using United Nations and World Bank data we were able to test this hypothesis and consider factors outside of our original scope.  Additional factors, such as a country’s level of income, lead us to more thorough analysis and allowed us to test our hypothesis in many different environments. 

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

Obviously you will need python and Jupyter Notebooks. Additionally, you will require the following libraries

1. Pandas
2. Numpy
3. Matplotlibs
4. geopandas
5. plotly
6. plotly-orca


### Installing

You can install your libraries using  pip:
* pip install sklearn-pandas
	
or using conda:
* conda install plotly

Now, plotly-orca is little bit different. You will need to:
* conda install -c plotly plotly-orca

Last but not least, download "Project-Guru" to a local directory

## Running the tests

1. Start your python enviornment
2. Open file "clean_project_data.ipynb" in a Jupyter notebook
3. Execute the code in the notebook. Once this notebook has been executed; the necessary files for the other 3 will be generated
4. Open any of the other files (Plot_Maps.ipynb, Plot_GDPMigrant_Data.ipynb, Chi Square.ipynb) and execute it. The charts will be sent to screen.

Note that the results all resulst will be saved on disk in addition to showinh then on the scree. The files will be in:
* Images directory - All charts (png-type files) will be stored in this directory
* Output directory - All data files (CSV files) will be stored in this directory


## Built With

* [Pandas](https://pandas.pydata.org/) - Used to clean and analyze data 
* [Numpy](https://numpy.org/) - Used to run calsulations (data analysis)
* [Matplotlib](https://matplotlib.org/) - Used to generate graphical plots
* [GeoPandas](http://geopandas.org/) - Used to analyze migrations data and create maps
* [Plotly] (https://plot.ly/) - Used to create complex visualizations
* [PlotlyOrca](https://github.com/plotly/orca) - Used to generate images(png)

## Contributing

Please read [CONTRIBUTING.md](https://gist.github.com/PurpleBooth/b24679402957c63ec426) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning

v 1.0

## Authors

* Donicia Williams
* Nithya Iyengar
* Martha Aguilar

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Matplotlib documentation for its broken axis example

