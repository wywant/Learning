# packags tensorflow.python.ops.gen_math_ops
## description
在寻找sigmoid源代码的过程中，遇到package tensorflow.python.ops.gen_math_ops,但是在tensorflow的github repository里面没有找到。
最后在 https://stackoverflow.com/questions/36783977/where-is-gen-math-ops-script-in-tensorflow 的帮助下找到了

## get path
```python
from tensorflow.python.ops import gen_math_ops
print(gen_math_ops)
```
运行上面的代码，得到如下结果
```
<module 'tensorflow.python.ops.gen_math_ops' from 'C:\\Users\\username\\AppData\\Local\\Programs\\Python\\Python36\\lib\\site-packages\\tensorflow\\python\\ops\\gen_math_ops.py'>
```
## conclusion
找到的源代码也不是真正的python代码  
生成的代码和一些[rules](https://github.com/tensorflow/tensorflow/blob/master/tensorflow/tensorflow.bzl) 有关.  
也就是说tensorflow的部分代码，是通过bazel生成的。具体的就先不研究了。

