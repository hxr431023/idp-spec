# IDP (Interface Data Packet) 格式规范

IDP（Interface Data Packet）接口数据包格式规范。XML 头 + JSON 数据的通信帧格式。

两层规范：第一层通用帧格式（XML 头 + 分隔符 + JSON 载荷）；第二层各用途内容规范（渲染指令、命令响应等）。

## 许可证

本规范文档以 Mozilla Public License 2.0（MPL-2.0）发布。
使用本规范时：若对规范内容作出修改，需公布修改后的规范文件；上层使用方的其他内容无需公开。
