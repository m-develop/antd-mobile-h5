## install


```
npm install antd-mobile-h5
```


## Usage

```js
var Tab = require('antd-mobile-h5/components/tab');
var tab = new Tab({
        data: [
            {
                text: '标签栏1'
            },{
                text: '标签栏2'
            },{
                text: '标签栏3',
                selected: true
            }
        ],
        onSelected: function(index, item){
            console.log(index, item);
        }
    });

    tab.render('#J_TabBox', function(el){
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
          <td>onSelected</td>
          <td>Function</td>
          <td></td>
          <td></td>
          <td>选择回调</td>
        </tr>
        <tr>
          <td>update</td>
          <td>Function</td>
          <td></td>
          <td></td>
          <td>更新数据并重新渲染</td>
        </tr>
    </tbody>
</table>