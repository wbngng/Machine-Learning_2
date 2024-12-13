# Machine-Learning_2

This repository contains a neural network model designed to predict task difficulty based on user interaction data. The model uses features such as correctness, attempts, hint usage, and overlap time to generate a difficulty score.

## Features
Inputs:
* correct: Binary indicator of task completion correctness.
* attempt_count: Number of attempts made.
* hint_count: Number of hints used.
* overlap_time: Time spent on the task.

Output:
* Predicted difficulty score, scaled between 1 and 10.
