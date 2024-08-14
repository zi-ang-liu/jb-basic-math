# Collections

## Sets

A set is a collection of objectives in which repetition is not allowed. Sets are commonly denoted by capital letters in italic form. For example, $A$, $B$, $C$, etc. The elements of a set are enclosed in curly brackets. For example, $A = \{1, 2, 3, 4, 5\}$.

An empty set is a set that does not contain any element. It is denoted by $\emptyset$ or $\{\}$.

### Membership

The symbol $\in$ is used to denote that an element belongs to a set. For example, $x \in S$ means that $x$ belongs to the set $S$. On the other hand, $x \notin S$ means that $x$ does not belong to the set $S$. For example, if $S = \{1, 2, 3, 4, 5\}$, then $1 \in S$ and $6 \notin S$.

### Definition and Notation

#### Roster Form

In the roster form, the elements of a set are listed within curly brackets. For example, $\{1, 2, 3, 4, 5\}$.

Large sets can be defined by listing the first few elements, followed by ellipses ($\ldots$) and the last element. For example, $\{1, 2, 3, \ldots, 100\}$ is the set of all natural numbers from 1 to 100.

Infinite sets can be defined by listing the first few elements, followed by ellipses ($\ldots$). For example, $A = \{0, 1, 2, 3, \ldots\}$ is the set of all non-negative integers.

#### Set-Builder Form

In the set-builder form, the elements of a set are defined by a property that they satisfy. Consider the set of $x$ that have certain property $P$. This set can be denoted as $\{x \mid x \text{ has property } P\}$. The vertical bar "$\mid$" is read as "such that". 

For example, the set of all $x$ in the interval $[0, 1]$ can be defined as $\{x \mid 0 \leq x \leq 1\}$. Similarly, the set of all integers that are at least 5 and less than 10 can be defined as $\{x \in \mathbb{Z} \mid 5 \leq x < 10\}$. Here, $\mathbb{Z}$ denotes the set of integers.

### Special Sets

- $\mathbb{Z}$: The set of integers, $\{\ldots, -3, -2, -1, 0, 1, 2, 3, \ldots\}$.
- $\mathbb{N}$: The set of natural numbers, $\{0, 1, 2, 3, \ldots\}$. Some definitions include 0 in the set of natural numbers, while others do not.
- $\mathbb{Q}$: The set of rational numbers, $\left\{x \in \mathbb{R} \mid x = a/b, \text{ where } a, b \in \mathbb{Z} \text{ and } b \neq 0\right\}$.
- $\mathbb{R}$: The set of real numbers.
- $\mathbb{R}^+$: The set of positive real numbers, $\{x \in \mathbb{R} \mid x > 0\}$.

### Relations and Operations

- **Equality**: Two sets are equal if they have the same elements. For example, $\{1, 2, 3\} = \{3, 2, 1\}$. 
- **Subset**: A set $A$ is a subset of a set $B$ if every element of $A$ is also an element of $B$. This is denoted as $A \subseteq B$. If $A$ is a subset of $B$ but not equal to $B$, it is denoted as $A \subset B$.
- **Superset**: $A \supseteq B$ means $B \subseteq A$. Similarly, $A \supset B$ means $B \subset A$.
- **Union**: The union of two sets $A$ and $B$ is the set of elements that are in $A$, in $B$, or in both. It is denoted as $A \cup B$. For example, if $A = \{1, 2, 3\}$ and $B = \{3, 4, 5\}$, then $A \cup B = \{1, 2, 3, 4, 5\}$.
- **Intersection**: 
