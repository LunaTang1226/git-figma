# 9.29 Git & GitHub 学习笔记

## 1. 安装与配置

1. **VS Code 里设置 git 用户名、邮箱**
   在终端输入以下命令：
   ```bash
   git config --global user.name "你的名字"
   git config --global user.email "你的邮箱@example.com"
   ```

2. **创建文件夹，创建 VSCode 文件**

3. **登录 GitHub**

4. **GitHub 设置代理**
   端口编号在 Watt Toolkit -> 加速设置 -> 代理设置 -> 26561
   ```bash
   git config --global http.proxy http://127.0.0.1:26561
   git config --global https.proxy http://127.0.0.1:26561
   ```

5. **与 VSCode 绑定**

---

## 2. 本地上传
（略）

## 3. 远程上传

1. 新建仓库时**不要 add README**
2. 可以粘贴，但最好是在 VSCode 里上传

### 💡 巨坑提醒：
**不要依赖 VSCode 的图形按钮，要用终端操作！！！**

---

### 情况一：如果是第一次新建文件上传
```bash
git init
git add .
git commit -m "first commit"
git branch -M main
git remote add origin 你的仓库地址   # (在 GitHub 网页上能找到)
git push -u origin main
```

### 情况二：如果是上传到之前已经传过的仓库（比如只是修改了一下）
```bash
git add .
git commit -m "这里写你这次改了什么，比如：更新了首页样式"
git push origin main
```

### 情况三：如果是上传到新仓库
```bash
git init
git add .
git commit -m "XXX"
git branch -M main
git remote add backup 另一个仓库地址   # (在 GitHub 网页上能找到)
git push -u backup main
```

> **注意：** `backup` 在这里只是习惯，事实上第二个仓库可以随便取（习惯叫 `backup` 或者 `repo2`）。**但是第一个必须叫 `origin` ！！！**
