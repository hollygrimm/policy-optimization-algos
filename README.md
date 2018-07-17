



# Simple Policy Gradient Algorithm


## Continuous Actions on Point-v0

```python simplepg/main.py Point-v0 --render True --use-baseline False```

-25 Return after 100 Iterations without Time-Dependent Baseline

```python simplepg/main.py Point-v0 --render True```

-20 Return after 100 Iterations *with* Time-Dependent Baseline


## Discrete Actions on CartPole-v0

```python simplepg/main.py CartPole-v0 --render True```

198 Average Return after 100 Iterations (default batch size 2000, discount 0.99, learning_rate 0.1)

```python simplepg/main.py CartPole-v0 --batch_size 1000 --discount 0.95 --learning_rate 0.01```

37.96 Average Return after 100 Iterations

TODO: Add Tensorboard Charting to compare hyperparameters
