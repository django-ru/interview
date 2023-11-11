1. что выведет код?
```python
d = {True: 'yes', 1: 'no', 1.0: 'maybe'}
print(len(d))
```

<details>
	<summary>Ответ</summary>

если посмотреть на вывод функции `hash` для каждого ключа:

```    
hash(True)
Out[5]: 1

hash(1)
Out[6]: 1

hash(1.0)
Out[7]: 1
```

то будет видно что все 3 ключа имеют одинаковый хеш
и если распечатать `d` то увидим
```python
print(d)
{True: 'maybe'}
```

правильный ответ на вопрос - 1
</details>
