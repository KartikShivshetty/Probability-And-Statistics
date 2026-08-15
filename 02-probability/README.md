# Chapter 2 — Probability

## Overview

This chapter covers the fundamentals of probability, random experiments, events, sample spaces, addition and multiplication laws of probability, conditional probability, Bayes theorem, and the total probability theorem. Probability helps in predicting outcomes and making decisions under uncertainty.

## Learning Outcomes

### Random Experiments
Learned concepts of trials, events, exhaustive cases, and mutually exclusive events.

### Probability Laws
Understood addition rule, multiplication rule, and probability calculations for multiple events.

### Conditional Probability
Learned probability of an event under given conditions and dependent events.

### Bayes Theorem
Applied Bayes theorem to update probabilities based on new information.

## Probability Visualization

The original portfolio includes an example visualization of equally likely outcomes using the **rolling of a die**.

## Important Probability Formulas

### Basic Probability

$$
P(E) = \frac{\text{Favorable Outcomes}}{\text{Total Outcomes}}
$$

Probability of occurrence of an event.

### Addition Rule

$$
P(A \cup B) = P(A) + P(B) - P(A \cap B)
$$

Used for the probability of the union of two events.

### Multiplication Rule

$$
P(A \cap B) = P(A) \cdot P(B\mid A)
$$

Probability of occurrence of both events.

### Conditional Probability

$$
P(B\mid A) = \frac{P(A \cap B)}{P(A)}
$$

Probability of B when A has already occurred.

### Independent Events

$$
P(A \cap B) = P(A) \cdot P(B)
$$

Formula for independent events.

### Complementary Event

$$
P(A') = 1 - P(A)
$$

Probability that an event does not occur.

### Law of Total Probability

$$
P(A) = \sum_i P(A\mid B_i)P(B_i)
$$

Used when the sample space is partitioned.

### Bayes Theorem

$$
P(E_i\mid A)=\frac{P(E_i)P(A\mid E_i)}{\sum_i P(E_i)P(A\mid E_i)}
$$

Updates prior probability using evidence.

## Applications of Probability

| Application | Portfolio description |
|---|---|
| **Machine Learning** | Used in Bayesian classification and predictive models. |
| **Weather Forecasting** | Helps predict rainfall and climate conditions. |
| **Games & Simulations** | Probability is widely used in gaming and simulations. |
| **Engineering** | Used in reliability testing and risk analysis. |
