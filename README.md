# useR! 2016
In this repository, we show the examples of usage of the package Shiny for text retrieval, classification and quantification, discussed in the abstract submitted to useR! 2016.

## Text Retrieval
The [interactive text retrieval](https://gmdn.shinyapps.io/shinyRF04/) demo allows students (and researchers) to get deeper insight into the consequences of probabilistic modeling assumptions (Binary Independence Model vs BM25) and the consequences of tuning parameter values by means of a two-dimensional representation of probabilities.

A reference for this work can be found [here](http://dx.doi.org/10.1145/2766462.2767867).

## Text Classification
The [interactive text classification](https://gmdn.shinyapps.io/shinyK/) demo allows us to study the problem of Naïve Bayes text classification on a two dimensional space and use this graphical interpretation to analyse different approaches to find the best decision on for different distribution assumptions (Bernoulli, Multinomial, and Poisson).

A reference for this work can be found [here](http://dx.doi.org/10.1016/j.ipm.2014.04.008).

## Text Quantification
The goal of text quantificatgion is the evaluation of the results of classication at the aggregate level (proportion of objects of a class over to the total number of objects to classify) rather than at the individual level (the class of each object, as in text classification).
In this [interactive demo](https://gmdn.shinyapps.io/TextQuantification/), we present the problem of the optimization
of a text quantifier by extending the framework we used for text classification by adding new evaluation measures and interactive plots that guide users quickly to the (sub)-optimal solution.

The source code of this demo can be found [here](https://github.com/gmdn/TextQuantification).
