# Air Rose: Botanist

一个基于运动感应的交互式花卉识别应用。

## 部署到 GitHub Pages

### 方式一：项目仓库（推荐）

1. 在 GitHub 上创建一个新仓库（例如：`airRose`）
2. 将本地代码推送到 GitHub：
   ```bash
   git remote add origin https://github.com/你的用户名/airRose.git
   git push -u origin main
   ```
3. 在仓库设置中启用 GitHub Pages：
   - 进入 Settings → Pages
   - Source 选择 `main` 分支
   - 点击 Save
4. 访问地址：`https://你的用户名.github.io/airRose/`

### 方式二：用户主页仓库

1. 在 GitHub 上创建一个名为 `你的用户名.github.io` 的仓库
2. 将本地代码推送到 GitHub：
   ```bash
   git remote add origin https://github.com/你的用户名/你的用户名.github.io.git
   git push -u origin main
   ```
3. GitHub Pages 会自动启用
4. 访问地址：`https://你的用户名.github.io/`

## 使用说明

在移动设备上打开页面，通过晃动设备来"收集 DNA"，然后保持设备静止以生成花卉。

