ybutton 华丽光影特效按钮
=============
  
相关链接
-------------
  
[ybutton在线演示](http://www.kpdown.com/ybutton/ "开辟软件站赞助") 
  
特性说明
-------------
  
纯css打造光影特效，因此用到了一些高级css特性，造成本按钮仅兼容谷歌浏览器。  
在其他浏览器上虽然看不到光影，但效果也不错。  
  
使用方法
-------------
  
引入ybutton核心css文件：  
  
    <link rel="stylesheet" href="css/ybutton.css">
  
在需要按钮的地方添加如下HTML元素：  
  
    <div class="ybutton">
      <span>
        <a href="javascript:void(0);" target="_blank" title="">测试按钮1</a>
      </span>
    </div>
  
通过最外层div元素的class属性，可以定制按钮细节：  
  
颜色可选值如下：  
  
* ybutton 默认灰色  
* ybutton-primary 蓝色  
* ybutton-success 绿色  
* ybutton-info 青色  
* ybutton-warning 黄色  
* ybutton-danger 红色  
  
尺寸可选值如下：  
  
* ybutton 默认中等尺寸  
* ybutton-sm 小号尺寸  
* ybutton-lg 大号尺寸  
  
综合示例：  
  
    <!-- 大按钮蓝色 -->
    <div class="ybutton ybutton-lg ybutton-primary">
      <span>
        <a href="javascript:void(0);" target="_blank" title="">测试按钮2</a>
      </span>
    </div>
  