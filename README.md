# areaSelector
> 中国城市三级联动选择器 jQuery版
>
> 版本 1.0.0

## 介绍
> 原js版为 area.js，作者不详！由于原版不满足需求，所以自己动手改了一下，并做了简单封装。
> 
###引入
```html
<script src="jquery.areaselector.js"></script>
```
> 
###使用
> 根据需求填写级别，最多三级。
> 
```html
<select id="province" name="province"></select>
<select id="city" name="city" ></select>
<select id="county" name="county" ></select>
```
> 
```javascript
$(document).ready(function() {
	$(document).areaSelector({
		id: ['#province', '#city', '#county'],
		text: ['省份', '城市', '区县'],
		after: function(data){}
	});
});
```
