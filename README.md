# stellar-classification
<br>

#### Stars are really just big balls of gas that emit light and heat. Astronomers study stars by looking at the light they emit, which tells them things like how bright the star is and what elements it's made of. Machine learning can help astronomers make sense of all this data by finding patterns and making predictions.
<br>

#### For example, imagine you're interested in finding stars that are similar to our Sun. You could use a machine learning model to look at things like the star's temperature, brightness, and chemical composition, and compare that to what we know about the Sun. The model could then use this information to predict which stars are most similar to the Sun, and display those results to you in an interface. This could help casual astronomers discover new stars that are similar to our own, which could give us more insight into how our solar system formed and how life might exist on other planets. Your machine learning model can compare the different models and display the results in an interactive way, allowing users to see which model performs best for their specific interests.

<br>
<br>
<br>


## Introduction:

<br>
<br>


#### The Sloan Digital Sky Survey (SDSS) is one of the largest astronomical surveys, providing detailed observational data for millions of stars and galaxies. Machine learning techniques can be applied to this data to improve our understanding of the physical properties and evolution of stars. Our project aims to create an interface that will allow us to explore stellar classification data using machine learning.
<br>

#### The SDSS dataset contains a variety of properties that can be used for machine learning-based stellar classification. Some of the key properties that are typically used in this context include:
<br>

#### Spectral features: The SDSS dataset includes spectra of millions of stars, which provide information on the wavelengths of light that the star emits. These spectra can be used to extract features such as the relative intensities of different spectral lines or the shapes of the spectral curves.
<br>

#### Temperatures: The temperature of a star can be estimated from its spectral features, such as the peak of its spectral curve. This information is important for classifying stars into different spectral types, such as O, B, A, F, G, K, and M.
<br>

#### Luminosities: The luminosity of a star, which is related to its brightness, can be estimated from its temperature and distance. Luminosity is an important parameter for studying the physical properties and evolution of stars.
<br>

#### Chemical compositions: The SDSS dataset includes information on the chemical composition of stars, including the abundance of different elements. This information can be used to classify stars into different populations, such as metal-rich or metal-poor stars.
<br>

#### Distances: The SDSS dataset provides information on the distances to millions of stars, which is important for estimating their luminosities and other physical properties.
<br>

#### Machine learning models can be trained using these properties to classify stars into different spectral types or other categories, such as giant or dwarf stars.
<br>

#### By combining different properties and using more complex models, it is also possible to identify rare or unusual types of stars, such as binary or variable stars.
<br>
<br>
<br>

## Objectives:
<br>
<br>


### To use machine learning to classify stars based on their spectral characteristics.
<br>

### To develop an interface that allows users to interact with the machine learning model and explore the data.
<br>

### To visualize the results of the classification and explore the properties of different types of stars.
<br>
<br>
<br>



## Examples for Interactivity: 
<br>
<br>


#### Classifying stars based on their temperature: build a machine learning model that uses data about a star's brightness and color to predict its temperature. This could help you better understand the different types of stars and how they evolve over time.
<br>

#### Identifying binary star systems: build a machine learning model that uses data about a star's motion and brightness to identify binary star systems, which are two stars orbiting around a common center of mass. This could help you better understand the dynamics of star systems and how they evolve over time.
<br>

#### Predicting the age of a star based on its color and size: build a machine learning model that uses data about a star's temperature, luminosity, and chemical composition to predict its age. This could help you better understand the evolution of stars and how they change over time.
<br>
<br>
<br>



## Methodology:
<br>
<br>


### Our project will involve the following steps:
<br>

#### Collect and preprocess the SDSS data, including spectra, temperatures, luminosities, and chemical compositions.
<br>

#### Extract relevant features from the data, such as the relative intensities of different spectral lines, or the presence or absence of certain chemical elements.
<br>

#### Train a machine learning algorithm to classify stars based on their spectral characteristics, using appropriate techniques such as cross-validation to ensure the model generalizes well to new data.
<br>

#### Develop an interface that allows users to input a star's properties and visualize the results of the classification, including the probability of belonging to different spectral classes.
<br>

#### Evaluate the accuracy of the machine learning model and refine it as necessary.
<br>
<br>
<br>

