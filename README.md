# 无操作息屏

无操作息屏(io.github.imroxy2222.autoscreenoffcode)
Xposed模块,基于LibXposed102开发

# 核心功能

可全局或单独对特定APP设置无操作息屏时间, 防止刷短视频过程中睡着, 第二天手机没电/发热巨大等问题

模块只检测触摸操作, 当指定息屏时间内无操作时, 将强制息屏

# 适配环境

系统要求: Android8+(理论)

- 已测试android13(flyme10.5)
- 已测试android15(hyperOS3.5)
- 已测试android16(colorOS16)

框架要求: 兼容LibXposed 102 API

# 开源许可

本项目遵循: https://github.com/imRoxy2222/lsp_AutoSceenOff/blob/master/LICENSE 开源

# 免责声明

项目基于混元4preview大模型
hook system有风险,如遇卡开机等情况, 可以进入安全模式
kernelSU在开机第一屏连续按音量减3次, 其他管理器自行查询
