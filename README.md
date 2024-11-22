# C.Leonardo's Law of Succession
An interactive demo exploring an alternative to Laplace's Rule of Succession, with a more realistic prior over probabilities

Read the full explanation in my [LessWrong post](https://www.lesswrong.com/posts/Gycja4SwB5T4qPW9k/rethinking-laplace-s-rule-of-succession).

## The Prior Distribution

w1 * lognormal(0, sigma^2) + w2 * 0.5(dirac(0) + dirac(1)) + w3 * thomae_{100}(α) + w4 * uniform(0,1)

Default parameters:
- w1 = 0.3 (lognormal component)
- w2 = 0.2 (deterministic component)
- w3 = 0.3 (rational component)
- w4 = 0.2 (uniform component)
- sigma = 5.0 (spread of lognormal)
- alpha = 2.0 (decay rate of rational weights)


