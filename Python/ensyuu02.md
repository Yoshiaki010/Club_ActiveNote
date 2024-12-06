# Add one(Ver.int)

0以上10以下の整数Nが入力されるので、それに1を足したものを出力してください。

## 制約

0 ≦ N ≦ 10

### 入力例

```code
0
```

### 出力例

```code
1
```

### 回答例1

```python
n = int(input())
print(n+1)
```

### 回答例2

```python
n = int(input())
n = n + 1
# 「n += 1」も、上と同義
print(n)
```

### 回答例3

```python
print(int(input()) + 1)
```
