# 中国大陆连接性测试

测试 IP、端口或域名在中国大陆的连接性。

## Usage

### DNS 测试

``` 
/gfwtest dns <Domain>
```

### Ping 测试

``` 
/gfwtest ping <Host>
```

### TCP 测试

```
/gfwtest tcp <Host> <Port>
```

### TLS 握手测试

```
/gfwtest tls <Host> [Port] [Server Name]
```

> 如不指定 Server Name, 则以 Host 作为 SNI。
