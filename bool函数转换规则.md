# bool 函数转换规则

以下代码：
```python
print(bool("1"))           # True
print(bool("0"))           # True
print(bool("-2"))          # True
print(bool(""))            # False
print(bool(" "))           # True
print(bool(1))             # True
print(bool(-1))            # True
print(bool(0))             # False
print(bool([]))            # False
print(bool([1]))           # True
print(bool(()))            # False
print(bool(('a',)))        # True
print(bool({}))            # False
print(bool({'b': 2}))      # True
print(bool(set()))         # False
print(bool(set((1, '2')))) # True
print(bool('None'))        # True
print(bool(None))          # False
```

bool 函数进行转换时，其结果取决于传入参数与 True 和 False 的等价关系，只需记住一点即可：
> 空字符串（""），数字零（0），空列表（[]），空元组（()），空字典（{}），空集合（set()）与 None 在条件判断语句中等价于 False，其他数值都等价于 True。