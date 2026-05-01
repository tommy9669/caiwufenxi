# TikTok Shop API Docs

本文件夹包含 TikTok Shop API 权限申请所需的最小可用文档，包括：

1. **Terms of Service (`tos.html`)**
2. **Privacy Policy (`privacy.html`)**

这些文档可直接上传到 GitHub Pages 或使用 ngrok 暴露公网 URL，用于 TikTok Shop API 应用权限申请。

---

## 文件说明

| 文件 | 功能 |
|------|------|
| `tos.html` | 服务条款页面（Terms of Service） |
| `privacy.html` | 隐私政策页面（Privacy Policy） |
| `README.md` | 本说明文件 |

---

## 使用方法

### 1. GitHub Pages

1. 创建一个新的 GitHub 仓库，例如 `tiktok_docs`  
2. 上传本文件夹中的文件到仓库  
3. 打开 **Settings → Pages → Source**，选择 `main` 分支并保存  
4. 页面 URL 示例：
   - `https://github.com/tommy9669/caiwufenxi/blob/main/tos.html`
   - `https://github.com/tommy9669/caiwufenxi/blob/main/privacy.html`  
5. 将 URL 填入 TikTok Shop API 表单的 **Terms of Service URL** 和 **Privacy Policy URL**

---

### 2. ngrok 暴露本地网页

1. 在本地启动一个简单 HTTP 服务：
   ```bash
   python -m http.server 3000
