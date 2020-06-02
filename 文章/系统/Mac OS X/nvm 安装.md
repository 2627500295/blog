## 安装

```bash
brew install nvm
```

## 设置

```bash
cat << EOF >> ~/.zshrc
export NVM_DIR="$(brew --prefix nvm)"
export NVM_NODEJS_ORG_MIRROR="https://npm.taobao.org/mirrors/node"
[ -s "/usr/local/opt/nvm/nvm.sh" ] && . "/usr/local/opt/nvm/nvm.sh"
[ -s "/usr/local/opt/nvm/etc/bash_completion" ] && . "/usr/local/opt/nvm/etc/bash_completion"
EOF
```

