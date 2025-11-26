# 独立开发者作品集展示页

这是一个为你准备的静态作品集网站模板。你可以用它来展示你的 App 和个人介绍。

## 📁 文件夹结构

```
ProductPresentation/
├── index.html      # 主页文件 (主要修改这里)
├── styles.css      # 样式文件
├── assets/
│   └── images/     # 存放图片 (头像、App截图)
└── README.md       # 说明文件
```

## 🛠 如何使用

### 1. 修改文字内容
打开 `index.html` 文件，找到以下内容并替换为你自己的信息：
- `[你的名字]`：替换为你的姓名或昵称。
- `App Name`：替换为你的 App 名称。
- App 描述文字：替换为真实的 App 介绍。
- 链接 `href="#"`：将 `#` 替换为你的 App Store、GitHub 或其他下载链接。
- `mailto:your.email@example.com`：替换为你的真实邮箱。

### 2. 添加图片
1. 将你的头像图片放入 `assets/images/` 文件夹，命名为 `avatar.jpg` 或 `avatar.png`。
2. 将你的 App 截图或封面图放入 `assets/images/` 文件夹，例如 `app1.png`, `app2.png` 等。
3. 修改 `index.html` 中的图片占位符：

   **头像部分：**
   ```html
   <!-- 原代码 -->
   <div class="avatar-placeholder">Avatar</div>
   
   <!-- 修改后 -->
   <img src="assets/images/avatar.jpg" alt="我的头像" class="avatar-placeholder" style="object-fit: cover;">
   ```

   **App 图片部分：**
   ```html
   <!-- 原代码 -->
   <div class="app-image-placeholder">
       <span>App Screenshot 1</span>
   </div>
   
   <!-- 修改后 -->
   <div class="app-image-placeholder">
       <img src="assets/images/app1.png" alt="App Name 1">
   </div>
   ```

## 🚀 如何部署到 GitHub Pages

1. 在 GitHub 上创建一个新的仓库 (Repository)，例如命名为 `my-portfolio`。
2. 将 `ProductPresentation` 文件夹内的所有文件上传到该仓库（或者用 git push）。
3. 进入仓库页面，点击 **Settings** (设置)。
4. 在左侧菜单找到 **Pages**。
5. 在 **Build and deployment** 下的 **Source** 选择 `Deploy from a branch`。
6. 在 **Branch** 选项中，选择 `main` (或 `master`) 分支，文件夹选择 `/ (root)`，点击 **Save**。
7. 等待几分钟，GitHub 会给出一个链接 (例如 `https://yourname.github.io/my-portfolio/`)，这就是你的个人主页了！

祝你的 App 大卖！🚀

