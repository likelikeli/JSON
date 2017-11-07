# JSON
json的简单用法
采用完全独立于编程语言的文本格式来存储和表示数据
对象表示为键值对     数据由逗号分隔     花括号保存对象    方括号保存数组
		var obj={name:"明月",age:18}
 name：属性名/键/key
 明月：属性值/值/value
 name:"明月"键值对
 下面是JSON的写法：
 
    var json = '{"name":"丽德国际大酒店","address":"松江区泗泾镇九干路168丽德创业园","cd":[{"name":"油炸里脊","pirce":"$20","PL":["里脊","油","盐"]},{"name":"青椒土豆丝","pirce":"$16","PL":["青椒","土豆","丝"]}]}';
		var obj=JSON.parse(json);
		console.log(obj)
