LaSVM
=====

![LaSVM comparision graph](http://leon.bottou.org/_media/papers/lasvm-epsiloncache.png?w=300&tok=a93ee2)

LASVM is an approximate SVM solver that uses online approximation. It reaches accuracies similar to that of a real SVM after performing a single sequential pass through the training examples. Further benefits can be achieved using selective sampling techniques to choose which example should be considered next.

As show in the graph, LASVM requires considerably less memory than a regular SVM solver. This becomes a considerable speed advantage for large training sets. In fact LASVM has been used to train a 10 class SVM classifier with [8 million examples](http://leon.bottou.org/papers/loosli-canu-bottou-2006) on a single processor.

See the [LaSVM paper](http://leon.bottou.org/papers/bordes-ertekin-weston-bottou-2005) for the details.

## Source

http://leon.bottou.org/projects/lasvm
