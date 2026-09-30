# 本地生活服务图片工厂：规则数据

规则版本 **1790782473702205200**：[规则Release](https://github.com/eish1997/local-service-factory-rules/releases/tag/rules-1790782473702205200)，最低软件版本 **1.4.2**。[软件安装包](https://github.com/eish1997/local-service-factory-releases/releases/download/v1.4.2/LocalServiceFactory-1.4.2-setup.exe)。`release-index.json` 指向签名校验后的最新规则，客户端原子激活。

本次只改两份数据：`configs/postprocess.json` 与 `projects/truck_rescue/variable_catalog.json`。电话底板固定透明，模板内随机不能重新添加；电话字号、居中、配色和描边保留，服务词底板继续允许变化。货车目录revision5启用10种手机和10种专业相机变量；专业相机分支与三拼满画布修复由软件1.4.2提供，不把Python代码放入规则包。

18个结构模板与4个兼容预设继续使用当前任务的确认电话和服务词。汽车/货车新共享批次自动轮换结构，旧批次保留冻结版本，已有图片不会自动重做。相机参数仅描述生成风格，不证明真实设备拍摄。

完整规则包37个白名单数据文件、八业务检查通过。客户电话、图片、任务、随机结果、预览、凭证及机器路径均不发布。ZIP SHA256：`4ece3eb7daecaa9505fcf737c69ed94e11ac7ab353fba0754a3bd99438e30b10`。

真实公开下载、Ed25519签名、全新独立引擎使用端首次updated→再次current以及活动指针/manifest一致验证通过。因既有代理共享出口匿名API限流，隔离验证子进程使用官方API直连、资源仍经既有代理，无发布凭证；未修改应用协议。维护端同步只检查基准，不覆盖本地编辑。

维护者先执行 `python factory.py rules release-plan` 检查，按明确发布指令执行 `rules publish`；兼容参数独立更新，软件代码通过安装包分发。
