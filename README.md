# Grupo-Bimbo
Clustering Grupo Bimbo over 100  fresh bakery products for 1 million stores along its 45,000 routes across Mexico.
producto_tabla.csv — product names (can be joined with train/test on Producto_ID)

https://www.kaggle.com/c/grupo-bimbo-inventory-demand/data

In submission_means I try to predict demand of product with maximize sales and minimize returns of bakery goods,
or forecast the demand of a product for a given week, at a particular store.
Given dataset consists of 9 weeks of sales transactions. Every week, there are delivery trucks that deliver products to the vendors. Each transaction consists of sales and returns. Returns are the products that are unsold and expired. The demand for a product in a certain week is defined as the sales this week subtracted by the return next week.


The train and test dataset are split based on time, as well as the public and private leaderboard dataset split.
