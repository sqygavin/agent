# GitHub Pages 部署说明

## 文件说明
- `index.html`：导航首页
- `agent-nature-simple.html`：Agent 本质深度剖析
- `ai-terms-essence.html`：AI 名词本质洞察

## 最快发布方式
1. 新建一个 GitHub 仓库
2. 把本目录下 3 个文件上传到仓库根目录
3. 打开仓库 `Settings` → `Pages`
4. `Build and deployment` 选择：`Deploy from a branch`
5. Branch 选择：`main`，Folder 选择：`/ (root)`
6. 保存后等待 1–3 分钟
7. 访问：`https://你的用户名.github.io/你的仓库名/`

## 命令行方式
```bash
git init
git add .
git commit -m "feat: publish html pages"
git branch -M main
git remote add origin https://github.com/你的用户名/你的仓库名.git
git push -u origin main
```
