# ETF_Analyzer

This ETF Analyzer uses Python, SQL, and Voilà to build a financial database and web appplication, and then analyzes the performance of a hypothetical fintech ETF.

---

## Technologies

This project uses Jupyter Notebook (within JupyterLab) and the standard Python 3.8 libraries. This project requires the following libraries and/or dependencies:

- [Pandas](https://pandas.pydata.org/) - a software library designed for open source data analysis and manipulation
- [hvplot](https://hvplot.holoviz.org/) - provides a high-level plotting API built on HoloViews that provides a general and consistent API for plotting data in all the abovementioned formats
- [NumPy](https://numpy.org/) - offers comprehensive mathematical functions, random number generators, linear algebra routines, Fourier transforms, and more
- [sqlalchemy](https://www.sqlalchemy.org/) - is the Python SQL toolkit and Object Relational Mapper that gives application developers the full power and flexibility of SQL

---

## Installation

The following dependencies must be installed before running the application:
```
Install Anaconda Package
Pip install Jupyter
conda install -c pyviz hvplot 
pip install SQLAlchemy
conda install -c conda-forge voila
```
---

## Methods

1. Use database queries using SQL to analyyze a single asset in the hypothetical ETF.
2. Analyze the entire ETF portfolio.
3. Use Voilà to deploy the web application.

---

## Analysis via Web Application

The following photos of the charts are shown on the web application via Voilà

![](https://github.com/ThomasBrierton/ETF_Analyzer/blob/main/Photos/Screen%20Shot%202022-02-20%20at%202.00.51%20PM.png)

![](https://github.com/ThomasBrierton/ETF_Analyzer/blob/main/Photos/Screen%20Shot%202022-02-20%20at%202.00.59%20PM.png)

![](https://github.com/ThomasBrierton/ETF_Analyzer/blob/main/Photos/Screen%20Shot%202022-02-20%20at%202.01.18%20PM.png)

The final cumulative return was analyzed, and was found to be 341.83% over the period analyzed.

---

## Contributors 

Thomas Brierton and UCB

---

## License

MIT