# Association Rule Mining Algorithm

For course assignment submission purposes

### generate_frequent_itemset
Input:
* list of transactions (which are lists of items)
* minimum support threshold (_minsup_)

Output:
* list of sets (represented as lists containing items) that appear frequently

```python
[['margarine'], ['ready soups'], ['citrus fruit','semi-finished bread'], ['tropical fruit','yogurt','coffee'], ['whole milk']]
```

### generate_association_rules
Input:
* list of transactions (which are lists of items)
* minimum support threshold (_minsup_)
* minimum confidence threshold (_minconf_)

Output:
* list of lists containing 2 itemsets with strong associations

```python
[['root vegetables', 'rolls/buns','=>', 'other vegetables'],['root vegetables', 'yogurt','=>','other vegetables']]
```