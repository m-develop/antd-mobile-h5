## install


```
npm install antd-mobile-h5
```


## Usage

```js
var Dialog = require('antd-mobile-h5/components/dialog');
new Dialog({
            type: 'image',
            closeAble: function () {
              var cancel = this.get('cancel');
              cancel && cancel.call(this);
            },
            topTitle: true,
            buttons: [{
                  id: 'cancel',
                  cls: 'am-button blue',
                  text: '行动按钮',
                  handler: function () {
                    var cancel = this.get('cancel');
                    cancel && cancel.call(this);
                }
              
            }],
            content : '辅助说明文字辅助说明文字辅助说明文字辅助说明文字', //也可以是文本和html
            title : '标题文字',
            imgUrl: 'https://os.alipayobjects.com/rmsportal/QnFHZkFYDZUJqBD.png',
            mask: true
        }).show();

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
          <td>type</td>
          <td>String</td>
          <td>simage, image</td>
          <td></td>
          <td>弹窗类型, 默认空</td>
        </tr>
        <tr>
          <td>title</td>
          <td>String</td>
          <td></td>
          <td></td>
          <td>标题，默认为空</td>
        </tr>
        <tr>
          <td>content</td>
          <td>String</td>
          <td></td>
          <td></td>
          <td>Dialog的内容, 文本或者html</td>
        </tr>
        <tr>
          <td>imgUrl</td>
          <td>String</td>
          <td></td>
          <td></td>
          <td>图片地址</td>
        </tr>
        <tr>
          <td>buttons</td>
          <td>Array</td>
          <td>id, cls, text, disabled, handler</td>
          <td></td>
          <td>按钮组，默认2个按钮</td>
        </tr>
        <tr>
          <td>show</td>
          <td>Function</td>
          <td></td>
          <td></td>
          <td>显示</td>
        </tr>
         <tr>
          <td>hide</td>
          <td>Function</td>
          <td></td>
          <td></td>
          <td>Function</td>
        </tr>
        <tr>
          <td>footCls</td>
          <td>String</td>
          <td></td>
          <td></td>
          <td>弹窗底部区域样式</td>
        </tr>
        <tr>
          <td>closeAble</td>
          <td>Function</td>
          <td></td>
          <td></td>
          <td>显示关闭</td>
        </tr>
        
    </tbody>
</table>