# UE5 gRPC 1.62.1 插件

## 简介

本仓库提供了一个即用型的UE5 gRPC 1.62.1插件资源文件，适用于Windows平台。该插件无需额外配置，下载后即可直接使用。

## 功能特点

1. **下载即用**：无需复杂的配置步骤，下载后即可直接在UE5项目中使用。
2. **平台支持**：目前仅支持Windows平台。
3. **示例测试**：采用gRPC自带的示例测试，包括`helloworld.proto`、`helloworld.grpc.pb.cc`、`helloworld.grpc.pb.h`、`helloworld.pb.cc`和`helloworld.pb.h`等文件。`greeter_server.cc`可以封装到UE的内部组织中，例如将其逻辑写在`FRunnable`的子类里，并通过`BlueprintFunctionLibrary`暴露给蓝图调用。
4. **模式支持**：支持至少包括`DebugGame`、`DebugGame Editor`、`Development`、`Development Editor`、`Shipping`等模式。

## 版本信息

- **gRPC版本**：1.62.1
- **UE5版本**：支持UE5

## 使用说明

1. 下载本仓库提供的资源文件。
2. 将资源文件导入到你的UE5项目中。
3. 根据需要，将`greeter_server.cc`封装到UE的内部组织中，并通过`BlueprintFunctionLibrary`暴露给蓝图调用。
4. 在不同的模式下测试插件的功能，确保其在各种模式下都能正常工作。

## 注意事项

- 本插件目前仅支持Windows平台，其他平台暂不支持。
- 使用过程中如遇到问题，请参考gRPC官方文档或联系开发者获取帮助。

## 贡献与反馈

如果你在使用过程中遇到任何问题或有改进建议，欢迎提交Issue或Pull Request。我们期待你的反馈和贡献！

## 下载链接
[UE5gRPC1.62.1插件](https://pan.quark.cn/s/d2362822052d) 

(备用: [备用下载](https://pan.baidu.com/s/1dCOhPf-IGO57SPhxPT93sQ?pwd=1234))
