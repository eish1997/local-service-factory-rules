# 本地生活服务图片工厂：规则数据

本仓库分发项目规则、场景变量和提示词配置，软件安装包在 [软件仓库](https://github.com/eish1997/local-service-factory-releases)。

规则版本 **1790730656981293500** 已正式发布：[规则 Release](https://github.com/eish1997/local-service-factory-rules/releases/tag/rules-1790730656981293500)。`release-index.json` 指向经过签名校验的最新版本，客户端会自动下载并激活。

规则包包含 36 个白名单文件，8 个业务组装验证通过。已排除电话、API 凭证、机器路径和客户历史。规则 ZIP SHA256：`4243d3b40ec8ea068e511e039eb22df2fd966bdaaeeb6f468f5344b3e76e974a`。已验证真实公开下载、签名以及使用端同步。

维护者通过 `python factory.py rules release-plan` 检查，再按明确发布指令使用 `rules publish`。日常本地修改不自动上传。新批次使用当前激活规则，旧批次继续使用冻结版本。Python 提示词算法随软件发行，规则数据通过本仓库独立更新。
