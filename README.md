本工具仅供学习和开发测试使用，请勿用于非法用途。
本项目ai开发，bug很多可以提issue，我会尽快修复。最好点个star
# QQ 经典农场助手

一个智能化的 QQ 经典农场托管工具，支持自动收菜、种植、巡田等功能。

### 环境要求

- Docker
- Docker Compose

### 使用镜像（推荐）

下载整个项目，运行以下命令启动容器：

```bash
docker-compose up -d
```
### 访问控制面板

打开浏览器访问：

```
http://localhost:3000
```

## 注意事项

1. **安全性**: 使用扫码登录，无需输入 QQ 密码
2. **稳定性**: 支持断线重连和自动恢复
3. **持久化**: 配置和数据保存在 `data/` 目录

## 许可证

MIT License
## 致谢

本项目基于 https://github.com/QianChenJun/qq-farm-bot 添加docker
扫码功能-https://github.com/lkeme/QRLib
