# kb

kb 是一个简单的性能测试脚本，通过`协程`模拟并发请求。

## install

```shell
> pip3 install requirements.txt
```

## 使用

修改脚本中的`URL`、`并发用户`和`请求数`。

```py
users = 10  # 用户数
numbers = 100  # 请求次数
req_url = "http://127.0.0.1:5000/user/tom"  # 请求URL

```

## 运行

```shell
python3 kb.py
请求URL: http://127.0.0.1:5000/user/tom
用户数：10，循环次数: 100
============== Running ===================
.................................................................
.................................................................
.................................................................
.................................................................
.................................................................
.................................................................
.................................................................
.................................................................
.................................................................
.................................................................
.................................................................
.................................................................
.................................................................
.................................................................
.................................................................
.........................
============== Results ===================
最大:       0.713 s
最小:       0.0071 s
平均:       0.0444 s
请求成功 1000
请求失败 0
============== end ===================
```
