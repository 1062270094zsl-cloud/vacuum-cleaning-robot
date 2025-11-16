# 推送资源文件到GitHub

## 📋 当前状态

✅ README中已添加图片展示代码  
✅ 图片文件存在于本地: `assets/images/` (7张)  
✅ GIF文件存在于本地: `assets/gifs/` (2个)  
✅ 视频文件存在于本地: `assets/videos/` (9个)  

⚠️ **需要将这些文件推送到GitHub仓库才能显示**

## 🚀 推送步骤

### 方法1: 如果这是本地项目目录

```bash
cd /Users/gyw/Desktop/Project/2025/cv_shili_zhang/my-portfolio/project-repos/vacuum-cleaning-robot

# 初始化git仓库（如果还没有）
git init

# 添加远程仓库
git remote add origin https://github.com/1062270094zsl-cloud/vacuum-cleaning-robot.git

# 添加所有文件
git add .

# 提交更改
git commit -m "Add project assets: images, videos, and GIFs"

# 推送到GitHub
git push -u origin main
```

### 方法2: 如果GitHub仓库已存在

```bash
# 克隆仓库
git clone https://github.com/1062270094zsl-cloud/vacuum-cleaning-robot.git
cd vacuum-cleaning-robot

# 复制assets目录
cp -r /Users/gyw/Desktop/Project/2025/cv_shili_zhang/my-portfolio/project-repos/vacuum-cleaning-robot/assets .

# 复制README（如果已更新）
cp /Users/gyw/Desktop/Project/2025/cv_shili_zhang/my-portfolio/project-repos/vacuum-cleaning-robot/README.md .

# 添加并推送
git add .
git commit -m "Add project assets: images, videos, and GIFs"
git push
```

## 📁 需要推送的文件

- `assets/images/` - 7张图片
- `assets/gifs/` - 2个GIF动画
- `assets/videos/` - 9个视频文件
- `README.md` - 已更新的README（包含图片展示代码）
- `docs/` - 文档文件（如果还没有）

## ✅ 推送后

推送完成后，GitHub上的README会自动显示：
- 7张项目图片的展示
- 2个GIF动画的展示
- 视频文件的下载链接

## 🔍 验证

推送后访问：https://github.com/1062270094zsl-cloud/vacuum-cleaning-robot

应该能看到图片在README中正确显示。

