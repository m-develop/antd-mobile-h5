## install


```
npm install antd-mobile-h5
```


## Usage

```js
var PageResult = require('antd-mobile-h5/components/page-result');
new PageResult({
      type: 'no-network',
      data: {
          title: '网络不给力',
          brief: '世界上最遥远的距离莫过于此',
          buttons: [{
              text : '刷新',
              handler: function(ev){
                  console.log(ev);
              }
          }]
      }
    }).render('#J_PageResult', function(el){
        console.log(el);
    });

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
          <td>type</td>
          <td>String</td>
          <td>no-network, network, error, busy, err, </td>
          <td></td>
          <td>弹窗类型, 默认空</td>
        </tr>
    </tbody>
</table>