## Expected Results:
<br>
<br>


#### We expect to develop an interface that allows users to explore stellar classification data using machine learning techniques. The interface will be useful for astronomers and researchers who want to study the physical properties and evolution of stars, and will be an educational tool for students who want to learn more about astronomy and machine learning.
<br>
<br>
<br>


## Conclusion:
<br>
<br>


#### The SDSS dataset provides a rich source of data for studying the properties and evolution of stars. By applying machine learning techniques to this data, we can improve our understanding of the physical processes that govern stellar evolution. Our project aims to create an interface that allows users to explore this data using machine learning techniques, providing a powerful tool for researchers and students alike.

<br>
<br>
<br>

## ABOUT THE SLOAN DIGITAL SKY SURVEY (SDSS)

<br>
<br>

#### The data from the Sloan Digital Sky Survey (SDSS) is stored in a relational database that consists of multiple tables. Each table contains a different type of astronomical object, such as stars, galaxies, or quasars, and includes various properties that have been measured or calculated for each object.

<br>

#### The tables typically have millions or even billions of rows, depending on the type of object and the region of the sky that has been surveyed. The columns in each table correspond to different properties, such as the position on the sky (RA and Dec), the brightness in different colors (u,g,r,i,z), and the shape or size of the object.

<br>

### For example, the table of stellar objects in SDSS (called "photoObjAll") includes columns such as:

<br>

#### ra, dec: Right Ascension and Declination of the star in degrees

<br>

#### u, g, r, i, z: Apparent magnitudes of the star in different color bands

<br>

#### err_u, err_g, err_r, err_i, err_z: Uncertainties in the apparent magnitudes

<br>

#### extinction_u, extinction_g, extinction_r, extinction_i, extinction_z: Corrections for the absorption of light by interstellar dust

<br>

#### class: Classification of the object as a star, galaxy, or quasar

<br>

#### subClass: Further classification of the object as a type of star (e.g., main-sequence, giant, white dwarf, etc.)

<br>

#### metallicity: Estimate of the metallicity (abundance of elements heavier than helium) of the star, based on its spectrum

<br>

#### photoz: Estimate of the redshift (which is related to the distance) of the star, based on its spectrum and photometry

<br>

### These are just a few examples of the many properties that are available in the SDSS dataset. 

<br>

### The data is typically provided in a format that can be easily loaded into software packages for analysis, such as Python or R.

<br>
<br>
<br>



## ACCESSING THE DATA

<br>
<br>

#### The SDSS data is publicly available through the SDSS website (https://www.sdss.org/), where you can search for and download data products for different types of astronomical objects, including stars. The data is also available through the SDSS Data Archive Server (https://dr16.sdss.org/), which provides access to all of the data from the survey, as well as tools for querying and downloading specific subsets of the data.

<br>

#### To access the data, you will need to create an account and agree to the data usage policies of the SDSS collaboration. Once you have an account, you can use the search tools on the website or the Data Archive Server to find and download the data products that you need. The data is provided in a variety of formats, including FITS (Flexible Image Transport System) files for images and tables, as well as ASCII or binary files for some data products.

<br>

#### There are also tools and packages available in Python and other programming languages that can help you access and work with the SDSS data. For example, the Astroquery package provides a convenient interface for querying and downloading SDSS data from within Python, while the PyVO package allows you to query the SDSS Virtual Observatory using the Astronomical Data Query Language (ADQL).

<br>

### The Sloan Digital Sky Survey (SDSS) provides access to their data through their public data release website. Here are the links to access each of the datasets mentioned earlier:

<br>

#### Spectroscopic Data: The spectroscopic data can be accessed through the SDSS SkyServer. Specifically, you can find this data in the Spectroscopic Data section of the SkyServer. The data is available in FITS and CSV formats.

<br>

#### Photometric Data: The photometric data can also be accessed through the SDSS SkyServer. You can find this data in the Navigate Tool, where you can search for and select specific fields of interest. The data is available in FITS and CSV formats.

<br>

#### Astrometric Data: The astrometric data can be accessed through the SDSS Catalog Archive Server (CAS). You can use the SQL Search interface to query the data and retrieve the information you need. The data is available in FITS and CSV formats.

