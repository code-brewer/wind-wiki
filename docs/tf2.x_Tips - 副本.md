運行一個簡單的例子都報錯：

```python
      1 import tensorflow as tf
      2 hello = tf.constant('Hello, TensorFlow!')
----> 3 sess = tf.Session()
      4 print(sess.run(hello))

AttributeError: module 'tensorflow' has no attribute 'Session'
```



GOOGLE 得到： 

```
https://github.com/tensorflow/tensorflow/issues/26816


```

 

