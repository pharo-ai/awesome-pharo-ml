# Awesome Machine Learning in Pharo

This is the list of machine learning projects written in or related to Pharo as well as books, booklets, papers, or tutorials on this topic. If you want to add an entry to this list - feel free to make a pull request or create an issue with a link to the project and we will add it ourselves. Entries are grouped into categories and sorted by aphabet.

## Contents

* [Mathematics](#mathematics)
* [Linear Models](#linear-models)
* [Neural Networks](#neural-networks)
* [Deep Learning](#deep-learning)
* [Neuroevolution](#neuroevolution)
* [Generative Models](#generative-models)
* [Natural Language Processing](#natural-language-processing)
* [Data Mining](#data-mining)
* [Data Structures](#data-structures)
* [Data Visualization](#data-visualization)
* [Interactive Notebooks](#interactive-notebooks)
* [Data Collection](#data-collection)
* [Applications](#applications)
* [Books & Booklets](#books--booklets)
* [Papers](#papers)

## Mathematics

* **[Domains](https://github.com/PolyMathOrg/Domains)** - Ongoing port of a computational algebra system in Smalltalk.
* **[Mathematics](https://github.com/grpistoia/Mathemagics)** - Symbolic algebra package.
* **[PolyMath](https://github.com/PolyMathOrg/PolyMath)** - Smalltalk library for numeric computations similar to NumPy, SciPy or SciRuby. Includes data structures and algorithms for linear algebra (PMVector, PMMatrix), statistics, differential equations, numeric integration, optimization, data mining, linear regression, genetic algorithms

## Linear Models

* **[MLLinearModels](https://github.com/AndriySkol/MLLinearModels)** - provides functionality to train and use linear regression models, such as Ordinary Least Squares, Ridge, Lasso, Elastic Net
* **[PMLinearRegression in PolyMath](https://github.com/PolyMathOrg/PolyMath)** - implementation of linear regression in PolyMath library

## Neural Networks

* **[AgileArtificialIntelligence](http://smalltalkhub.com/#!/~abergel/AgileArtificialIntelligence)** - object-oriented implementation of neural networks, equipped with toy examples (logical gates, games)
* **[MLNeuralNetworks](https://github.com/olekscode/MLNeuralNetwork)** - multilayer neural networks. Classification of MNIST handwritten digits
* **[NeuralNetwork](https://github.com/vanor/NeuralNetwork)** - multilayer neural network with separate classes for Layers and Neurons
* **[NeuralNetworks](http://smalltalkhub.com/#!/~abergel/NeuralNetworks)** - simple neurons, perceptrons, logical gates

## Deep Learning

* **[Keras bindings](https://github.com/ObjectProfile/KerasWrapper)** - allows to use [Keras](https://keras.io/) functions within Pharo
* **[TensorFlow bindings](https://github.com/PolyMathOrg/libtensorflow-pharo-bindings)** - allows to use [TensorFlow](https://www.tensorflow.org/) in Pharo

## Neuroevolution

* **[NEAT (NeuroEvolution of Augmenting Topologies)](https://github.com/bergel/NEAT)** - a genetic algorithm for evolving artificial neural networks. NEAT is probably the most popular algorithm for neuroevolution.

## Learning Classifier System

* **[LCSTalk](http://www.squeaksource.com/LCSTalk.html)** is a small machine learning framework based on Learning Classifier Systems. 

## Generative Models

* **[NaiveBayesClassifier](https://github.com/olekscode/NaiveBayesClassifier)** - a multinomial Naive Bayes classifier that can be used for spam detection

## Natural Language Processing

* **[Ngram](https://github.com/olekscode/Ngram)** - Ngram class and String extensions that provide n-gram functionality for Pharo (splitting text into unigrams, bigrams, trigrams, etc)
* **[NgramModel](https://github.com/olekscode/NgramModel)** - framework for training n-gram language models
* **[nlp_smalltalk](https://github.com/mark-watson/nlp_smalltalk)** - natural language processing library. Implements part of speech tagging, categorization, named entity recognition, sentence segmentation, and summarization
* **[Pharo-NLtoolkit](https://github.com/nikhilpinnaparaju/Pharo-NLtoolkit)** - n-gams and TF-IDF implementations by Nikhil Pinnaparaju
* **[Polyglot](https://github.com/PolyMathOrg/Polyglot)** - a natural language processing library implemented in Pharo by Nikhil Pinnaparaju during Google Summer of Code.

## Data Mining

* **[APriori](https://github.com/olekscode/APriori)** - implementation of [A-Priori algirithm](https://en.wikipedia.org/wiki/Apriori_algorithm) for finding frequent itemsets and [learning the association rules](https://en.wikipedia.org/wiki/Association_rule_learning).

## Data Structures

* **[DataFrame](https://github.com/PolyMathOrg/DataFrame)** - tabular data structures for data analysis and machine learning

## Data Visualization

* **[MatplotLibBridge](https://github.com/juliendelplanque/MatplotLibBridge)** - a bridge to provide the ability to Pharo user to use Python's [Matplotlib](https://matplotlib.org/)
* **[Roassal](https://github.com/ObjectProfile/Roassal2)** - visualization engine for the Pharo and VisualWorks. Provides powerful tools for charting, plotting, and other data visualization

## Interactive Notebooks

* **[JupyterTalk](https://github.com/jmari/JupyterTalk)** - basic Pharo Smalltalk kernel for [Jupyter](http://jupyter.org/)
* **[Grafoscopio](https://mutabit.com/grafoscopio/index.en.html)** - Pharo based interactive outliner for reproducible research & publishing and agile visualization and data storytelling.
* The Pharo edition of **[ActivePapers](https://github.com/activepapers/activepapers-pharo)** focuses on the documentation and user interface aspects of communicating computational science.
* **[Leibniz-pharo](https://github.com/khinsen/leibniz-pharo)** is the Pharo version of the digital scientific notation **[Leibniz](https://github.com/khinsen/leibniz)**.

## Data Collection

* **[CSV](https://github.com/svenvc/NeoCSV)** - NeoCSV is an elegant and efficient standalone Smalltalk framework to read and write CSV converting to or from Smalltalk objects.
* **[NeoJSON](https://github.com/svenvc/NeoJSON)** - Framework to handle JSON in Pharo.
* **[Soup](https://github.com/Ducasse/Soup)** - A library for web scrapping based on HTML and XML parsers
* **[Soup-for-Pharo](https://github.com/seandenigris/Soup-for-Pharo)** - a binding for Python's [Beautiful Soup](https://www.crummy.com/software/BeautifulSoup/) - tool for web scrapping based on HTML and XML parsers
* **[Territorial](https://github.com/hernanmd/Territorial)** - Smalltalk package for Geographical Information Retrieval (GIR)

## Applications

* **[ELIZA-Pharo](https://github.com/brackendev/ELIZA-Pharo)** - Pharo Smalltalk implementation of [ELIZA](https://en.wikipedia.org/wiki/ELIZA), an early natural language processing computer program created from 1964 to 1966 at the [MIT Artificial Intelligence Laboratory](https://www.csail.mit.edu/) by [Joseph Weizenbaum](https://en.wikipedia.org/wiki/Joseph_Weizenbaum).
* **[Generating method names](https://github.com/ObjectProfile/GeneratingMethodNames)** - using sequence to sequence recurrent neural networks for neural machine translation of Pharo source code into English. Translating method code into a very short description (1-5 words) which is a method name

## Books & Booklets

* **[Agile Artificial Intelligence](https://agileartificialintelligence.github.io/)** - a book that covers classical algorithms commonly assimilated as artificial intelligence techniques
* **[Agile Visualization](http://agilevisualization.com/)** - a book that covers agile visualization with [Roassal](https://github.com/ObjectProfile/Roassal2)
* **[DataFrame Booklet](https://github.com/SquareBracketAssociates/Booklet-DataFrame)** - a small booklet about Pharo DataFrame provided by [SquareBracketAssociates](https://github.com/SquareBracketAssociates)
* **[Grafoscopio User Manual](https://zenodo.org/record/1974261)**.
* **[Numerical Methods with Pharo](https://books.pharo.org/numerical-methods/)** - a book that documents the [PolyMath](https://github.com/PolyMathOrg/PolyMath) project and covers many topics related to data science: function interpolation, iteration, zeroes, linear algebra series, statistics, estimation, minimisation, and data mining
* **[Object-oriented Implementation of Artificial Neural Networks in Pharo](https://github.com/olekscode/MLNeuralNetwork-Doc)** - describes and documents the [MLNeuralNetworks](https://github.com/olekscode/MLNeuralNetwork) library

## Papers

* **[Towards Exploratory Data Analysis for Pharo](https://dl.acm.org/citation.cfm?id=3139918)** - a paper about DataFrame.
* **[Grafoscopio: A moldable tool for literate computing and reproducible research](http://joss.theoj.org/papers/c92ed13fa746bc681081f9b31678841b)**.
* **[Building a scientific workbench in Pharo](https://hal.archives-ouvertes.fr/hal-02533110/)**
