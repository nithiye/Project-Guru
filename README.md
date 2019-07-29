# Project Guru

One Paragraph of project description goes here

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

* [Dropwizard](http://www.dropwizard.io/1.0.2/docs/) - The web framework used
* [Maven](https://maven.apache.org/) - Dependency Management
* [ROME](https://rometools.github.io/rome/) - Used to generate RSS Feeds

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

