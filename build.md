#  docker build

修改检查网址

修改`setting.py`

```python
# 代理验证目标网站
HTTP_URL = "http://httpbin.org"

HTTPS_URL = "https://www.google.com"
# HTTPS_URL = "https://www.qq.com"
```


> docker build -t proxy_pool_google .