# Frequent Itemset Mining

Classical apriori, fp-growth, and improved apriori are compared.

My improved apriori seeks to address classical apriori's redundant candidate generation, which is computationally expensive. With my improvement, transactions are parsed only once at the start into an array at the start as opposed to before every iteration in classical apriori. Since information about every transaction in an array, we can mark which transaction lines lack infrequent itemsets and therefore will undergo candidate generation and which transaction lines contain infrequent itemsets will skip candidate generation.

## To Run

In Main.java: change the dataset attributes on line 19 as needed

Open command prompt

Change directory to project folder

To compile, type: javac \*.java

To run, type: java Main

## Restrictions

Data file must NOT include an attribute row.

# Improvements

Allow user to change dataset attributes via command line inputs

