# House Price Prediction
> Problem Statement
> > A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The company wants to know:

> > - Which variables are significant in predicting the price of a house, and
> > - How well those variables describe the price of a house.

> > It is required to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.



## Dataset Information
- The Dataset has 1460 rows, 81 columns
- The Data Description is provided in data_description.txt file


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- The Optimal Value of Alpha for Ridge regression is 3.51
- - With Training R2 = 0.8955817207861989 And Testing R2 = 0.8533533529371365
- The Optimal Value of Alpha for Lasso regression is 0.91
- - With Training R2 = 0.7744864089923619 And Testing R2 = 0.7620538116080745

- Followings are the Important Predictor variable along with their respective Coefficients
- - YearBuilt: 0.001989726925053266 
- - GarageArea: 0.0004429035741300149 
- - GrLivArea: 0.0002706436062495077 
- - TotalBsmtSF: 0.0001945505754640916 
- - WoodDeckSF: 0.00018002207249729084 
- - 2ndFlrSF: 4.6660699044849394e-05 
- - MasVnrArea: 4.6102728234679326e-05 
- - BsmtFinSF1: 3.707307759808199e-05 
- - LotArea: 8.788746769066721e-07


## Technologies Used
- numpy - version 1.23.5
- pandas - version 1.5.3
- matplotlib - version 3.7.1
- seaborn - version 0.12.2
- scipy - version 1.11.3


## Acknowledgements

- This project was conducted by Mr. B. M. Shivagunde


## Contact
Created by [@bshivagunde](https://github.com/bshivagunde) - feel free to contact me!
