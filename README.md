# 接口加密工具
- @Encrypt 加密接口使用在方法和参数上

- @Decrypt 解密工具使用在方法上

# 配置文件
```yaml
# 配置key，加密的容错
spring:
  encrypt:
  ## 密钥需要16字节
    key: zlf6667788888222
```

**接口加密结果返回时需要使用该工具自带的RespBean**
