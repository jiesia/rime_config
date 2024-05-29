```sh
// 安装 Rime
$ git clone --depth=1 https://github.com/rime/plum
$ cd plum

# 安装 雾凇拼音
$ bash rime-install iDvel/rime-ice:others/recipes/full

# 安装 鼠须管 Squirrel，安装之后需要登出系统重新登入才能添加输入法
$ brew install --cask squirrel

$ cp default.custom.yaml ~/Library/Rime/default.custom.yaml
$ cp squirrel.custom.yaml ~/Library/Rime/squirrel.custom.yaml
```