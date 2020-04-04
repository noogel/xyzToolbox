# xyzToolbox

打包命令

```
环境安装
npm install

# Linux打包成AppImage文件
# 在Linux环境上执行
node_modules/.bin/electron-builder -l AppImage

# Windows打包成exe安装文件
# 在Windows环境下执行
node_modules/.bin/electron-builder -w nsis
# 如果在非Windows上打包win程序，也可以借助docker 如下
# docker run --rm -it -v ${PWD}:/project electronuserland/builder:wine sh -c "node_modules/.bin/electron-builder -w nsis"

# Mac打包成dmg文件
# 在Mac环境下执行
node_modules/.bin/electron-builder -m dmg
```