```
  hello
```

### 2020-11-26

#### 1.隐藏滚动条

```
https://blog.csdn.net/csdn_cai_csdn/article/details/78838949
在滚动元素处添加 伪类选择器
  &-box{
    overflow-y: auto;
    -webkit-overflow-scrolling: touch;
  }
  &-box::-webkit-scrollbar{width:0;}
```

#### 2.::before伪元素

```
    @{name}-block-wrapper::before{
      display: block;
      content: '';
      position: absolute;
      left: 0;
      top: 0;
      height: calc(100% + 0.64rem);
      border-left: 0.03rem rgba(37, 72, 255, 0.35) solid;
    }
```

