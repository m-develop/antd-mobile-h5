## install


```
npm install antd-mobile-h5
```


## Usage

```js
var Toast = require('antd-mobile-h5/components/toast');
var toast = new Toast({
      content : '自定义业务文案最多14个字符'
    });

toast.show();

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
          <td>show</td>
          <td>Function</td>
          <td></td>
          <td></td>
          <td></td>
        </tr>
      <tr>
          <td>type</td>
          <td>String</td>
          <td>fail, success, network, warn, loading</td>
          <td></td>
          <td>toast类型</td>
        </tr>
        <tr>
          <td>hideDelay</td>
          <td>Number</td>
          <td></td>
          <td></td>
          <td>延迟隐藏的时间</td>
        </tr>
        
    </tbody>
</table>