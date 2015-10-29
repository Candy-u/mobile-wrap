# mobile-wrap参数
startSlide: 4,  //起始图片切换的索引位置

auto: 3000, //设置自动切换时间，单位毫秒

continuous: true,  //无限循环的图片切换效果

disableScroll: true,  //阻止由于触摸而滚动屏幕

stopPropagation: false,  //停止滑动事件

callback: function(index, element) {},  //回调函数，切换时触发

transitionEnd: function(index, element) {}  //回调函数，切换结束调用该函数。

