自动编译在24小时内源码有更新的插件，或手动指定插件编译！



**默认**

编译`x86_64`平台插件



**单个编译插件**

`Packages`运行→`luci-app-`改为`luci-app-autoupdate`，则只编译`luci-app-autoupdate`



**编译指定插件**

`Packages`运行→`luci-app-`改为`luci-app-(aria2|acme) `，编译`luci-app-aria2`和`luci-app-acme`



**编译所有luci-app软件包**

`Packages`运行→`luci-app-`改为`luci-app`，编译所有 luci-app 软件包



**编译所有软件包**

`Packages`运行→`luci-app-`改为`.*`，则编译所有软件包



**编译2天内更新的所有软件包**

`Packages`运行→`luci-app-`改为`.*2`，则编译最近两天内有更新的软件包



**编译mipsel_24kc系统插件**

`Packages`运行→`luci-app-`改为`mipsel_24kc`，则只编译`mipsel_24kc`平台插件，适用于xiaomi_mi-router-3-pro等路由器

