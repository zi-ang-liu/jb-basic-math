# Sets

A set is a collection of objectives in which repetition is not allowed. Sets are commonly denoted by capital letters in italic form. For example, $A$, $B$, $C$, etc. The elements of a set are enclosed in curly brackets. For example, $A = \{1, 2, 3, 4, 5\}$.

An empty set is a set that does not contain any element. It is denoted by $\emptyset$ or $\{\}$.

## Membership

The symbol $\in$ is used to denote that an element belongs to a set. 

- $x \in S$: that $x$ is an element of the set $S$.
- $x \notin S$: that $x$ is not an element of the set $S$.

## Definition and Notation

### Roster Form

In the roster form, the elements of a set are listed within curly brackets. For example, $\{1, 2, 3, 4, 5\}$.

Large sets can be defined by listing the first few elements, followed by ellipses ($\ldots$) and the last element. For example, $\{1, 2, 3, \ldots, 100\}$ is the set of all natural numbers from 1 to 100.

Infinite sets can be defined by listing the first few elements, followed by ellipses ($\ldots$). For example, $A = \{0, 1, 2, 3, \ldots\}$ is the set of all non-negative integers.

### Set-Builder Form

In the set-builder form, the elements of a set are defined by a property that they satisfy. Consider the set of $x$ that have certain property $P$. This set can be denoted as $\{x \mid x \text{ has property } P\}$. The vertical bar "$\mid$" is read as "such that". 

For example, the set of all $x$ in the interval $[0, 1]$ can be defined as $\{x \mid 0 \leq x \leq 1\}$. Similarly, the set of all integers that are at least 5 and less than 10 can be defined as $\{x \in \mathbb{Z} \mid 5 \leq x < 10\}$. Here, $\mathbb{Z}$ denotes the set of integers.

## Special Sets

- $\mathbb{Z}$: The set of integers, $\{\ldots, -3, -2, -1, 0, 1, 2, 3, \ldots\}$.
- $\mathbb{N}$: The set of natural numbers, $\{0, 1, 2, 3, \ldots\}$. Some definitions include 0 in the set of natural numbers, while others do not.
- $\mathbb{Q}$: The set of rational numbers, $\left\{x \in \mathbb{R} \mid x = a/b, \text{ where } a, b \in \mathbb{Z} \text{ and } b \neq 0\right\}$.
- $\mathbb{R}$: The set of real numbers.
- $\mathbb{R}^+$: The set of positive real numbers, $\{x \in \mathbb{R} \mid x > 0\}$.

## Relations and Operations

- **Equality**: Two sets are equal if they have the same elements. For example, $\{1, 2, 3\} = \{3, 2, 1\}$. 
- **Subset**: A set $A$ is a subset of a set $B$ if every element of $A$ is also an element of $B$. This is denoted as $A \subseteq B$. If $A$ is a subset of $B$ but not equal to $B$, it is denoted as $A \subset B$.
- **Superset**: $A \supseteq B$ means $B \subseteq A$. Similarly, $A \supset B$ means $B \subset A$.
- **Union**: The union of two sets $A$ and $B$ is the set of elements that are in $A$, in $B$, or in both. It is denoted as $A \cup B$. For example, if $A = \{1, 2, 3\}$ and $B = \{3, 4, 5\}$, then $A \cup B = \{1, 2, 3, 4, 5\}$.
- **Intersection**: $A \cap B$ is the set of elements that are in both $A$ and $B$. For example, if $A = \{1, 2, 3\}$ and $B = \{3, 4, 5\}$, then $A \cap B = \{3\}$.
- **Difference**: $A - B$ is the set of elements that are in $A$ but not in $B$. For example, if $A = \{1, 2, 3\}$ and $B = \{2, 4, 6\}$, then $A - B = \{1, 3\}$. Sometimes, this is denoted as $A \setminus B$.
- **Complement**: Let $\Omega$ be the universal set. The complement of a set $A$ is the set of elements in $\Omega$ that are not in $A$. It is denoted as $A^c$ or $\bar{A}$. Using set difference, $A^c = \Omega - A$.

## The Algebra of Sets

The algebra of sets is a collection of rules and properties that describe the relationships between sets and the operations that can be performed on them. Some of the key properties include:

- $A \cup B = B \cup A$
- $A \cap B = B \cap A$
- $A \cup (B \cap C) = (A \cup B) \cap (A \cup C)$
- $A \cap (B \cup C) = (A \cap B) \cup (A \cap C)$
- $A \cup \Omega = \Omega$
- $A \cap \Omega = A$
- $A \cup A^c = \Omega$
- $A \cap A^c = \emptyset$

The De Morgan's laws are also important in set theory:

- $(A \cup B)^c = A^c \cap B^c$
- $(A \cap B)^c = A^c \cup B^c$

The rules can be expressed as:

- not (A or B) = (not A) and (not B)
- not (A and B) = (not A) or (not B)

In general, the laws can be expressed for $n$ sets as:

- $\left(\bigcup_{i=1}^{n} A_i\right)^c = \bigcap_{i=1}^{n} A_i^c$
- $\left(\bigcap_{i=1}^{n} A_i\right)^c = \bigcup_{i=1}^{n} A_i^c$

Suppose that $x \in \left(\bigcup_{i=1}^{n} A_i\right)^c$. Then, $x \notin \bigcup_{i=1}^{n} A_i$. This implies that $x \notin A_i$ for all $i$. Therefore, $x \in A_i^c$ for all $i$, and hence $x \in \bigcap_{i=1}^{n} A_i^c$. This proves that $\left(\bigcup_{i=1}^{n} A_i\right)^c \subseteq \bigcap_{i=1}^{n} A_i^c$. The reverse inclusion can be proved similarly.

