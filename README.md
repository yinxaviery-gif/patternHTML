# SMT8 Pattern Editor

一个基于浏览器的 SMT8 Pattern 编辑、校验与格式转换工具，面向爱德万（Advantest）93K 测试程序开发和 ATE 工程使用。无需安装后端服务，直接打开 `smt8-pattern.html` 即可运行。

## 功能

- 打开并编辑 SMT8 `.pat` 文件中的 `Program.sprg`、`Vectors.vec`、`Comments.cmt` 等文本成员
- 校验 pin 数量、向量列数以及 `genVec` 行数
- 在整合视图中查看 HEADER、pin、vector、指令和注释
- `.pat` 与整合 TXT 之间相互转换
- 新建 Pattern，支持 SPI 四线和 8 路数字 IO 模板
- 中英文界面切换
- 支持浏览器直接打开，适合离线使用

## 使用方法

1. 下载 `smt8-pattern.html`。
2. 使用 Chrome 或 Edge 打开。
3. 点击“打开 .pat”编辑现有 Pattern，或点击“新建 Pattern”创建文件。
4. 完成修改后校验并保存 `.pat`。

也可以使用“导出整合 TXT”和“TXT 转 .pat”功能，在文本格式和 SMT8 Pattern 格式之间转换。

## 适用关键词

爱德万 93K、Advantest 93K、93K ATE、SMT7、SMT8、SMT7 Pattern、SMT8 Pattern、ATE 程序开发、ATE 测试程序、测试程序编辑器、半导体测试、芯片测试、量产测试、CP 测试、FT 测试、ATE 工程、Pattern 编辑、Vector 编辑、`Program.sprg`、`Vectors.vec`、`Comments.cmt`、SPI Pattern。

## 说明

本仓库只发布浏览器端 HTML 源码，不包含任何具体产品、芯片、客户或测试项目的 `.pat` 样例数据。请在使用前确认生成的 Pattern 符合你的测试平台版本、站点配置和内部流程要求。

## 联系方式

技术交流、ATE 程序开发、爱德万 93K / SMT7 / SMT8 Pattern 支持：

**yin.xaviery@gmail.com**

## License

本项目采用 [MIT License](LICENSE) 开源。

---

# SMT8 Pattern Editor

Browser-based editor, validator, and converter for SMT8 test patterns, designed for Advantest 93K ATE program development. It runs locally in Chrome or Edge without a backend service.

Topics: Advantest 93K, SMT7, SMT8, ATE program development, semiconductor test, IC test, pattern editing, vector editing, SPI pattern, `Program.sprg`, `Vectors.vec`, and `Comments.cmt`.

Contact: **yin.xaviery@gmail.com**
