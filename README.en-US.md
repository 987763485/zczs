# Assessment Assistant IDE

An open-source three-in-one tool for MLPS (Multi-Level Protection Scheme) assessment, Cryptographic assessment, and Risk assessment. The client is permanently free to use and supports secondary custom development.

![desktop1](https://cloud.miaodu.net/public/mac-1.jpeg)

![desktop3](https://cloud.miaodu.net/public/windows-1.jpeg)

![desktop2](https://cloud.miaodu.net/public/%E8%B5%84%E4%BA%A7%E6%94%B6%E9%9B%86.png)

A standard, fast, secure, and extensible cybersecurity business assessment system developed based on Rust; described as the "VS Code for Security Engineers."

- Supports plugin development (users can customize plugins to implement specific business needs).
- Supports edit locking (shared projects can be locked to prevent unauthorized secondary modifications).
- Supports custom knowledge bases (users can modify or add to the knowledge base according to their domain of expertise).
- Provides open OpenAPI interfaces (users can integrate external systems based on their needs).
- Supports process documentation generation (the built-in DoScript scripting language allows users to write Word or Excel templates according to their needs).
- Supports free pasting of Excel formats (shares the same table attributes as Excel, supporting mutual copying).
- Supports LAN shared editing (clients in the same domain are automatically recognized to enable project sharing).

---

## System Architecture

The client's underlying business logic is implemented in Rust, the UI layer uses WinUI, and the storage layer uses DuckDB.

![架构](https://cloud.miaodu.net/public/%E6%9E%B6%E6%9E%841.png)

### DoScript

[DoScript](https://github.com/987763485/DoScript) is a script engine implemented in Rust. DoScript natively supports the creation of Word and Excel documents (it is a very simple scripting language that supports describing Word structures using Chinese descriptions).

### DuckDB

[DuckDB](https://github.com/987763485/duckdb) is an open-source OLAP database. This project uses a fork of the official DuckDB, adding data encryption functionality to store user business data.

### Rustls

[rustls](https://github.com/rustls/rustls) is an OpenSSL library implemented in Rust, providing secure network transmission and data encryption in this project.

### Security Business

The Security Business module provides the basic logic for the Assessment Assistant, including business processing and risk calculation for MLPS, Cryptographic, and Risk assessments.

---

# How to Obtain

Due to regulatory requirements for cybersecurity tools and security protection measures to prevent malicious exploitation, source code downloads are not currently provided. Source code is distributed only via real-name registration.

### Please make sure to `Star` the project before adding via WeChat to obtain it.

<img src="https://cloud.miaodu.net/public/weixin-user1.jpg" alt="微信" width="300">

If the QR code does not display, please add the WeChat ID: `ceping2024`

## This project focuses on security research and community building, and we commit that this client will remain free to use forever.
