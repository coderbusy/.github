# 码农很忙 (CoderBusy)

欢迎来到**码农很忙**组织！我们致力于开发高质量、易用的 .NET 开源工具和库，帮助开发者提高生产力，简化日常开发工作。

## 🌟 我们的项目

### 🎨 [LuYao.Avalonia](https://github.com/coderbusy/luyao-avalonia)
![Stars](https://img.shields.io/github/stars/coderbusy/luyao-avalonia?style=social)
[![License](https://img.shields.io/github/license/coderbusy/luyao-avalonia)](https://github.com/coderbusy/luyao-avalonia/blob/main/LICENSE)

为 Avalonia UI 框架提供的实用控件和行为库，包含丰富的组件和字体集成。

**主要功能：**
- ImageFromFileBehavior - 从文件路径加载图像
- MiSans 字体集成
- FlagIcon 国家旗帜图标控件
- VirtualizingWrapPanel 虚拟化环绕面板

**NuGet 包：**
- [![NuGet](https://img.shields.io/nuget/v/LuYao.Avalonia.Behaviors.svg)](https://www.nuget.org/packages/LuYao.Avalonia.Behaviors) LuYao.Avalonia.Behaviors
- [![NuGet](https://img.shields.io/nuget/v/LuYao.Avalonia.Fonts.MiSans.Regular.svg)](https://www.nuget.org/packages/LuYao.Avalonia.Fonts.MiSans.Regular) LuYao.Avalonia.Fonts.MiSans.Regular

---

### 🛠️ [LuYao.Dotnet](https://github.com/coderbusy/luyao-dotnet)
![Stars](https://img.shields.io/github/stars/coderbusy/luyao-dotnet?style=social)
[![License](https://img.shields.io/github/license/coderbusy/luyao-dotnet)](https://github.com/coderbusy/luyao-dotnet/blob/main/LICENSE)
[![NuGet](https://img.shields.io/nuget/v/LuYao.Common.svg)](https://www.nuget.org/packages/LuYao.Common)

一个高质量、易用的 .NET 通用工具库，提供丰富的通用工具类和扩展方法。

**主要功能：**
- 缓存机制 (CachedObject)
- 哈希算法 (MD5, SHA1, CRC32, CRC64, Murmur128)
- 临时文件管理 (AutoCleanTempFile)
- 线程同步工具 (KeyedLocker, AsyncLock)
- 字符串压缩 (LZ-String, GZip)
- Hosts 文件管理
- 伪造用户代理 (FakeUserAgent)
- 限流器 (TokenBucket)
- 密码强度检测
- 文本分词与分析

**支持框架：** .NET Framework 4.5+, .NET Standard 2.0/2.1, .NET 6/7/8

**NuGet 包：**
- [![NuGet](https://img.shields.io/nuget/v/LuYao.Common.svg)](https://www.nuget.org/packages/LuYao.Common) LuYao.Common
- [![NuGet](https://img.shields.io/nuget/v/LuYao.Text.Json.svg)](https://www.nuget.org/packages/LuYao.Text.Json) LuYao.Text.Json
- [![NuGet](https://img.shields.io/nuget/v/LuYao.Text.Json.Jint.svg)](https://www.nuget.org/packages/LuYao.Text.Json.Jint) LuYao.Text.Json.Jint

---

### 🔐 [LuYao.TlsClient](https://github.com/coderbusy/luyao-tls-client)
![Stars](https://img.shields.io/github/stars/coderbusy/luyao-tls-client?style=social)
[![License](https://img.shields.io/github/license/coderbusy/luyao-tls-client)](https://github.com/coderbusy/luyao-tls-client/blob/main/LICENSE)
[![NuGet](https://img.shields.io/nuget/v/LuYao.TlsClient.svg)](https://www.nuget.org/packages/LuYao.TlsClient)

基于 [bogdanfinn/tls-client](https://github.com/bogdanfinn/tls-client) 的 .NET TLS 客户端库，提供高级 TLS 指纹模拟功能。

**主要功能：**
- 多浏览器 TLS 指纹模拟 (Chrome, Firefox, Safari, Opera 等)
- 跨平台支持 (Windows, Linux, macOS, Alpine)
- HttpClient 集成
- Cookie 会话管理
- Native AOT 支持

**支持框架：** .NET Framework 4.5/4.6.1, .NET Standard 2.0/2.1, .NET 6/7/8

**NuGet 包：**
- [![NuGet](https://img.shields.io/nuget/v/LuYao.TlsClient.svg)](https://www.nuget.org/packages/LuYao.TlsClient) LuYao.TlsClient

---

### ⚡ [LuYao.LightRpc](https://github.com/coderbusy/luyao-light-rpc)
![Stars](https://img.shields.io/github/stars/coderbusy/luyao-light-rpc?style=social)
[![License](https://img.shields.io/github/license/coderbusy/luyao-light-rpc)](https://github.com/coderbusy/luyao-light-rpc/blob/main/LICENSE)
[![NuGet](https://img.shields.io/nuget/v/LuYao.LightRpc.svg)](https://www.nuget.org/packages/LuYao.LightRpc/)

一个支持 AOT（Ahead-of-Time）编译的轻量级 RPC 框架。

**主要功能：**
- 支持 AOT 编译
- 源代码生成器，零反射开销
- 多框架支持
- 灵活的数据转换
- 适用于微服务和无服务器架构

**支持框架：** .NET Framework 4.5+, .NET Standard 2.0/2.1, .NET 6/7/8

**NuGet 包：**
- [![NuGet](https://img.shields.io/nuget/v/LuYao.LightRpc.svg)](https://www.nuget.org/packages/LuYao.LightRpc/) LuYao.LightRpc
- [![NuGet](https://img.shields.io/nuget/v/LuYao.LightRpc.Newtonsoft.svg)](https://www.nuget.org/packages/LuYao.LightRpc.Newtonsoft/) LuYao.LightRpc.Newtonsoft
- [![NuGet](https://img.shields.io/nuget/v/LuYao.LightRpc.SourceGenerators.svg)](https://www.nuget.org/packages/LuYao.LightRpc.SourceGenerators/) LuYao.LightRpc.SourceGenerators

---

### 📦 [LuYao.ResourcePacker](https://github.com/coderbusy/luyao-resource-packer)
![Stars](https://img.shields.io/github/stars/coderbusy/luyao-resource-packer?style=social)
[![License](https://img.shields.io/github/license/coderbusy/luyao-resource-packer)](https://github.com/coderbusy/luyao-resource-packer/blob/main/LICENSE)
[![NuGet](https://img.shields.io/nuget/v/LuYao.ResourcePacker.svg)](https://www.nuget.org/packages/LuYao.ResourcePacker/)

一个用于在构建时和运行时打包和访问资源文件的 .NET 库。

**主要功能：**
- 构建时将多个资源文件打包为单个 .dat 文件
- 智能分层压缩 (GZip)
- MSBuild 集成
- C# 源代码生成器，提供强类型资源访问 (Android 风格)
- 异步支持

**NuGet 包：**
- [![NuGet](https://img.shields.io/nuget/v/LuYao.ResourcePacker.svg)](https://www.nuget.org/packages/LuYao.ResourcePacker/) LuYao.ResourcePacker
- [![NuGet](https://img.shields.io/nuget/v/LuYao.ResourcePacker.MSBuild.svg)](https://www.nuget.org/packages/LuYao.ResourcePacker.MSBuild/) LuYao.ResourcePacker.MSBuild

---

## 📊 项目统计

| 项目 | Stars | Forks | 开源协议 | 主要语言 |
|------|-------|-------|---------|---------|
| [luyao-avalonia](https://github.com/coderbusy/luyao-avalonia) | 23 ⭐ | 1 | MIT | C# |
| [luyao-dotnet](https://github.com/coderbusy/luyao-dotnet) | 22 ⭐ | 1 | MIT | C# |
| [luyao-tls-client](https://github.com/coderbusy/luyao-tls-client) | 13 ⭐ | 3 | MIT | C# |
| [luyao-light-rpc](https://github.com/coderbusy/luyao-light-rpc) | 12 ⭐ | 0 | MIT | C# |
| [luyao-resource-packer](https://github.com/coderbusy/luyao-resource-packer) | 12 ⭐ | 0 | MIT | C# |

## 🎯 我们的愿景

我们致力于：
- 📚 构建高质量的开源工具库
- 🚀 提高 .NET 开发者的生产力
- 🌍 推动 .NET 生态系统的发展
- 🤝 促进开源社区的交流与合作

## 🤝 如何贡献

我们欢迎各种形式的贡献！

- 🐛 提交 Bug 报告
- 💡 提出新功能建议
- 🔧 提交 Pull Request
- 📖 改进文档
- ⭐ 为项目点 Star

## 📞 联系我们

- 🌐 网站: [https://www.coderbusy.com/](https://www.coderbusy.com/)
- 💬 GitHub Discussions: 在各个项目的 Discussions 中讨论
- 🐞 Issues: 在相应项目中提交问题

## 📄 许可证

我们的所有项目均采用 [MIT 许可证](https://opensource.org/licenses/MIT)，可以自由使用、修改和分发。

---

<div align="center">

**感谢您对码农很忙的支持！**

如果觉得我们的项目有帮助，请给我们一个 ⭐ Star！

</div>
