# Javascript

HTML5自身其实已经附带了挺多的控件了，详情见：[http://www.w3school.com.cn/html5/att_input_type.asp](http://www.w3school.com.cn/html5/att_input_type.asp)。不过鉴于当前阶段兼容性的问题，所以还是很有必要采取js方式实现的。

网页中的控件，常见的就是时间的输入，范围的选择，选项的选择，图片输入预览和截取。


## 时间输入控件:

- [bootstrap-datepicker](https://github.com/eternicode/bootstrap-datepicker "使用")
- [bootstrap-datetimepicker](https://github.com/smalot/bootstrap-datetimepicker)
- [datetimepicker](https://github.com/xdan/datetimepicker)
- [bootstrap-datetimepicker](https://github.com/Eonasdan/bootstrap-datetimepicker)

PS: **bootstrap-datepicker** 版本有多个


## 图片上传预览裁剪

## 移动设备检测

```javascript
<script type=”text/javascript”>
	if( /Android|webOS|iPhone|iPad|iPod|BlackBerry|IEMobile|Opera Mini/i.test(navigator.userAgent) ) {
		window.location = “mobile.html”; //可以换成http地址
	}
</script>
```

[https://github.com/matthewhudson/device.js](https://github.com/matthewhudson/device.js)