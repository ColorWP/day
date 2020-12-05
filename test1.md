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


#### 3.html页面清除缓存
```
3行 http-equiv
  <meta http-equiv="Cache-Control" content="no-cache, no-store, must-revalidate" />
  <meta http-equiv="Pragma" content="no-cache" />
  <meta http-equiv="Expires" content="0" />
```


#### 4.dpr viewport


#### 5.1px 适配


#### 6.video
```

  webkit-playsinline
  playsinline
  x5-playsinline
  x5-video-player-fullscreen
  x-webkit-airplay
  x5-video-player-type="h5"
  x5-video-orientation = 'portraint'

```


#### 7.toast
```
点击复制
  1.添加一个input，给input定位到-9999，并且只读
  2.给个div显示

  <input id="xxx" type="text" value="xxxx" readonly="readonly" >
```


#### 8.ios transform
```
```

#### 9.滚动穿透
```
给body加hidden，也就是遮罩层
  document.body.style.overflow = 'hidden'

取消
  document.body.style.overflow = ''

```


#### 10.ios 100vh


#### 11.无缝滚动

