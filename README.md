## 扁平化列表方法
> ① expansion : 递归方法实现多维列表扁平化
> ② expansion_up : 生成器方法实现多维列表扁平化





```python
"""
可以参考怎么样发布你的 Python 代码给别人 “pip install”来发布自己的pypi包。如果需要更新包的话，可以通过以下几个步骤完成。

第一步：更新代码
这个比较简单也比较基础，把经过测试的代码更新到package中的.py文件即可。

第二步：更新版本号信息
打开setup.py文件，然后修改对应的信息，比如版本号等等。

第三步：使用以下指令更新包体

python setup.py sdist bdist
1
第四步：使用以下指令把新包体上传到pypi服务器上

twine upload dist/*
1
第五步：使用以下指令更新python中的包体

pip install --upgrade certimaker
————————————————
版权声明：本文为CSDN博主「梧桐雪」的原创文章，遵循CC 4.0 BY-SA版权协议，转载请附上原文出处链接及本声明。
原文链接：https://blog.csdn.net/weixin_41855010/article/details/105506343
"""
```