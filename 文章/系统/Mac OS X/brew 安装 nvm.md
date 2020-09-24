## 安装

```bash
brew install nvm
```

## 删除软链接

删除 `$(brew --prefix nvm)` 链接

```bash
/usr/local/opt/nvm
```

## 设置

```bash
cat << EOF >> ~/.zshrc
export NVM_NODEJS_ORG_MIRROR="https://npm.taobao.org/mirrors/node"
export NVM_DIR="$(brew --prefix nvm)"
[ -s "$(brew --prefix nvm)/nvm.sh" ] && . "$(brew --prefix nvm)/nvm.sh"
[ -s "$(brew --prefix nvm)/etc/bash_completion" ] && . "$(brew --prefix nvm)/etc/bash_completion"
EOF
```

