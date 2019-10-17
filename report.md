# Project report

## Learning algorithm

The learning algorithm used is vanilla Deep Q Learning as described in the original paper. A vector of state is used as an input instead of an image so convolutional neural network is replaced with deep neural network. The deep neural network has following layers:

- Fully connected layer - input: 37 (state size) output: 64
- Fully connected layer - input: 64 output 64
- Fully connected layer - input: 64 output: (action size)

Parameters used in DQN algorithm:

- Maximum steps per episode: 1000
- Starting epsilion: 1.0
- Ending epsilion: 0.01
- Epsilion decay rate: 0.999

## Results

```
Episode 100	Average Score: 1.26
Episode 200	Average Score: 4.94
Episode 300	Average Score: 8.07
Episode 400	Average Score: 10.31
Episode 500	Average Score: 12.91
Episode 600	Average Score: 13.30
Episode 700	Average Score: 14.27
Episode 800	Average Score: 15.06
Episode 900	Average Score: 15.04
Episode 1000	Average Score: 16.51
Episode 1100	Average Score: 16.06
Episode 1200	Average Score: 16.25
Episode 1300	Average Score: 16.43
Episode 1400	Average Score: 15.76
Episode 1500	Average Score: 15.77
Episode 1600	Average Score: 15.52
Episode 1700	Average Score: 15.93
Episode 1800	Average Score: 15.50
Episode 1900	Average Score: 15.50
Episode 2000	Average Score: 16.29
```
```
Environment solved in 403 episodes!	Average Score: 13.00
```
## Ideas for future work

1. Extensive hyperparameter optimization
2. Double Deep Q Networks
3. Prioritized Experience Replay
4. Dueling Deep Q Networks
5. RAINBOW Paper
