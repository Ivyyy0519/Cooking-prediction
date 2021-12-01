### README For COMP30027 Assignment 2

1. First, import the library
2. Second, run cells in `Load Data` to load data
3. `Visualization` section is to explore numeric data properties, and produce the graphs used in the report.
4. Then executing all the cells in the `preprocessing` section to produce the preprocessed data set for training. After this, three types of preprocessed data set will be produced:
    1. new countvectorizer with more preprocessing,
    2. countvectorizer after TF-IDF transformation with more preprocessing
    3. countvectorizer after TF-IDF with more preprocessing.
5. Run all the code cells in `Manual Cross Validation` section. This section is for cross validation in later stages. As the countvectoriser for validation set should be transformed by the countvectoriser fitted by the training set, the built in cross validation function does not work. Therefore, the five countvectorisers were created manually for 5-fold cross validation and the corresponding validation set will be transformed by the countvectorisers that are fitted by the training set.
6. Run all the cells in `Feature Selection` section
7. Then the corresponding model could be trained in the section with corresponding title, and the figures and evaluation results used in the report will be produced accordingly. **Please note the SVM and stack model will take significant running time.**
