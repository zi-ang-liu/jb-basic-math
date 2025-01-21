# Sample Space and Probability

## Element of a Probabilistic Model

- **Sample Space**: The set of all possible outcomes of an experiment. It is denoted by $\Omega$.
- **Event**: A subset of the sample space. For example, $A \subseteq \Omega$.
- **Probability Law**: A function that assigns a non-negative number to an event. $P(A)$ is the probability of event $A$.

## Probability Axioms

1. **(Non-negativity)**: $P(A) \geq 0$ for all events $A$.
2. **(Additivity)**: If $A$ and $B$ are disjoint events, then $P(A \cup B) = P(A) + P(B)$. 
3. **(Normalization)**: $P(\Omega) = 1$.

## Properties of Probability Laws

1. If $A \subseteq B$, then $P(A) \leq P(B)$.
2. $P(A \cup B) = P(A) + P(B) - P(A \cap B)$.
3. $P(A \cup B) \leq P(A) + P(B)$.
4. $P(A \cup B \cup C) = P(A) + P(A^c \cap B) + P(A^c \cap B^c \cap C)$.

## Conditional Probability

Consider two events $A$ and $B$ with $P(B) > 0$. The conditional probability of $A$ given $B$ is defined as: 

$$
P(A|B) = \frac{P(A \cap B)}{P(B)}
$$

For a fixed event $B$, the function $P(\cdot|B)$ is a probability law. Hence, it satisfies the axioms of probability.

1. **(Non-negativity)**: $P(A|B) \geq 0$.
2. **(Additivity)**: $P(A \cup C|B) = P(A|B) + P(C|B)$ if $A \cap C = \emptyset$.
3. **(Normalization)**: $P(\Omega|B) = 1$.

In addition, sometimes we know $P(A|B)$ and $P(B)$, and we want to find $P(A \cap B)$. This can be done by rearranging the definition of conditional probability:

$$
P(A \cap B) = P(A|B) \cdot P(B)
$$

