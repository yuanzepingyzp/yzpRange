# yzpRange
range compenent powered by angularjs 
##USEAGE
```html
<!DOCTYPE html>
<html>
	<head>
		<meta charset="utf-8">
		<link rel="stylesheet" type="text/css" href="yzpRange.css">
	</head>
	<body ng-app="app">
		<yzp-range start-range=0 end-range=10 yzp-value=0.5 length=1000></yzp-range>
		<script type="text/javascript" src="angular.js"></script>
		<script type="text/javascript" src="yzpRange.js"></script>
	</body>
</html>
```
##API
```html
    <yzp-range start-range=0 /*number,define the start range of the compenent*/
                end-range=10 /*number,define the end range of the compenent*/
                yzp-value=0.5 /*number define the value of the compenent,max value is 1*/
                length=1000/*number define the length of the compenent*/
                ></yzp-range>
```
##总结
event.clientX获取鼠标相对于窗口的坐标，event.pageX(IE)鼠标相对于文档开头的坐标，event.screenX鼠标相对于显示器边缘坐标，
