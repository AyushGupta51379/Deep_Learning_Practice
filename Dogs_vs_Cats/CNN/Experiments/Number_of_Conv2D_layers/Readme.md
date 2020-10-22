# Number of layers

Layers of Conv2D:   1       2         3         4         5

Precision %:       76.5     81.7     88.2     90.3       89.0

Cohen kappa:       0.529    0.635    0.765    0.806      0.781

Cats f1-score:     0.77     0.82     0.88     0.90       0.90

Dogs f1-score:     0.76     0.81     0.89     0.91       0.88

# Conclusion

It seems that 4 Conv2D layers work best for this task. The cohen kappa score is also highest for this case.

Cohen kappa score: Basically, it is a more robust measure than simple % accuracy, recall, as it compares the results with that of a random model. Thus, it compares how good our model is performing against a model that is performing just by chance.

Read more here: https://towardsdatascience.com/cohens-kappa-9786ceceab58

