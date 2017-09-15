# Big Data Analytics Using Apache Spark

Major goals of this project are to:

1. Understand the components of the Apache Spark framework and programming: spark context (sc), dataflow operations in transformations and actions
2. Study the scalability provided by Spark. Analyze the performance improvement achieved by Apache Spark vs. traditional Hadoop MR by repeating the analysis with Project Tesserae data.
3. Format the output according to the format shown in the Project Tesserae page.

### Featured activity: Analysis of Latin documents for word-co-occurrence

Program a word-co-occurrence program in Spark and test it for n=2 (n-grams) and just 1 or 2 documents. Scale it up for as many documents as possible. This problem was provided by researchers in the Classics department at UB. They have provided two classical texts and a lemmatization file to convert words from one form to a standard or normal form. In this case you will use several passes through the documents.

* Pass 1: Lemmetization using the lemmas.csv file
* Pass 2: Identify the words in the texts by <word <docid, [chapter#, line#]> for two documents.
* Pass 3: Repeat this for multiple documents.
