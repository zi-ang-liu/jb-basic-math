# クラス

## Basic Exercises

### Basic-Q1

`name`, `age`の2つの属性を持つ`Person`クラスを定義せよ。`info()`メソッドを定義し、`name`と`age`を表示するようにせよ。

```python
class Person:
    def __init__(self, name, age):
        # your code here

    def info(self):
        # your code here

alice = Person("Alice", 30)
alice.info()  # Name: Alice, Age: 30 と表示される
```

### Basic-Q2

`Turtle`クラスを定義せよ。`Turtle`クラスは、`name`, `position`の2つの属性を持ち、`move()`メソッドを定義し、指定された上下左右の方向に1歩移動するようにせよ。`position`の初期値は`(0, 0)`とする。

```python
class Turtle:
    def __init__(self, name, position=(0, 0)):
        # your code here

    def move(self, direction):
        """
        Parameters
        ----------
        direction : str
            "up", "down", "left", "right"のいずれか
        """
        # your code here
        # 例: positionが(0, 0)のとき、"up"を指定するとpositionは(0, 1)になる
    
shelly = Turtle("Shelly")
print(shelly.position)  # (0, 0)

shelly.move("up")
print(shelly.position)  # (0, 1)

shelly.move("right")
print(shelly.position)  # (1, 1)
```
