# areaSelector
中国三级城市联动选择器 jQuery版
版本 1.0.0

## 介绍

###引入
<script src="jquery.areaselector.js"></script>

###使用
```javascript
$(document).ready(function() {
	$(document).areaSelector({
		id: ['#province', '#city', '#county'],
		text: ['省份', '城市', '区县'],
		after: function(data){}
	});
});
```
