# h5imagedit
##Html5 图片编辑
这个是基于Image Editor修改的，处理了iphone图片不能正常显示的问题，还有图片移动时小于选择框时的处理。
Image Editor原链接暂时忘记了，等找到后再添加。

使用方法可参考demo.html.
手机端端图片生成为了避免模糊，图片采用了x2的处理，所以显示的时候可以规定显示图片的大小以防止显示的图片过大而显示不完整的问题。

相关参数如下：

```
var defaults = {
        width: 400,
        height: 400,
        imageUrls: [], // element of array could be: 'images/url.jpg' or {url: 'images/url.jpg', closeButtonRequire: false, clickToSelect: true, onClick: function() {}}
        removeIcon: 'images/delete.png',
        removeIconSize: 0,
        addImageAnimation: true,
        removeImageAnimation: true,
        onImagesLoaded: function() {},
        onInitCompleted: function() {}
      };
```
      