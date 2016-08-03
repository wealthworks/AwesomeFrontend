# npm

## ~/.npmrc

```
$ cat ~/.npmrc
save-exact=true
registry=https://registry.npm.taobao.org
```

参考：https://docs.npmjs.com/misc/config

## npm bin

npm 安装的 binary 会被放到 *node_modules/.bin* 下。如 `npm install webpack`，会把 `webpack` 装到 *node_modules/.bin/webpack*。

package.json 中的 scripts 可以找到 binary 的位置。

`npm bin` 可以打出 *<fullpath>/node_modules/.bin*，因此可以

```
alias npmbin='PATH=$(npm bin):$PATH'
npmbin
webpack
```
