### 层模型
1. 添加position: absolute; 的都是一个全新的层。脱离原来的位置进行定位。z-index: ;决定层的顺序
2. position: relative; 保留原来的位置进行定位
3. postion与left，right联用进行定位
4. absolute定位原则，相对于最近的有定位的父级进行定位，如果没有，就相对于文档进行定位
5. relative定位原则，相对于自己原来的位置进行定位
6. position: fixed; 一个固定定位，元素会相对于视窗来定位，这意味着即便页面滚动，它还是会停留在相同的位置。
7. 制作相对于文档的居中DIV容器
````css
div{
    width: 100px;
    height: 200px;
    position: absolute;
    left: 50%;
    top: 50%;
    margin-left: -50px;
    margin-top: -100px;
}
````
