# MoreLogin Launcher

## 📢 我的推特
🔗 [@0x零](https://twitter.com/0xlin168) 求个关注！如果有任何使用问题，可以通过推特联系我。

---

## 🚀 功能介绍
- **批量启动** 指定范围内的环境
- **批量关闭** 指定范围内的环境
- **随机分组** 指定范围内的环境（适用于多开任务）
- **复制分组结果** 方便管理和记录

---

## ⚙️ 设置方法
**MoreLogin Launcher** 提供 **在线版** 和 **离线版** 两种使用方式：

### **在线版**
直接访问：[MoreLogin Launcher 在线版](https://ludekuai.cc/tools/morelogin_launcher/)

### **离线版**
下载 Github 上的 `index.html` 文件并保存到本地。

### **Chrome 配置步骤**
1. 由于 MoreLogin 接口 **不允许跨域**，无论使用在线版还是离线版，都不能直接在浏览器中打开网页，需要进行以下设置：
2. **复制 Chrome 快捷方式** 并重命名为 **MoreLogin 启动器**。
3. 右键 -> **属性** -> **目标**，将文本框内容替换为：
   ```sh
   "C:\Program Files\Google\Chrome\Application\chrome.exe" --disable-web-security --user-data-dir="C:\MoreLoginLauncher"
   ```
4. **双击快捷方式启动 Chrome**，然后打开 `chrome://settings/onStartup`。
5. 找到 **“打开特定网页或一组网页”** 选项，并将 **在线版或离线版的地址** 设置为起始页面。

至此，MoreLogin 启动器的基本设置完成，建议 **仅用这个 Chrome 快捷方式** 来运行 MoreLogin Launcher。

---

## 📌 使用指南

在使用 **MoreLogin 启动器** 之前，需要 **填写 API ID、API Key 和端对端密钥（可选）**。

- **API ID & API Key**：在 MoreLogin 启动器界面右上角的 **API 弹窗** 中查看。
- **端对端密钥**（仅在开启端对端加密时需要填写）：
  - 进入 **头像 -> 设置中心 -> 全局设置 -> 环境端对端加密**，查看密钥。
- **使用期间需要保持 MoreLogin 软件运行**，否则无法进行操作。

### **1️⃣ 随机分组**
- 输入 **环境序号** 和 **多开数量**，然后进行随机分组。
- 这样可以让每次任务的环境 **随机打乱**，有效防止 **女巫检测**。
- 进行多个任务时，可以把每个任务都随机分组， **复制分组结果** 到 Excel，这样确保任务执行时间和顺序随机。

**支持的环境格式：**
- **区间格式**：如 `1-20`
- **指定格式**：如 `1,3,5`
- **混合格式**：如 `1-10,13,15,20`

### **2️⃣ 批量启动/关闭指定环境**
- MoreLogin 原生软件 **只能单个启动或全选 10/20 个环境**，难以快速批量打开指定环境。
- 本启动器 **支持自定义范围批量启动/关闭**。

**支持的环境格式：**
- **区间格式**：如 `1-20`
- **指定格式**：如 `1,3,5`
- **混合格式**：如 `1-10,13,15,20`

---

## 🔒 安全性说明
撸毛最重要的是什么？
👉 **是安全，安全，还是 TM 的安全！**

- 所以本启动器 **未使用 Python**，而是基于 **JavaScript 前端脚本** 开发。
- **所有请求都可以在浏览器控制台查看**，无任何隐藏操作。
- **无需安装 Python 环境**，**小白也能放心使用**。

### **MD5 加密**
- **MD5 算法** 采用了 **JavaScript-MD5 DEMO** 中的js链接。
- 🔗 **MD5.js 线上链接**：[JavaScript-MD5](https://blueimp.github.io/JavaScript-MD5/js/md5.js)
- 📌 **Github 开源地址**：[blueimp/JavaScript-MD5](https://github.com/blueimp/JavaScript-MD5)

---

## ❤️ 支持与反馈
如果本工具对你有帮助，欢迎在 GitHub 点 **Star** 支持！
📢 有任何问题或建议，欢迎在 **推特 [@0xlin888](https://twitter.com/0xlin888)** 联系我！

