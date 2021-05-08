# FuckUnicom
借助V2Ray实现联通免流

# 使用说明
在服务器上执行以下命令
```
wget https://github.com/EraserCN/FuckUnicom/blob/main/install.sh
wget https://github.com/EraserCN/FuckUnicom/blob/main/config.json
```

> 之后强烈建议修改config.json之UUID

# 再执行以下命令

```
bash install.sh
systemctl enable v2ray
cp config.json /usr/local/etc/v2ray/config.json
systemctl start v2ray
```
