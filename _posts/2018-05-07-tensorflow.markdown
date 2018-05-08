---
layout: post
title: tensorflow install
date: 2018-05-07 15:32:24.000000000 +09:00
---

### 1.安装python虚拟环境  
```
$ pip install virtualenv
$ virtualenv --version
$ cd my_project_folder
$ virtualenv my_project
$ virtualenv -p /usr/bin/python2.7 my_project
$ source my_project/bin/activate
```

### 2.mac安装TensorFlow 
```shell
pip install --ignore-installed --upgrade https://storage.googleapis.com/tensorflow/mac/tensorflow-0.9.0-py3-none-any.whl
```
### 3.运行helloworld
```python
python 
import tensorflow as tf
hello = tf.constant('hello world!')
sess = tf.Session()
sess.run(hello)

sess.close()
```



[jekyll-docs]: http://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/
