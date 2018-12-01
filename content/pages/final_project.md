Title: Final Project
Summary: Guidelines and expectations for final project

Final projects must be completed individually.
The final project is due Thursday, Dec 6 (the final day of class). Everyone will
give a five minute overview of the project in class. In order to fit everyone in,
four people will have to present their work in progress on Tuesday, Dec. 4
(volunteers welcome).

### Learning Goals

The goal of the final project is to assess your ability to combine and apply
the skills you have learned in class in the context of a real-world research
problem. Our class has mostly focused on tools for data analysis and
visualization, so this must be the focus of your final project. Specifically,
we seek to assess your ability to do the following tasks:

- Discover and download real datasets in standard formats (e.g. CSV, netCDF)
- Load the data into pandas or xarray, performing any necessary data cleanup
  (dealing with missing values, proper time encoding, etc.) along the way.
- Perform realistic scientific calculation involving, for example tasks such as
  grouping, aggregating, and applying mathematical formulas.
- Visualize your results in well-formatted plots.

### Dataset Requirements

Your datasets can involve data collected by yourself or your lab, or can
come from a public data repository. Ideally, your choice of dataset should be
driven by your research. It is acceptable (and encouraged) to have your final
project for this class involve an ongoing research project.
_However, it is not acceptable to have your final project overlap with the final
project for another class._

If you don't know what dataset to use, here are a couple of links to get you
started:

- [IRI Data Library](http://iridl.ldeo.columbia.edu)
- [USGS Data Catalog](https://data.usgs.gov/datacatalog/)
- [NOAA National Climate Data Center](https://www.ncdc.noaa.gov/)
- [NASA Earth Science Data](https://earthdata.nasa.gov/)

You may use just one dataset, or you may choose to combine multiple datasets,
depending on your scientific question.

### Analysis Requirements

The goal here is the same as with any science project: to use the data to
investigate a scientific question or hypothesis. In order to succeed on the
project, you will have to draw on your experience _outside_ our class, from
your science-focused classes or independent research, in order to define a
scientifically interesting question. It is also acceptable to use this project
to reproduce the results from a published study that you find interesting,
provided you have access to the original data.

Whatever you choose, you should _clearly define a hypothesis or scientific
question that you aim to investigate with your analysis_. This will determine
what you have to do.

The results of this analysis will be figures. Beautiful figures which clearly
provide answers to your question / hypothesis. Your notebook should contain
at least 4 and no more than 8 figures. If you have closer to 4, they
should be complex, multi-panel figures. All figures must have titles, clearly
labeled axes, informative colormaps / colorbars, and legends, where
appropriate.

### Technical Requirements

Your final project must meet the following technical requirements

- A _single jupyter notebook_
- Stored in a standalone public github repo
- All data is either stored in the repo itself or downloaded / accessed from
  within the notebook (no manual download steps)
- Complete explanatory text / equations included in the notebook as markdown
  cells
- Notebook must execute in sequence with no errors
- The whole github repo must be configured to run on
  [mybinder.org](https://mybinder.org) or, for analysis involving dask,
  [binder.pangeo.io](http://binder.pangeo.io)

You *must* use either pandas or xarray (or both) in some part of your project.
You _may_ use other scientific python libraries as well, if you wish, to
facilitate some analysis that is not possible with xarray / pandas alone. Some
libraries you may wish to consider are:

- [SciPy](https://docs.scipy.org/doc/scipy/reference/) for interpolation,
  signal processing, spectral analysis, linear algebra, and other general
  purpose scientific computing routines
- [Statsmodels](https://github.com/statsmodels/statsmodels) for advanced
  statistical analysis
- [Scikit-image](https://scikit-image.org/) for image processing
- [Scikit-learn](https://scikit-learn.org/stable/) for machine learning
- [XGCM](https://xgcm.readthedocs.io/en/latest/) for working with
  finite-volume data from general circulation models
- [XESMF](https://xesmf.readthedocs.io/en/latest/) for regridding of gridded
  data
- [Pyresample](https://pyresample.readthedocs.io/en/latest/) for resampling
  (reprojection) of satellite data
- [EOFS](https://ajdawson.github.io/eofs/) for empirical orthogonal function
  analysis
- [windspharm](https://ajdawson.github.io/windspharm/latest/) for spherical
  harmonic analysis of global atmospheric wind data
- [metpy](https://unidata.github.io/MetPy/latest/index.html) a collection of
  tools in Python for reading, visualizing, and performing calculations with
  weather data

### Project Approval

You must have your dataset(s) and general scope for your project improved by
the instructor. This must be done by Tuesday, Nov. 20. The approval process
works like this:

- Create a new public github repo for your project
- Add a `README.md` file which contains the scientific question / hypothesis
  you plan to investigate, links to the relevant datasets, and a three
  sentence summary of the analysis you plan to do.
- Email the link to this repository to the instructor <rpa@ldeo.columbia.edu>
  with the title "RCES Final Project Proposal"
  
### In-Class Presentations

You are asked to give a 5-minute presentation about your project. Do not
prepare any slides. Instead, make your presentation by opening your notebook
from GitHub on the presentation computer and walking us through parts of it.
Your presentation should be concise and cover the following topics:

- What data did you analyze and how did you load it?
- What is the most interesting figure you made? (Show us the figure.)
- What was the biggest challenge you faced in completing your project.

_Don't forget to make your project repo **public**; otherwise we won't be
able to see it._
