# Interactive Pricing App Based on Bokeh

This app has a dual objetive: on the one hand, it allows the user to price european options using both the Black-Scholes formula and the Euler implicit scheme and on the other hand it allows the user to price a more complexe structure, an accumulator, using Monte Carlo. Hence this project contains a plurality of methods used in modern finance for pricing: stochastic calculus, PDE, Monte Carlo. It has been written using various Python libraries such as Dask, Numpy and Bokeh among others.
It also contains some tests made using the library iPytest.

# Installation

The user has to run the following in his shell: 

pip install nodejs

pip install ipytest


## Usage

The user can directly manipulate the GUI which is in the file name BIDAL_AFLALO_GUI. The user can price put or call option and compare the results given by Black-Scholes with those obtained by the Euler implicit scheme which is an approximation of Black-Scholes. Finally, the user can price an accumulator monitored continuously or discretely, using a constant volatility model (Black-Scholes) or a stochastic volatility model (Heston). If he choose to use Heston then the correponding volatility surface will appear on a new page.

The file BIDAL_AFLALO_DETAILED_CODE contains all the code, it is useful to understand how the project was built. 

## License
[MIT](https://choosealicense.com/licenses/mit/)
