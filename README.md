# assignment_1_Machine-learning
polynomial-regression
## Results (test set)

| Optimizer | RMSE | R2 |
|---|---|---|
| GD | 3.86 | 0.843 |
| SGD | 3.78 | 0.849 |
| Mini-Batch GD | 3.80 | 0.848 |
| RMSprop | 4.17 | 0.816 |
| Adam | 5.40 | 0.692 |

SGD and Mini-Batch got the best results here, and GD was very close. RMSprop and Adam needed more tuning (a smaller learning rate and more epochs) to reach the same level.
