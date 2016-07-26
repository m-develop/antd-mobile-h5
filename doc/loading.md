## install


```
npm install antd-mobile-h5
```


## Usage

```js
var Loading = require('antd-mobile-h5/components/loading');
var loading = new Loading({
          type: 'page',
          data: {
              text : '正在加载...'
          }
      });
loading.render('#J_PageLoading');

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
          <td>page</td>
          <td></td>
          <td>弹窗类型, 默认空</td>
        </tr>
    </tbody>
</table>