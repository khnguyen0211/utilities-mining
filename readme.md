
# ***<p style="text-align:center;">ABSTRACT</p>***

Mining high-utility patterns in databases containing items with both positive and negative profits is useful in market basket databases, since negative profits are common in the real world. Obviously, in the market basket database, patterns with stable long-term profits have more meaning. The discovery of item sets with a consistent high frequency is known as periodic frequent pattern mining. Therefore, mining periodic high utility patterns in a database containing items with both positive and negative profits is an interesting and useful task. 

However, this task has two main challenges. First, the utility measure does not have the download closure property. Second, the huge search space needs to be pruned more effectively. In this paper, we propose a vertical data structure-based algorithm called PHMN to discover periodic high-utility patterns (PHUPs) or itemsets in a transaction database with both positive and negative utilities. To be more efficient, we propose a new upper bound to prune the search space and an improved algorithm to discover the PHUPs. 

Finally, experiments are conducted to verify the effectiveness and efficiency of algorithms 