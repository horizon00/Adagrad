# adagrad Optimizer

Adagrad is an algorithm for gradient-based optimization that does just this: It adapts the learning
rate to the parameters, performing larger updates for infrequent and smaller updates for frequent
parameters. For this reason, it is well-suited for dealing with sparse data. Dean et al. have found
that Adagrad greatly improved the robustness of SGD and used it for training large-scale neural nets
at Google, which – among other things – learned to recognize cats in Youtube videos Moreover,
Pennington et al. used Adagrad to train GloVe word embeddings, as infrequent words require
much larger updates than frequent ones.
