移动端开发

## 今日目标

1. 学习flex布局
2. 一行中三个盒子的布局

## 如何简单的布置三个盒子
```html
<p>
    <span>1</span>
    <span>2</span>
    <span>3</span>
</p>
```

```css
p span {
    /*这里的意思是3个span各占一份*/
    flex: 1;
    background-color: blueviolet;
}
p span:nth-child(2) {
    flex: 2;
    background-color:chartreuse;
}
```

## 难点

* align-content
* align-items