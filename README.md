# 先看效果图


![这里写图片描述](http://img.blog.csdn.net/20170712105504004?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvQW5keV9sMQ==/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)


# 技术要点


-  **自定义dialog布局**
- **ListView实现无限滑动**
- **使listView可见条目的第二条保持选中状态**

- 只是单纯的写一个demo,实现pickerView的效果,开始没想到用无限滑动来实现,想着滑动时默认是可见条目的第二条是选中的,这样的话滑动到底部选中状态条目的下面位置的条目是没办法选中的,想着再加一个条目点击事件不就可以了,但就是这么简单的需求出问题了 ,滑动选中我是在ListView的滚动监听实现的,但此时在设置条目点击事件无效,哪位大神解决好了,麻烦告知一下
[CSDN][1]
[1]:http://blog.csdn.net/Andy_l1/article/category/6891276
