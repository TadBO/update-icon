# update-icon
自动跟新iconfont
1. clone or down icon.js
2. 更改ICON_CONFIG中的地址为项目地址
3. 如果没有使用css模块化，删除` chunk = :global {${chunk}};`
4. 添加命名`node icon.js --url=//at.alicdn.com/t/font_883239_9i0kvhrklhr.css`,每次跟新iconfont后跟新url，运行即可
