The JupyterNotebook “FitDataToPolynomial.ipynb” will fit a polynomial of degree set by NDeg to a tab-delimited text file of data.

The first row of the text file consists of names of the columns.

Files consisting of 2, 3 or 4 columns of data are compatible with the routine.  For two column format, they should be abscissa and ordinate.  For 3 columns: abscissa, ordinate and standard deviation of the ordinate. For 4 columns: abscissa, standard deviation of the abscissa, ordinate and standard deviation of the ordinate.

If uncertainties are provided for the data, then uncertainties are provided for the coefficients of the polynomial.

For 4 columns of data, the Orthogonal Distance Regression algorithm is used. This algorithm minimizes the distance between the data point and the curve along a segment normal to the curve.

Michael Fitzsimmons

19Dec23



