## install


```
npm install antd-mobile-h5
```


## Usage

```js
var Notice = require('antd-mobile-h5/components/notice');
var notice new Notice({
        type: 'notice',
        data: {
            title: '因全国公民身份系统升级，添加银行卡银行卡银行卡银行卡银',
            buttons: [{
                type: 'close',
                handler: function (ev) {
                    console.log(ev);
                }
            }]
        }
    });
notice.render('#J_Notice');

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
          <td>Object</td>
          <td></td>
          <td></td>
          <td>组件渲染所需数据</td>
        </tr>
        <tr>
          <td>data.title</td>
          <td>String</td>
          <td></td>
          <td></td>
          <td>标题</td>
        </tr>
        <tr>
          <td>data.buttons</td>
          <td>Array</td>
          <td></td>
          <td></td>
          <td>按钮</td>
        </tr>
         <tr>
          <td>data.buttons.type</td>
          <td>String</td>
          <td>close, go, button</td>
          <td></td>
          <td>按钮类型</td>
        </tr>
        <tr>
          <td>data.buttons.text</td>
          <td>String</td>
          <td></td>
          <td></td>
          <td>type为button有效</td>
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
          <td>notice, inform</td>
          <td></td>
          <td>提示类型</td>
        </tr>
    </tbody>
</table>