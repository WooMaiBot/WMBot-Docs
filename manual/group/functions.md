# 群组功能设置

群组管理员可以启用或禁用部分机器人功能。

## 使用方式

以下指令均需要群组管理员权限。

```
# 启用功能
/function enable <功能名称>

# 禁用功能
/function disable <功能名称>
```

## 支持的功能

| 名称               | 说明                                | 默认值 | 备注 |
| ------------------ | ----------------------------------- | ------ | ---- |
| `captcha`          | 入群验证                            | 启用   | *注1 |
| `url_probe`        | 链接探测                            | 禁用   | *注2 |
| `youtube_url`      | 识别 YouTube 视频链接并解析元数据   | 启用   | *注2 |
| `bilibili_url`     | 识别 Bilibili 视频链接并解析元数据  | 启用   | *注2 |
| `steam_url`        | 识别 Steam 个人资料链接并解析元数据 | 启用   | *注2 |
| `ehentai_url`      | 识别 E-Hentai 画廊链接并解析元数据  | 启用   | *注2 |
| `peeringdb_url`    | 识别 PeeringDB 链接并解析元数据     | 启用   | *注2 |
| `ncm_url`          | 识别网易云音乐分享链接并下载        | 启用   | *注2 |
| `shadowsocks_url`  | 解析 Shadowsocks URL 信息           | 启用   | *注2 |
| `shadowsocksr_url` | 解析 ShadowsocksR URL 信息          | 启用   | *注2 |
| `vmess_url`        | 解析 V2Ray URL 信息                 | 启用   | *注2 |

*注1: 操作开启/关闭的管理员须具有[用户管理权限](./permissions.md), 且机器人在群组中至少具有删除消息与封禁用户权限。

*注2: 该功能尚未推出。但目前可以调整此设置。
