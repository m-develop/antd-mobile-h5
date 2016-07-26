## install


```
npm install antd-mobile-h5
```


## Usage

```js
var Carousel = require('antd-mobile-h5/components/carousel');
new Carousel({
        hasTrigger: true,
        play : true,
        interval: 2000,
        loop : true,
        lazyimg: 'https://zos.alipayobjects.com/rmsportal/NIscRCjezwtsnNl.gif',
        data: [
            {
                href: 'https://www.alipay.com',
                img: 'https://t.alipayobjects.com/images/rmsweb/T1UshgXipgXXXXXXXX.jpg'
            },
            {
                href: 'https://www.alipay.com',
                img: 'https://t.alipayobjects.com/images/rmsweb/T1XHtgXahxXXXXXXXX.jpg'
            },
            {
                href: 'https://www.alipay.com',
                img: 'https://t.alipayobjects.com/images/rmsweb/T1dbRgXdlqXXXXXXXX.jpg'
            }
        ]
    }).render('#J_CarouselBox');


```

## API

### props

<table class="table table-bordered table-striped">
    <thead>
    <tr>
        <th style="width: 100px;">name</th>
        <th style="width: 50px;">type</th>
        <th style="width: 50px;">params</th>
        <th style="width: 50px;">return</th>
        <th>description</th>
    </tr>
    </thead>
    <tbody>
      <tr>
          <td>data</td>
          <td>Array</td>
          <td></td>
          <td></td>
          <td>组件渲染所需数据</td>
        </tr>
        <tr>
          <td>render</td>
          <td>Function</td>
          <td></td>
          <td></td>
          <td></td>
        </tr>
        <tr>
          <td>trigger</td>
          <td>string</td>
          <td></td>
          <td></td>
          <td>触发元素，也可理解为状态元素</td>
        </tr>
        <tr>
          <td>visible</td>
          <td>Number</td>
          <td></td>
          <td></td>
          <td>每次滑动几个panels，默认1</td>
        </tr>
        <tr>
          <td>curIndex</td>
          <td>Number</td>
          <td></td>
          <td></td>
          <td>初始化在哪个panels上，默认0为第一个</td>
        </tr>
         <tr>
          <td>loop</td>
          <td>Boolean</td>
          <td></td>
          <td></td>
          <td>动画循环，默认false</td>
        </tr>
        <tr>
          <td>play</td>
          <td>Boolean</td>
          <td></td>
          <td></td>
          <td>动画自动播放，默认false</td>
        </tr>
        <tr>
          <td>interval</td>
          <td>Number</td>
          <td></td>
          <td></td>
          <td>播放间隔时间，默认5000ms，play为true时才有效</td>
        </tr>
    </tbody>
</table>