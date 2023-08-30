## 新开普 前置服务管理平台 service.action 远程命令执行漏洞

### 漏洞描述

新开普 前置服务管理平台 service.action 接口存在远程命令执行漏洞，攻击者通过漏洞可以获取服务器权限

### 依赖库
```
pip install argparse requests rich
```

### 使用

```
python poc2.py -h
```

![image](https://github.com/zh-byte/rce/assets/81899489/5b1689f4-0ac8-47a3-8dff-6dbac96d24c3)

### 下面是跑的结果

![image](https://github.com/zh-byte/rce/assets/81899489/0a042ee2-f688-4e50-a793-82c3816239c7)
