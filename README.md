# market-basket-analysis
Implementing ML algorithms in Retail data

Market basket analysis is a data mining technique, which aids in finding items that buyers desire to buy.

This involves:

- Support:

  ![image](https://github.com/Chukwuebuka-2003/market-basket-analysis/assets/56232734/de274f6e-f41c-4e16-ba8d-3d9ca6f63c63)

  This metric gives an idea of how frequent an item is in the transactions of the given data.
  It helps to identify rules that are important for further analysis.

  A high support metric means that if most customers buy an item, then this item is important for our shop/business.
  
- Confidence:

  ![image](https://github.com/Chukwuebuka-2003/market-basket-analysis/assets/56232734/a452c2a3-774c-4aac-81b2-f2cebbf0cfdb)

  This defines the probability of an occurence of the followung items in the same transaction given that some items (antecedents) already exist in the given transaction.

- Lift:
  
  ![image](https://github.com/Chukwuebuka-2003/market-basket-analysis/assets/56232734/aaab9ce7-9b06-4c45-8808-c8b7d9d8330f)

  This is the ratio that probability of B ocurring given A is present and the probability that B occurs without knowing about A.

- Leverage:

   ![image](https://github.com/Chukwuebuka-2003/market-basket-analysis/assets/56232734/9ac6efd0-e0c7-4f5c-8a0b-029cc0252730)

  Any leverage value of 0 indicates independence.

- Conviction:

  ![image](https://github.com/Chukwuebuka-2003/market-basket-analysis/assets/56232734/bfb217da-e3a4-45dc-862b-9fa562304e3b)

  This is used to judge if the rule used in the market basket analysis happened to be there by chance or not.

  The notebook of this project can be found here: https://nbviewer.org/github/Chukwuebuka-2003/market-basket-analysis/blob/main/model.ipynb

  The Medium article that was written based on this project can be found here: https://medium.com/@ebulamicheal/implementing-ml-in-a-retail-success-johns-data-driven-store-transformation-669080fea242


