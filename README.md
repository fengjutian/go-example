# Go示例项目集合

这是一个包含多个Go语言示例项目的仓库，旨在展示Go语言的各种功能和最佳实践。每个子目录都是一个独立的示例项目，可以单独运行和学习。

## 目录结构

```
├── AsciiJSON/           # Gin框架的AsciiJSON功能示例
│   ├── go.mod
│   ├── go.sum
│   └── main.go
├── bind_form_data_custom_structor/  # 自定义结构体绑定表单数据示例
│   ├── go.mod
│   ├── go.sum
│   └── main.go
└── README.md            # 项目说明文档
```

## 示例项目说明

### 1. AsciiJSON

这个示例演示了Gin Web框架中的AsciiJSON功能，用于将非ASCII字符转换为Unicode转义序列输出。

**主要功能**：
- 创建一个简单的Web服务器
- 定义API端点返回JSON数据
- 使用AsciiJSON方法处理包含中文和HTML特殊字符的数据
- 自动将非ASCII字符转换为Unicode转义序列

**使用方法**：
```bash
cd AsciiJSON
go run main.go
```
然后在浏览器中访问 `http://localhost:8080/someJSON` 查看结果。

### 2. bind_form_data_custom_structor

这个示例演示了如何在Gin框架中将表单数据绑定到自定义结构体。

**使用方法**：
```bash
cd bind_form_data_custom_structor
go run main.go
```

## 环境要求

- Go 1.23+ (推荐最新稳定版本)
- 依赖管理使用Go Modules

## 安装依赖

进入各个示例目录后，可以使用以下命令安装依赖：

```bash
go mod tidy
```

## 运行示例

每个示例项目都可以独立运行：

```bash
cd 示例目录
go run main.go
```

## 贡献

欢迎提交更多的Go语言示例或改进现有示例！

## 许可证

本项目采用MIT许可证。