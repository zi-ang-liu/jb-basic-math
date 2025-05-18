# Numpy

## Basic Exercises

### Basic-Q1

`numpy`を使って、1から10までの整数の配列を作成せよ。

```python
import numpy as np
# your code here
print(arr)  # [ 1  2  3  4  5  6  7  8  9 10]
```

### Basic-Q2

リスト`[1, 2, 3]`を`numpy`の配列に変換せよ。

```python
import numpy as np
# your code here
print(arr)  # [1 2 3]
```

### Basic-Q3

ベクトル$\mathbf{x}$と$\mathbf{y}$は次のように定義されているとする。

$$
\mathbf{x} = \begin{pmatrix} 1 \\ 2 \\ 3 \end{pmatrix}, \quad
\mathbf{y} = \begin{pmatrix} 4 \\ 5 \\ 6 \end{pmatrix}
$$

ベクトル$\mathbf{x}$と$\mathbf{y}$の内積、要素ごとの積を計算せよ。

```python
import numpy as np
# your code here
print(inner_product)  # 32
print(elementwise_product)  # [ 4 10 18]
```

### Basic-Q4

行列$\mathbf{A}$は次のように定義されているとする。

$$
\mathbf{A} = \begin{pmatrix} 1 & 2 \\ 3 & 4 \end{pmatrix}
$$

行列$\mathbf{A}$の転置行列を計算せよ。

```python
import numpy as np
matrix_a = np.array([[1, 2], [3, 4]])
# your code here
print(transpose_a)  # [[1 3] [2 4]]
```

### Basic-Q5

行列$\mathbf{A}$と$\mathbf{B}$は次のように定義されているとする。

$$
\mathbf{A} = \begin{pmatrix} 1 & 2 \\ 3 & 4 \end{pmatrix}, \quad
\mathbf{B} = \begin{pmatrix} 5 & 6 \\ 7 & 8 \end{pmatrix}
$$

行列$\mathbf{A}$と$\mathbf{B}$の積を計算せよ。

```python
import numpy as np
matrix_a = np.array([[1, 2], [3, 4]])
matrix_b = np.array([[5, 6], [7, 8]])
# your code here
print(product_ab)  # [[19 22] [43 50]]
```

