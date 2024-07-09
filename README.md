# 测评助手IDE

开源的等保测评、密评、风评三合一工具，客户端永久免费使用，可二次定制开发

![desktop1](https://cloud.miaodu.net/public/mac-1.jpeg)

![desktop3](https://cloud.miaodu.net/public/windows-1.jpeg)


![desktop2](https://cloud.miaodu.net/public/%E8%B5%84%E4%BA%A7%E6%94%B6%E9%9B%86.png)


基于Rust开发的标准的、快速的、安全的、可扩展的、网络安全业务测评系统；称作安全工程师的vscode

- 支持插件开发（用户可根据自己的业务需求定制插件实现一些特定的业务需求）
- 支持编辑锁定功能（共享编辑的项目可以锁定，防止二次修改）
- 支持自定义知识库（用户可根据自己的知识领域修改或增加知识库）
- 开放OpenAPI接口（用户可根据自己的需求接入外部系统）
- 支持过程文档制作（内置的DoScript脚本语言可以根据自己的需求编写word或excel模版）
- 支持excel格式的自由粘贴（和excel相同的表格属性，支持相互复制）
- 支持局域网共享编辑（相同域下的客户端自动识别，实现项目共享）

---

## 系统架构

本客户端底层使用Rust完成业务逻辑、UI层使用WinUI、存储层使用DuckDB。

![架构](https://cloud.miaodu.net/public/%E6%9E%B6%E6%9E%841.png)

### DoScript

[DoScript](https://github.com/987763485/DoScript)是一个Rust实现的脚本引擎，DoScript原生支持创作Word和Excel（这是一个非常简单的，支持中文描述word结构的脚本语言）

### DuckDB
[DuckDB](https://github.com/987763485/duckdb)是一个开源 OLAP 数据库，本项目对DuckDB官方进行了一个分支，增加了数据加密的功能，用于存储用户的业务数据。

### Rustls
[rustls](https://github.com/rustls/rustls) 是一个Rust实现的OpenSSL库，在本项目中提供安全的网络传输和数据加密

### 安全业务
安全业务提供测测评助手基本的业务逻辑，包含等保测评、密评、风评的业务处理，风险计算等。

---

# 获取方式





出于网络安全工具的监管要求和安全性保护措施，防止他人恶意利用，暂不提供源码下载，源代码只能通过实名登记发放，请添加开发人员微信获取

<img src="https://cloud.miaodu.net/public/weixin-user1.jpg" alt="微信" width="300">


