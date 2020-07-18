# canvas
画图
#### 兼容手机端画图

js判断是否支持触摸
```javascript
let isTouchDevice = 'ontouchstart' in document.documentElement;
 console.log(isTouchDevice);
```

使线条再转折出不出现断层和锯齿状的方法使添加lineCap属性
```javascript
        ctx.lineCap = "round";
```
