# 本地生活服务图片工厂：规则数据

本仓库用于分发项目规则、场景变量和提示词配置，软件安装包在 [软件仓库](https://github.com/eish1997/local-service-factory-releases)。

## 首批规则快照

`snapshots/1790730656981293500/rules.zip` 包含 36 个白名单文件，已通过 8 个业务的本地组装校验。已过滤电话、密钥、凭证、机器路径和私有记录。压缩包 SHA256：`4243d3b40ec8ea068e511e039eb22df2fd966bdaaeeb6f468f5344b3e76e974a`。

## 发布状态

当前仅保存经校验的仓库快照，尚未发布可被客户端自动更新的正式 Release。正式发布需要由维护端 `python factory.py rules publish` 生成签名清单、上传 Release，并在验证公开下载后更新 `release-index.json`。仓库快照不会自动激活更新。

新批次使用已激活的规则版本；旧批次继续使用冻结版本。提示词 Python 算法随软件更新发布；数据配置通过本仓库的规则更新发布。
