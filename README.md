# 添加远程仓库地址（两种协议任选其一）
git remote add origin https://github.com/Eliaub/my-project.git  # HTTPS

# 验证远程仓库配置
git remote -v

# 首次推送代码（以 main 分支为例）
git branch -M main    # 重命名默认分支
git push -u origin main# my-project
