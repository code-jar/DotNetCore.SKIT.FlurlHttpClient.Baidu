﻿# CHANGELOG

### 版本说明

各 SDK 的版本号将遵循语义化版本规则。

在更新日志中会包含以下几种名词：

1.  “**新增**”：
    -   追加了新功能；
    -   一般不会产生破坏性更新。
2.  “**变更**”：
    -   可能重新实现了已有的功能，通常会带来使用方式上的变化；
    -   可能升、降级了第三方依赖库的版本。
    -   一般会产生破坏性更新。
3.  “**修复**”：
    -   修复了已知的一些问题；
    -   不会产生破坏性更新。

注意，预览版本（版本号将以 `-alpha`、`-beta`、`-rc` 结尾）不会在更新日志中呈现。如非必要，请不要将预览版本应用于生产项目。

自 v2.0.0 版本起，各 SDK 将与[公共组件](https://www.nuget.org/packages/SKIT.FlurlHttpClient.Common)的主版本号保持对齐关系，即：

-   SDK v2.x.x 将依赖公共组件 v2.x.x；
-   SDK v3.x.x 将依赖公共组件 v3.x.x。
-   依此类推。
