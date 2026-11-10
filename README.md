# market-basket-analysis
Implementing ML algorithms in Retail data

Market basket analysis is a data mining technique, which aids in finding items that buyers desire to buy.

This involves:

- Support:

  ![image](<img width="478" height="138" alt="image" src="https://github.com/user-attachments/assets/2bc31a29-c1bc-4c1b-a282-7d47791b91d3" />
)

  This metric gives an idea of how frequent an item is in the transactions of the given data.
  It helps to identify rules that are important for further analysis.

  A high support metric means that if most customers buy an item, then this item is important for our shop/business.
  
- Confidence:

  ![image](<img width="478" height="138" alt="image" src="https://github.com/user-attachments/assets/9c4c6faf-4b53-4ec6-9fc8-1166e4d44c57" />
)

  This defines the probability of an occurence of the followung items in the same transaction given that some items (antecedents) already exist in the given transaction.

- Lift:
  
  ![image](<img width="693" height="125" alt="image" src="https://github.com/user-attachments/assets/ab41ca8f-4216-4c43-90eb-1c4d08773433" />
)

  This is the ratio that probability of B ocurring given A is present and the probability that B occurs without knowing about A.

- Leverage:

   ![image](<img width="686" height="96" alt="image" src="https://github.com/user-attachments/assets/adb890a8-4424-4495-a01a-b4660c8fb977" />
)

  Any leverage value of 0 indicates independence.

- Conviction:

  ![image](<img width="686" height="96" alt="image" src="https://github.com/user-attachments/assets/7da2f03f-e123-4723-a4be-0cdd90e29c7f" />
)

  This is used to judge if the rule used in the market basket analysis happened to be there by chance or not.

  The notebook of this project can be found here: (https://nbviewer.org/github/PressyEms/market-basket-analysis/blob/main/model.ipynb)

  The Medium article for this project can be found here: (https://medium.com/@pressydeux018/implementing-ml-in-a-retail-success-johns-data-driven-store-transformation-f3a43001f44c)


