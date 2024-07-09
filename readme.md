# Fuzzy Logic Implementation for Sentience Level Estimation

This repository contains Python code that implements a fuzzy logic system using scikit-fuzzy to estimate the sentience level based on three input variables: behavior complexity, human interaction effectiveness, and learning adaptation.

## Dependencies

Make sure you have scikit-fuzzy installed:

```bash
!pip install scikit-fuzzy
```
## Usage
Clone the repository:

```bash
git clone https://github.com/yourusername/your-repository.git
```
Run the fuzzy logic simulation:

Open the Python script sentience_level_fuzzy.py and execute it. Ensure you have Python and the necessary libraries installed.

Input Variables:

Behavior Complexity: Ranges from 0 to 10, defining the complexity of behavior.
Human Interaction Effectiveness: Ranges from 0 to 10, indicating how effective interactions with humans are.
Learning Adaptation: Ranges from 0 to 10, representing the adaptability and learning capability.
Output:

Sentience Level: Ranges from 0 to 100, indicating the estimated sentience level based on the fuzzy logic rules.

## Example
```bash
import numpy as np
import skfuzzy as fuzz
from skfuzzy import control as ctrl

# Define Antecedents and Consequent as in the code snippet

# Define fuzzy membership functions

# Define rules for fuzzy logic

# Create control system and simulation

# Set input values

# Compute and view the output

sentience_level.view(sim=sentience_simulation)
```
