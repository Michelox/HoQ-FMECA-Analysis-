# Robotic Vacuum Cleaner - Q-Bench and ELECTRE II Optimization

This project contains a reconstructed Google Colab notebook implementing a decision-support procedure for the technical optimization of a robotic vacuum cleaner. The notebook applies a simplified ELECTRE II outranking method combined with a Q-Bench-style iterative search algorithm to identify the best technical configuration among predefined design alternatives.

The work is part of a Quality Engineering analysis focused on the conceptual design of a smart robotic vacuum cleaner. The main goal is to support product design decisions by comparing technical characteristics, evaluating trade-offs, and selecting an optimized solution based on weighted criteria.

## Project Overview

The notebook evaluates different technical characteristics of a robotic vacuum cleaner, such as suction-related performance, navigation capability, battery capacity, recharge time, noise level, component lifetime, and user setting flexibility.

The optimization process uses multi-criteria decision-making logic to determine whether one technical configuration outranks another. The final output is the best solution found within the available design domains, together with visual plots showing the performance profile of the selected configuration.

## Main Methodologies

The project combines two main methods:

### ELECTRE II Outranking

ELECTRE II is used to compare two solutions based on concordance and discordance logic. A solution is considered better if it satisfies a sufficient level of agreement across weighted criteria while avoiding excessive disadvantage in any individual criterion.

The implementation includes:

- Criterion normalization
- Weight normalization
- Concordance matrix calculation
- Discordance matrix calculation
- Strong and weak outranking logic
- Alternative ranking based on dominance relationships

### Q-Bench Iterative Search

The Q-Bench-style procedure starts from an initial admissible solution and progressively improves it by testing small variations in the technical criteria. Each candidate solution is accepted only if it outranks the current best solution according to the ELECTRE II rules.

This allows the notebook to identify a locally optimized technical profile within the predefined design ranges.

## Technical Criteria

The robotic vacuum cleaner is evaluated using the following technical characteristics:

- Motor Power
- Airflow Rate
- SLAM Localization Accuracy
- SLAM Update Range
- Path Optimization Metric
- Auto Recharge Time
- Battery Capacity
- Acoustic Noise Level
- Component Lifetime
- Setting Steps

Some criteria are maximized, such as airflow rate, battery capacity, and component lifetime. Other criteria are minimized, such as recharge time, acoustic noise level, and setting complexity.

## Libraries Used

The notebook uses the following Python libraries:

- NumPy
- Pandas
- Matplotlib
- Seaborn

These libraries are used for numerical computation, data handling, and visualization of the optimization results.

## Notebook Outputs

The notebook produces:

- Normalized performance profiles
- Concordance and discordance matrices
- Strong and weak outranking matrices
- Ranking levels of alternatives
- Iterative improvement logs
- Final optimized solution
- Graphical profile of the best solution

## Final Result

The Q-Bench and ELECTRE II optimization procedure identifies the following best solution:

```text
[2000, 36, 3, 3, 88, 90, 5800, 67, 4, 3]
