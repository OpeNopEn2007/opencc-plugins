# OpeNopEn Claude Code Plugins

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Claude Code](https://img.shields.io/badge/Claude_Code-Marketplace-blue.svg)](https://claude.ai/code)

> OpeNopEn2007 的 Claude Code 插件集合

## 可用插件

| 插件 | 描述 | 版本 |
|------|------|------|
| **arkts-patterns** | ArkTS 开发模式与 HarmonyOS NEXT 最佳实践 | 2.2.0 |

---

## 安装方式

### 1. 添加市场

```bash
/plugin marketplace add OpeNopEn2007/opencc-plugins
```

### 2. 安装插件

```bash
# 安装 ArkTS 开发辅助插件
/plugin install arkts-patterns@OpeNopEn
```

---

## 插件详情

### arkts-patterns

HarmonyOS NEXT (API 12+) ArkTS 开发模式与最佳实践。

**功能特性**：
- 状态管理模式 (@State, @Prop, @Link, @Observed/@ObjectLink)
- 组件生命周期 (aboutToAppear, aboutToDisappear, UIAbility)
- 并发模式 (TaskPool, Worker)
- 导航模式 (NavPathStack + NavDestination)
- HTTP 客户端模式
- 数据持久化 (Preferences, RDB)
- 动画与手势
- EmptyAbility 官方模板

**仓库**: [OpeNopEn2007/arkts-patterns](https://github.com/OpeNopEn2007/arkts-patterns)

---

## 更新市场

```bash
/plugin marketplace update OpeNopEn
```

---

## License

MIT License - see [LICENSE](LICENSE) for details.