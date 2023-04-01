A/B Testing: Website Redesign
=============================

This project provides an analysis of an A/B test performed on a website redesign for a Datacamp Competition. It uses a dataset provided by DataCamp, data contains information about user conversion statistics before/after an new launch page implementation and a new image set. 

Installation
------------

To install the required libraries, you can use pip:

Copy code

`pip install numpy pandas scipy statsmodels matplotlib seaborn`

You will also need to download the data files from the `data` folder in this repository.

Usage
-----

The main entry point for the project is the `ab_testing_website_redesign.py` script. You can run it from the command line:

Copy code

`python ab_testing_website_redesign.py`

This will load the data, perform statistical analysis, and generate visualizations of the results. You can customize the behavior of the script by modifying the parameters in the `config.json` file.

Features
--------

The project includes several features to analyze the results of the A/B test:

*   **Statistical analysis**: The script performs several statistical tests to compare the performance of the old and new versions of the website. These tests include the t-test, the Mann-Whitney U test, and the chi-squared test.
    
*   **Effect size calculation**: The script also calculates effect sizes for the statistical tests. This can be used to quantify the magnitude of the differences between the old and new versions of the website.
    
*   **Visualization**: The script generates several visualizations of the results, including histograms, box plots, and bar charts. These visualizations can be used to identify patterns and relationships in the data.
    

License
-------

This project is licensed under the MIT License. See the LICENSE file for more details.

Contributing
------------

Contributions are welcome! If you want to contribute to this project, please fork the repository and submit a pull request with your changes.
