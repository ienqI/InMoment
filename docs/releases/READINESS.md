# 发布状态

**InMoment 1.0.0** 于 2026 年 11 月 26 日正式发布，适用于 Windows 11 x64。从 [InMoment 下载页](https://ienqi.github.io/InMoment/) 点击「下载 Windows 版」获取安装包。

## 下载与配套资料

- 安装包 `InMoment-Setup-1.0.0-x64.exe` 可选择安装位置，内置程序运行时、原生助手、离线转写、语义模型和图片 OCR。
- 安装包的 SHA-256 校验文件在下载页提供。安装包内含原始许可证，第三方许可与对应源码按配套清单提供。[第三方许可与源码清单](../../OPEN_SOURCE_DOWNLOADS.md)
- 安装、升级和版本变化见 [1.0.0 更新说明](1.0.0.md)与[使用指南](../USER_GUIDE.md)。历史构建见[版本清单](VERSIONS.md)。

## 1.0.0 验证结果

| 验证项 | 结果 |
| --- | --- |
| 公开下载页 | 点击「下载 Windows 版」后，浏览器留在原页并完成下载。文件大小为 617,157,120 字节，SHA-256 与发布包一致。 |
| Windows 11 x64 虚拟机 | 在 Windows 11 企业评估版 LTSC 26100 上，用实际下载的安装包从 0.14.31 覆盖安装到 1.0.0。核对了版本、路径、主程序、卸载程序、开始菜单入口和应用窗口。 |
| 定向测试 | 596 项通过，1 项桌面交互测试跳过。 |

全新 Windows 环境安装、跨应用操作、真实语音识别和云端服务效果待对应环境验收。历次功能检查见[验证记录](../validation.md)。

## 运行条件

电脑缺少 VC++ x64 运行库时，向导会征得同意，再从微软下载安装。系统可能要求管理员授权。安装包目前未进行 Windows 代码签名。GPT 与 DeepSeek 的 MP4 抽帧路径另需 FFmpeg 和 ffprobe。[使用指南](../USER_GUIDE.md#随手问-ai)

2026 年 11 月 14 日的生产依赖公告检查匹配到 0 项已知漏洞。OCR 所附 FFmpeg DLL 已与 OpenCV 官方发布件匹配，配套附件收录对应源码与构建材料。[依赖检查](DEPENDENCY_REVIEW.md) · [第三方源码说明](../../THIRD_PARTY_SOURCE_OFFER.md#offline-ocr-and-opencvs-ffmpeg-library)
