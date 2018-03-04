# 筆記

### ch1
- alert()
- onload()
- onclick()
- prompt() : pop-up window
- Three data type : text/number/boolean

### ch3
- `prompt(text, defaultText)`：input
- `setTimeout(function,milliseconds)`：定時計時器
- `clearTimeout(id_of_settimeout)`：清除定時計時器
- 視窗大小
	```
		var clientWindowHeight = window.innerHeight
		|| document.documentElement.clientHeight
		|| document.body.clientHeight;
	``` 
- 如果改變image的寬或高另一個有會等比例縮放
- `<body onload="載入" onresize="調整視窗">`