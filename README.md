# 教师信息数据集（示例）

基于你提供的字段结构，整理了一份可直接用于前端/后端演示的示例数据集，包含 10 条记录：

- `id`：整数主键  
- `name`：姓名  
- `image`：头像地址（占位图片链接，可替换为你自己的 OSS/CDN）  
- `gender`：性别（1=男，0=女，可按需要调整为字符串）  
- `job`：职位/科目  
- `entrydate`：入职日期（YYYY-MM-DD）  
- `updatetime`：最近更新时间（YYYY-MM-DD HH:mm:ss）  

## 文件说明
- `data.json`：主数据（UTF-8，缩进 2）
- `data.csv`：同样的数据，便于低代码/表格导入
- `LICENSE`：MIT 协议，方便开源复用

## 如何在 GitHub 上创建仓库并推送
```bash
# 1）在本地准备仓库目录
git init teacher-dataset
cd teacher-dataset

# 2）把上述三个文件放进来（data.json、data.csv、README.md、LICENSE）

# 3）创建新仓库（到 GitHub 网页 new repository），名字可用 teacher-dataset
# 假设你的远程是：git@github.com:YOUR_USER/teacher-dataset.git

git add .
git commit -m "feat: 初始数据集"
git branch -M main
git remote add origin git@github.com:YOUR_USER/teacher-dataset.git
git push -u origin main
```

## 许可证
本项目使用 MIT 许可证。你可以自由地复制、修改和发布。
