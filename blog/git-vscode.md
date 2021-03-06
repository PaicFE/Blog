

## 提交信息

`git commit`提交信息的规范，建议在提交信息头部加上这几个类型。

- 增加功能
- 更新功能
- 删除功能
- 优化代码
- 合并代码
- 修复bug

## ITREM + OH MY ZSH的相关操作

#### 安装

**via curl**

```bash
sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
```

**via wget**

```bash
sh -c "$(wget https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh -O -)"
```

#### 环境变量的配置

```bash
vim ~/.zshrc
```

```bash
alias code='/Applications/Visual\ Studio\ Code.app/Contents/Resources/app/bin/code'
alias subl='/Applications/Sublime\ Text.app/Contents/SharedSupport/bin/subl'
alias ngrok='~/software/ngrok'
```

## vscode关于eslint配置

```javascript
"eslint.validate": [
    "javascript",
    "javascriptreact",
    "html",
    "vue"
],
"eslint.options": {
    "plugins": ["html"]
},
"git.confirmSync": false
```

参考[【译】让人倾倒的 11 个 npm trick](https://segmentfault.com/a/1190000006804410)

