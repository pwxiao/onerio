# onerio

Oneiro - 你的AI梦境日记伴侣

## 🚀 GitHub Pages 部署

这个仓库包含了Oneiro应用的隐私政策和支持页面，用于App Store提交。

### 部署步骤

1. **推送代码到GitHub**
   ```bash
   git add .
   git commit -m "Add privacy policy website for App Store"
   git push origin main
   ```

2. **启用GitHub Pages**
   - 进入仓库设置 (Settings)
   - 滚动到 "Pages" 部分
   - Source 选择 "Deploy from a branch"
   - Branch 选择 "main" 分支和 "/ (root)" 文件夹

3. **访问地址**
   - 部署完成后，访问地址为：`https://[你的用户名].github.io/onerio/`
   - 隐私政策页面：`https://[你的用户名].github.io/onerio/privacy-policy.html`

### App Store 提交

在App Store Connect中填写以下信息：

- **隐私政策URL**: `https://[你的用户名].github.io/onerio/privacy-policy.html`
- **支持URL**: `https://[你的用户名].github.io/onerio/` 或 `https://github.com/[你的用户名]/onerio/issues`

### 文件说明

- `index.html` - 主页，介绍Oneiro应用
- `privacy-policy.html` - 隐私政策页面
- `styles.css` - 样式文件
- `README.md` - 项目说明

### 自定义

1. 将 `[你的用户名]` 替换为你的实际GitHub用户名
2. 根据需要修改隐私政策内容
3. 更新联系邮箱等信息
