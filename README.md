# Association Rule Mining/ Market Basket Analysis:

Implementation of association rule mining/market basket analysis using Brute Force approach & Apriori Algorithm in Python for discovering interesting relations between variables in large databases.

#### Data:
Created 5 transaction databases using a product list of a sample shopping cart item of Costco.

#### Item List:
My_itemList = ['flatscreen TVs', 'television sets', 'MP3 players', 'video recorders', 
            'DVD players','laptops', 'printers', 'paper shredders','cell phones',
            'sugar','flour', 'spices', 'milk', 'bread', 'coffee', 'tea', 'wine', 
            'cooking oils','donuts','Dyes','Removals', 'Perfumes', 'Novelty Makeup',
            'Wall prints','clocks','Table lamps','Cushions','Candles','Rugs','Vases']

#### Databases:

• I've generated five distinct transaction databases, each with 20 unique transactions. 
• Text files are used to preserve these databases. 
• Each transaction is recorded on a single line in a database file, with elements separated by a comma. 
• To produce the transactions, I wrote a function that chooses a specified number of random objects from my item list at random. 
• I manually modified several of the transactions in the databases to increase the performance.

#### Implementation of Apriori Algorithm for association rule mining:

•	The Apriori method is a classic data mining approach for mining frequent itemsets and appropriate association rules. 
•	It is based on the idea that any non-empty subset of a frequent itemset must be frequent, and that if an itemset is infrequent, all its supersets will be infrequent. 
•	There are two key aspects to remember while using association rule mining: 

(1) Support: evaluates how popular an itemset is based on how many transactions it occurs in. 

(2) Confidence: represented as X -> Y and indicates the likelihood of item Y being purchased when item X is purchased.
