# Python Snippets

This is the collection of snippets provided by Python extensions.

---

#### [Python](https://marketplace.visualstudio.com/items?itemName=ms-python.python)

- Snippets for Python

```py
# Sample:
# Type async/def
async def funcname(parameter_list):
    pass

# Type async/for
async for target in iter:
    block

# Type async/for/else
async for target in iter:
    block
else:
    block

# Type async/with
async with expr as var:
    block

# Type class
class classname(object):
    pass

# Type def
def funcname(parameter_list):
    pass

# Type def(abstract class method)
def funcname(self, parameter_list):
    raise NotImplementedError

# Type def(class method)
def funcname(self, parameter_list):
    pass

# Type def(static class method)
@staticmethod
def funcname(parameter_list):
    pass

# Type elif
elif expression:
    pass

# Type else
else:
    pass

# Type for
for target_list in expression_list:
    pass

# Type for/else
for target_list in expression_list:
    pass
else:
    pass

# Type if
if expression:
    pass

# Type if/else
if condition:
    pass
else:
    pass

# Type ipdb
import ipdb; ipdb.set_trace()

# Type lambda
lambda parameter_list: expression

# Type __name__
if __name__ == "__main__":
    pass

# Type pdb
import pdb; pdb.set_trace()

# Type pudb
import pudb; pudb.set_trace()

# Type try/except
try:
    pass
except expression as identifier:
    pass

# Type try/except/else
try:
    pass
except expression as identifier:
    pass
else:
    pass

# Type try/except/else/finally
try:
    pass
except expression as identifier:
    pass
else:
    pass
finally:
    pass

# Type try/except/finally
try:
    pass
except expression as identifier:
    pass
finally:
    pass

# Type try/finally
try:
    pass
finally:
    pass

# Type while
while expression:
    pass

# Type while/else
while expression:
    pass
else:
    pass

# Type with
with expression as target:
    pass
```
