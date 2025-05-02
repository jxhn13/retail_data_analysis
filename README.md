📌 Business Problem
Retail businesses often face challenges in understanding customer buying behavior, peak sales periods, and the impact of promotional strategies. To improve revenue, efficiency, and customer retention, businesses must analyze when and how purchases happen, what products are in demand, and which marketing techniques work best.

ASSUMPTIONS
1.	No extreme market events (like lockdowns or economic crashes) occurred during the transaction period.

2.	Customer names are anonymized and reused, not personally identifying.

3.	All transactions are recorded accurately and reflect real purchases.

4.	Product names and categories are standardized.

5.	Promotions were applied correctly and logged without error.

6.	Payment method and customer category are self-reported or inferred correctly.

7.	Customers in the dataset represent typical behavior of the broader customer base

🎯 Research Questions
1.	Which days, months, and seasons see the highest number of transactions and revenue?

2.	Which products and promotions lead to the most revenue?

3.	What is the impact of promotions on customer purchases?

4.	How do customer types, store locations, and payment methods affect spending?


import libraries
In [1]:
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import warnings
warnings.filterwarnings('ignore')

