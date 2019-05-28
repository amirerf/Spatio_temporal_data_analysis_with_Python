# Spatio_temporal_data_analysis_with_Python


For many applications in science and engineering, the properties of a system or a single variable can change across both time and space. Studying/modeling of such systems requires collecting and analyzing multidimensional data with at least one temporal and one spatial dimension. The spatiotemporal data analysis has become an emerging research area in many fields including geography, physics, astronomy, earth science, epidemiology, biology, healthcare, transportation, environmental science, earthquake and structural engineering, social science, marketing, and economics mostly thanks to the development and recent advancement of computational infrastructures/techniques allowing for reliable storage and fast analysis of large spatiotemporal datasets. 

In earth system science, multidimensional data can have up to 3 spatial and one temporal dimensions. Depending on the size of domain, temporal length of the data, and the spatiotemporal resolution, these data may become very large and require specific techniques/tools to store, transfer, read, analyze, and visualize. One such tool is the NCAR Command Language, NCL, an interpreted computer language developed by the National Center for Atmospheric Research (NCAR). NCL is specifically designed for scientific data analysis and visualization and is open source, portable, free, and can be installed on Mac and Linux systems using Conda environment. You can find more information about NCL and some useful coding examples at the following address: 

http://www.ncl.ucar.edu

Recently, NCAR has announced its decision to adopt python as the scripting language platform of choice for future development of analysis and visualization tools. As a part of the adaptation process, NCL is going to be integrated into the python ecosystem and NCL functions will be packaged into python libraries. Currently, there are three libraries, namely PyNIO, PyNGL, WRF-Python already released and one more library, PyNComp, scheduled to be released in summer 2019. Among these packages, PyNIO uses NumPy to facilitate read/write access to a variety of file formats including binary, ASCII, netCDF, HDF, HDF-EOS, GRIB, and OGR files (shapefiles, MapInfo, GMT, and Tiger). PyNGL translates NCL graphic routine into python and is developed for array processing and visualizing scientific data, with an emphasis on geospatial data and high quality 2D maps. The PyNcomp module, currently under development, is going to contain the NCL computational routines that are widely used for conducting spatiotemporal analysis on multidimension arrays. To read more about these libraries and the new NCAR policy, you can visit the following pages:

https://www.ncl.ucar.edu/Document/Pivot_to_Python/ 

http://www.ncl.ucar.edu/Training/Tutorials/WRF_Users_Workshop/python.shtml

https://www.ncl.ucar.edu/Document/Pivot_to_Python/NCL_Pivot_to_Python_Roadmap_and_Software_Diagram.pdf

The following repository also contains several examples about migrating from NCL to Python:

https://www.ncl.ucar.edu/Applications/NCL_to_Python/

In accordance with the NCAR recent move, I also started to switch to these libraries for conducting geospatial data analysis in python and regularly share some sample codes that I use in my current research. These sample codes are publicly accessible at the following github repo:

https://github.com/amirerf/Spatio_temporal_data_analysis_with_Python

Besides PyNIO and PyNGL, xarray is the other library that I extensively use in conducting spatiotemporal analysis. Xarray is an open source python package specifically developed for working with labelled multi-dimensional arrays in python. Xarray structure is very similar to NumPy and heavily borrows from Pandas with a distinct advantage that it allows the use of labeled arrays in the form of dimensions, coordinates and attributes on top of raw NumPy-like arrays. As a result, xarray can seamlessly work with netCDF files and tightly integrate with dask for parallel computing. You can find more information about xarray here:

http://xarray.pydata.org/en/stable/index.html



