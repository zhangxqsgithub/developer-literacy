# brew是Mac的一款包管理工具

[官网](https://brew.sh/)
> The Missing Package Manager for macOS (or Linux)

## 安装brew
```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

## 常用命令
```bash
# 安装包
brew install wget
# 搜索包
brew search wget
# 查看包信息
brew info wget
# 清理brew缓存
brew cleanup
# 列出brew已安装的包
brew list
# brew更新仓库中所有包的版本信息
brew update
# 升级包
brew upgrade wget
# 卸载包
brew uninstall wget
# 检查brew是否健康
brew doctor
# 使用brew安装APP（安装的app会在/Applications中）
brew install --cask firefox

# brew services管理
# 列出所有的service
brew services list
# 启动服务
brew services start nginx
# 停止服务
brew services stop nginx
# 重启服务
brew services restart nginx
# 查看服务运行信息
brew services info nginx 
```