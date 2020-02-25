# Question

An Inuit shaman was observing weather for his entire life. In the past, shaman could predict weather by observing wind strength, bird migrations and other factors. But now he is old and must predict weather based only on the probability distribution, that he learned during his lifetime of observations:

* P<sub>Raining</sub> = 0.7
* P<sub>Sunny</sub> = 0.3

Which of the following strategies would be best for the shaman to use, and why? Calculate risk of each strategy.

1. Always predict "Raining"
2. Predict "Raining" in 70% of cases, "Sunny" in other 30% of cases
3. Predict "Raining" in 50% of cases, "Sunny" in other 50% of cases
4. Always predict "Sunny"

# Answer

## Strategy 1 (correct answer)

R = 1 * 0.3 + 0 * 0.7 = 0.3

This is **deterministic optimal Bayesian strategy**.

## Strategy 2

R = 0.7 * 0.3 + 0.3 * 0.7 = 0.42

## Strategy 3

R = 0.5 * 0.3 + 0.5 * 0.7 = 0.5

Random guessing using coin toss.

## Strategy 4

R = 0 * 0.3 + 1 * 0.7 = 0.7

This is worst possible strategy.
