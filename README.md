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

# 最后导入V2Ray连接

```
vmess://eyJhZGQiOiLkv67mlLnkuLrkvaDnmoTmnI3liqHlmahpcCIsImFpZCI6IjgiLCJob3N0IjoicHVsbC5mcmVlLnZpZGVvLjEwMDEwLmNvbSIsImlkIjoiM2ZkMzUzODEtZDczNC00NTQyLTk1MzEtZjUxZDk0M2U1Y2MwIiwibmV0Ijoid3MiLCJwYXRoIjoiL2dpdGh1YmVyYXNlcmNuIiwicG9ydCI6IjQ0MyIsInBzIjoiZXhhbXBsZSIsInNuaSI6IiIsInRscyI6IiIsInR5cGUiOiJub25lIiwidiI6IjIifQ==
```

然后您的流量就不要钱了
## 鸣谢
![Hunk Zhang](https://t.me/hunkzhang)
