# Python スニペット集

Python 系の拡張機能に用意されているスニペット集です。

---

#### [Python](https://marketplace.visualstudio.com/items?itemName=ms-python.python)

- Python 用スニペット。

```py
# 例）
# async/def と入力
async def funcname(parameter_list):
    pass

# async/for と入力
async for target in iter:
    block

# async/for/else と入力
async for target in iter:
    block
else:
    block

# async/with と入力
async with expr as var:
    block

# class と入力
class classname(object):
    pass

# def と入力
def funcname(parameter_list):
    pass

# def(abstract class method) と入力
def funcname(self, parameter_list):
    raise NotImplementedError

# def(class method) と入力
def funcname(self, parameter_list):
    pass

# def(static class method) と入力
@staticmethod
def funcname(parameter_list):
    pass

# elif と入力
elif expression:
    pass

# else と入力
else:
    pass

# for と入力
for target_list in expression_list:
    pass

# for/else と入力
for target_list in expression_list:
    pass
else:
    pass

# if と入力
if expression:
    pass

# if/else と入力
if condition:
    pass
else:
    pass

# ipdb と入力
import ipdb; ipdb.set_trace()

# lambda と入力
lambda parameter_list: expression

# __name__ と入力
if __name__ == "__main__":
    pass

# pdb と入力
import pdb; pdb.set_trace()

# pudb と入力
import pudb; pudb.set_trace()

# try/except と入力
try:
    pass
except expression as identifier:
    pass

# try/except/else と入力
try:
    pass
except expression as identifier:
    pass
else:
    pass

# try/except/else/finally と入力
try:
    pass
except expression as identifier:
    pass
else:
    pass
finally:
    pass

# try/except/finally と入力
try:
    pass
except expression as identifier:
    pass
finally:
    pass

# try/finally と入力
try:
    pass
finally:
    pass

# while と入力
while expression:
    pass

# while/else と入力
while expression:
    pass
else:
    pass

# with と入力
with expression as target:
    pass
```
