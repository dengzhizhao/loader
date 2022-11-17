# 手写一个loader
1.安装依赖

```js
npm i
```

2.打包

```js
 node -r ts-node/register bundler_css_loader.ts
```

3.如果需要chrome调试

```js
node -r --inspect-brk ts-node/register bundler_css_loader.ts
```

### 如何使用

你可以在`project_css`文件夹里面的**style.css**随便编写样式，当然也可以新建，然后你需要在`index.js`里面引入一下即可，最后再使用命令打包一下即可

