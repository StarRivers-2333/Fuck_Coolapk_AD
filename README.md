# 酷安广告移除模块使用指南  

---

## 📦 模块功能  
本 Magisk 模块可彻底移除酷安 (CoolApk) 应用内的所有广告，需配合 **HyperCeiler** 或 **CorePatch** 的核心破解功能使用。

---

## ⚙️ 前置条件  
### 1. 安装 LSPosed 框架  
- **必须使用最新版 LSPosed** (Zygisk 版本)  
- [官方下载](https://github.com/LSPosed/LSPosed/releases)  

### 2. 安装核心破解模块 (二选一)  
| 模块 | 支持系统 | 下载地址 |  
|------|----------|----------|  
| **HyperCeiler** | Android 9-15 | [GitHub Release](https://github.com/ReChronoRain/HyperCeiler/releases) |  
| **CorePatch(核心破解)** | Android 9-15 | [GitHub Release](https://github.com/LSPosed/CorePatch/releases) |  

---

## 🔧 核心破解配置指南  
### ▶️ HyperCeiler 配置  
1. 在 LSPosed 中启用 **HyperCeiler** 并勾选 **系统框架**  
2. 打开 HyperCeiler → `系统框架` → `包管理服务`  
3. **必须开启以下选项**：  
   ```markdown
   ✅ 允许降级安装应用  
   ✅ 禁用软件包管理器签名验证  
   ✅ 禁用 APK 签名验证  
   ✅ 禁用低 API 校验  
   ✅ 禁用持久性检查  
   ✅ 禁用安装包验证代理  
   ✅ 禁用隔离应用检查  
   ✅ 允许安装系统应用  
   ```
   > ⚠️ 必须**关闭**"安装时始终使用已装APP的签名"（危险选项）

### ▶️ CorePatch(核心破解) 配置  
1. 在 LSPosed 中启用 **CorePatch** 并勾选 **Android 系统**  
2. 打开 CorePatch 进行配置：  
   ```markdown
   ✅ 允许降级安装应用  
   ✅ 禁用软件包管理器签名验证  
   ✅ 禁用 APK 签名验证  
   ✅ 绕过黑名单  
   ✅ 绕过共享用户签名验证  
   ✅ 禁用安装包验证代理  
   ```
   > ⚠️ 必须**关闭**"安装时始终使用已装APP的签名"（危险选项）

---

## 📥 安装模块  
1. 在 Magisk 中刷入模块 `Fuck_Coolapk_AD.zip`  
2. **强制重启两次**：  
   - 第一次重启：应用核心破解配置  
   - 第二次重启：激活广告移除模块  
3. 打开酷安 → 验证广告已消失  

---

## ❓ 常见问题  
**Q：模块刷入后广告仍在？**  
A：请检查：  
- 是否严格按上述要求配置所有选项  
- LSPosed 中已启用 HyperCeiler/CorePatch  
- 模块在 Magisk 中显示为已启用  
- 尝试清除酷安应用数据  

**Q：安装失败怎么办？**  
A：确保：  
1. 已禁用"安装时始终使用已装APP的签名"  
2. 已开启所有必需选项  
3. 使用最新版 LSPosed  

---

## 🌐 技术支持  
- 模块问题反馈：[Issues](https://github.com/yourname/coolapk-adblock/issues)  
- HyperCeiler 支持：[Telegram 群组]（https://t.me/HyperCeiler）  
- CorePatch 支持：[Discord 社区](https://discord.gg/lsposed)  

---

## 📦 模块功能
这个 Magisk 模块完全删除了 CoolApk 应用程序中的所有广告，需要 **HyperCeiler** 或 **CorePatch** 核心补丁功能。

---

## ⚙️ 先决条件
### 1.安装 LSPosed 框架
-**必须使用最新的 LSPosed**（Zygisk 版本） 
-[官方下载]（https://github.com/LSPosed/LSPosed/releases）   

### 2.安装核心补丁模块（选择一个） 
|模块 |支持的作系统 |下载 |  
|--------|--------------|----------|  
|**HyperCeiler** |安卓 9-15 |[GitHub 版本]（https://github.com/ReChronoRain/HyperCeiler/releases） |  
|**核心补丁** |安卓 9-15 |[GitHub 版本]（https://github.com/LSPosed/CorePatch/releases） | 

---

## 🔧 核心补丁配置
### ▶️ HyperCeiler 设置
1. 在 LSPosed 中启用 **HyperCeiler** 并检查 **系统框架**  
2. 打开 HyperCeiler →转到“系统框架”→“包管理服务”  
3.**基本选项**：   
   ''' 降价
   ✅ 允许降级安装  
   ✅ 禁用 Package Manager 签名验证  
   ✅ 禁用 APK 签名验证  
   ✅ 禁用低 API 检查  
   ✅ 禁用持久检查  
   ✅ 禁用包验证代理  
   ✅ 禁用隔离的应用程序检查  
   ✅ 允许系统应用程序安装  
   ```
   ⚠️ > **禁用** “始终使用已安装的应用程序签名” （危险选项）

### ▶️ CorePatch 设置
1. 在 LSPosed 中启用 **CorePatch** 并检查 **Android 系统**  
2. 配置 CorePatch：
   ''' 降价
   ✅ 允许降级安装  
   ✅ 禁用 Package Manager 签名验证  
   ✅ 禁用 APK 签名验证  
   ✅ 绕过黑名单  
   ✅ 绕过共享用户签名验证  
   ✅ 禁用包验证代理  
   ```
   ⚠️ > **禁用** “始终使用已安装的应用程序签名” （危险选项）

---

## 📥 安装
1. Magisk 中的 Flash 模块“Fuck_Coolapk_AD.zip”
2.**双重重启程序**： 
   - 首次重启：应用核心补丁设置
   - 第二次重启：激活广告移除模块
3. 打开 CoolApk →验证广告是否已删除

---

## ❓ 常见问题
**Q： 广告还会出现吗？  
A： 验证：  
- 所有必需的选项均按上述方式启用
- 在 LSPosed 中启用了 HyperCeiler/CorePatch
- 模块在 Magisk 中显示为已启用
- 尝试清除 CoolApk 应用数据

**Q： 安装失败？ **  
答：确保：  
1. “始终使用已安装的应用程序签名”已禁用
2. 所有基本选项均已启用
3. 使用最新的 LSPosed 版本

---

## 🌐 支持
- 模块问题：[GitHub Issues]（https://github.com/yourname/coolapk-adblock/issues）
- HyperCeiler 支持：[Telegram Group]（https://t.me/HyperCeiler）
- CorePatch 支持：[Discord Community]（https://discord.gg/lsposed）

''美人鱼
图表 TD
    A[安装 LSPosed] --> B{选择核心补丁模块}
B --> C[HyperCeiler]
B --> D[CorePatch]
    C --> E[在 LSPosed 中启用]
    D --> E
    E --> F[配置基本选项]
    F --> G[禁用危险选项]
G --> H[闪光灯Fuck_Coolapk_AD.zip]
H --> I[首次重启]
I --> J[第二次重启]
J --> K[无广告 CoolApk]
```
