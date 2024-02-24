# ASTR352 Jupyter Activities
 Python (Jupyter) based activities used in ASTR352 (Extragalactic Data Science) 0.5 credit upper-level undergraduate class at Haverford College.

 These examples were practiced and/or developed in a [Sciserver.org](https://apps.sciserver.org/dashboard/) Compute Jupyter Notebook. 

 1. Computing Galactic Orbits of Stars with Gala [Astropy tutorial](https://learn.astropy.org/tutorials/gaia-galactic-orbits.html) 

 2. Galaxy Populations and Data Visualisation - a Notebook in this repository. This uses SciServer and Casjobs to query SDSS data, learn about sample selection, data frames (pandas), and some examples of data visualisation with matplotlib.

 3. Galaxy Kinematics Scaling Relations and MaNGA Data - a Notebook in this repository. This explores MaNGA data mostly related to kinematics, and also does some statistics with line fits, comparing distributions, exploring the Tully-Fisher relation and how different measures of kinematics differ. 

Other ideas: 
   * We will explore [SDSS-IV MaNGA](https://www.sdss.org/dr16/manga/) spectral maps of galaxies with the code, Marvin
   * Check out [Marvin Web](https://dr16.sdss.org/marvin/) and pick a galaxy you like. 
   * Do the [Plotting Tutorial: The Basics of Plotting in Marvin](https://sdss-marvin.readthedocs.io/en/stable/tutorials/plotting-tutorial.html), and make the plots for your chosen galaxy. 
   * Pick one of the [Science Exercises](https://sdss-marvin.readthedocs.io/en/stable/tutorials/exercises.html) to try out. 
 
 4. Choose your own adventure: 
   * Image contour overlays (Contour Image Overlay.ipynb) works through some of this. Not very finished yet! 
      * THINGS (HI 21cm data): https://www2.mpia-hd.mpg.de/THINGS/Data.html (moment 0 is the intensity map). 
      * Digitised Sky Survey (for optical FITS images): https://archive.eso.org/dss/dss
      * List of sources for astronomical FITS files: https://fits.gsfc.nasa.gov/fits_samples.html
      * Astropy, read a FITS image and plot: https://docs.astropy.org/en/stable/generated/examples/io/plot_fits-image.html#sphx-glr-generated-examples-io-plot-fits-image-py
      * Astropy: read RA and Dec from the header of a FITS file: https://learn.astropy.org/tutorials/celestial_coords1.html
      * Astropy overlay contours: https://docs.astropy.org/en/stable/visualization/wcsaxes/images_contours.html
      * Astropy make 3 colour image: https://docs.astropy.org/en/stable/visualization/rgb.html
      * Astropy FITS cube: https://learn.astropy.org/tutorials/FITS-cubes.html

   * Large Scale structure in simulations and/or observations
      * Explore the Indra Simulations (accessed on SciServer with "indra-tools": https://github.com/bfalck/indra-tools) https://www.sciserver.org/datasets/
      * Large Scale structure in SDSS: https://github.com/ritatojeiro/SDSSEPO/blob/master/AS1001_SDSSEPO.ipynb (some of this will be a bit familiar from the Galaxy populations notebook - but this focuses more on the LSS and environment). 
      * Two-point correlation functions (tutorial found on Github which works through this statistical method which is often used on LSS): https://github.com/fjaviersanchez/corrfunc_tutorial


 ## Other Resources 
Here are a bunch of links to other Astronomical Python Tutorials and/or Examples, some of which have been directly used in the development of materials for this class. 

 * [Learn Astropy](https://learn.astropy.org/) - a variety of Tutorials, Examples and Documentation about Astropy. 
 * [Python for Astronomers](https://prappleizer.github.io/index.html) (free online textbook, which contains some tutorials/examples)
 *  Britt Lundgren's [SciServer Based Astronomy Class](https://github.com/brittlundgren/SDSS-EPO) - tested in an upper level astronomy class at UNC Asheville. 
 * Intro to Python by Colette Salyk: https://github.com/csalyk/python_tutorial/blob/master/python_tutorial.ipynb
 * AstroEdu Package: https://github.com/astroDimitrios/astroedu 
 * [Python Data Science](https://github.com/jakevdp/PythonDataScienceHandbook) - Github repository of this textbook by Jake VanderPlas
 * Try out LSSGalPy for interactive visualisation: https://github.com/margudo/LSSGALPY
 * NOIR Data Lab: https://datalab.noirlab.edu/docs/manual/UsingTheNOAODataLab/ScienceExamples

