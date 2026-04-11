# Autodesk_rule

Autodesk 的分流规则集合，用于匹配 Autodesk 相关域名并支持代理/直连规则管理。

## 内容说明

- `Autodesk.list`：包含 Autodesk 及其相关服务域名的分流规则。
- `.gitignore`：忽略常见的临时文件和编辑器配置文件。

## 用途

该仓库适合用于：

- 代理规则管理
- Clash / Surge / Quantumult X 等分流配置参考
- Autodesk 服务域名监控与维护

## 规则示例

规则采用 `DOMAIN-SUFFIX` 和 `DOMAIN-KEYWORD` 格式，示例：

```text
DOMAIN-SUFFIX,autodesk.com
DOMAIN-KEYWORD,adsk
```

## 贡献说明

欢迎提交 issue 或 pull request，补充更多 Autodesk 相关域名并保持规则准确。
