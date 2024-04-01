# Apriori_-algorithm
The Apriori algorithm is a classical algorithm in data mining used for discovering frequent itemsets within a dataset and generating association rules between those items. It's particularly useful in market basket analysis, where the goal is to identify relationships between items frequently purchased together.

# How it's works?
In a small business scenario, selecting interesting rules from the multitude of possibilities can be crucial for decision-making. Several measures are commonly used to assess the interestingness of association rules:

1) Support: This measure indicates the frequency of occurrence of an itemset in the dataset. It is calculated as the proportion of transactions in the dataset that contain the itemset. Rules with higher support values are generally more significant.

2) Confidence: Confidence measures the reliability of the association rule. It is calculated as the ratio of the support of the itemset containing both the antecedent and consequent of the rule to the support of the antecedent alone. Higher confidence values indicate stronger associations between items.

3) Lift: Lift measures how much more often the antecedent and consequent of a rule occur together than we would expect if they were statistically independent. It is calculated as the ratio of the confidence of the rule to the support of the consequent. Lift values greater than 1 indicate that the antecedent and consequent are positively correlated.

4) Leverage: Leverage measures the difference between the observed frequency of occurrence of the antecedent and consequent together and what would be expected if they were independent. It is calculated as the support of the itemset containing both the antecedent and consequent minus the product of their individual supports.

5) Conviction: Conviction measures the degree of implication of the consequent by the antecedent. It is calculated as the ratio of the probability that the antecedent occurs without the consequent to the probability that the antecedent occurs with the consequent. Conviction values greater than 1 indicate stronger implication.

6) Interest Factor: Interest Factor combines lift and confidence to provide a measure of the interestingness of an association rule. It is calculated as (lift - 1) * confidence. Positive values indicate interesting rules, while negative values indicate uninteresting rules.

# Association rule 
An association rule is a relationship or pattern discovered within a dataset that describes the co-occurrence or correlation between items. It typically takes the form of "if X then Y," indicating that the presence (or absence) of certain items in a transaction implies the presence (or absence) of other items.
