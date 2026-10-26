# Natural Relationships 1.6.34

自然关系 1.6.34。下面的文件分别用于不同的 Minecraft 版本和加载器；只选择与你的游戏环境对应的一份。

## 下载

| Minecraft | 加载器 | 文件 | 状态 |
| --- | --- | --- | --- |
| 1.21.11 | Fabric | [原版 1.6.34](naturalrelationship-1.6.34+1.21.11.jar) | 原有交付，保留 |
| 1.21.1 | Fabric | [兼容测试包](compatibility/fabric-1.21.1/naturalrelationship-1.6.34-fabric-1.21.1.jar) | 完整构建、983项测试及生产加载通过 |
| 1.21.1 | NeoForge | [兼容测试包](compatibility/neoforge-1.21.1/naturalrelationship-1.6.34-neoforge-1.21.1.jar) | 完整构建、986项测试及生产加载通过 |
| 26.3 | Fabric | [兼容测试包](compatibility/fabric-26.3/naturalrelationship-1.6.34-fabric-26.3.jar) | 完整构建、983项测试及生产加载通过 |

三个兼容包独立构建，均基于原始 1.6.34；不包含正在开发的 1.7 功能。请勿同时安装多个自然关系 JAR。

## 对应环境

- Fabric 1.21.1：Java21、Fabric Loader0.18.2、Fabric API0.107.0+1.21.1、GeckoLib4.9.2；需要自然之需联动时，使用 `needsofnature-1.5.3-beta.2+1.21.1-fabric.jar`。
- NeoForge 1.21.1：Java21、NeoForge21.1.259、GeckoLib4.9.3；需要自然之需联动时，使用 `needsofnature-1.5.3-beta.2+1.21.1-neoforge.jar`。
- Fabric26.3：Java25、Fabric Loader0.19.5、Fabric API0.165.0+26.3、GeckoLib5.5.7；需要自然之需联动时，使用 `needsofnature-1.5.3-beta.2+26.3-fabric.jar`。可选JEI测试使用31.17.0.93及MezzConfig0.6.9，可选ModMenu测试使用21.0.0及Placeholder API3.2.0+26.3。

本仓库只提供自然关系，不重新分发 Minecraft、自然之需或其他第三方依赖。自然之需的完整动画和内容包请按该模组自身要求安装。

## 已验证范围与限制

三套兼容包分别通过完整构建及全部测试；成品JAR在有、无自然之需的独立服务端均完成启动、资源重载、保存和正常停止。客户端已使用对应自然之需及JEI进入独立测试世界。

尚未完成画面和完整自然之需互动验收，也未验证客户端正常退出、长时间多人游戏及所有旧存档情况。请先在备份或新建的测试存档中使用。

跨维度召回按本次兼容范围暂时关闭，待后续恢复；同维度召回保留。不要把测试包的加载通过理解为所有玩法及视觉均已验收。

## 校验

原始1.21.11包SHA256：`A2287A753F5B8AD4726D452271DA37384B5D363F014C1E916EF97C1398C5B5D0`。

三个兼容包的SHA256记录在 [SHA256SUMS.txt](compatibility/SHA256SUMS.txt)。

第三套的独立离线测试中出现了 Windows 性能计数器读取错误，以及离线测试身份导致的账号／Realms认证错误；这些日志已单独记录，客户端仍成功进入并保存世界。未把这些记录当作画面或完整互动通过的证据。
