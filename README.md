# Alphabet_Soup

## Objective
Analyse the Alphabet Soup charity loans and predict which charities would make better use of the money and have the projects completed.

## Analsysis
The dataset was cleard and non-essencial columns were removed.
Two models were chosen to this analysis, Random Florest and Deep Learning. The models achieved good performance with Random Florest at 68% and Deep Learning at 70%.

## Conclusion
Among several models tested the Ramdom Florest have the best performance with the lower processing time, however, it fell below the target of 75%.
The Deep Learning model was tested with several variations and all of then achieved the same accuracy of 0.706. Some of the variations are:
* 2 and 3 hidden layers
* Increased the number of neurons on each layer
* Activation modes tested: relu, elu, selu, sigmoid, hard_sigmoid and tanh

Based on the results presented above, there is little indication that a differente model would present a better result. There are two factors that could present better results: review the preprocessing and include/explude other data and from the dataset, collect more information on the charities.