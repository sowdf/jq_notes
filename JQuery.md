很高兴能和大家分享JQuery入门分享，第一次分享，有什么不好的地方请大家多多指教！
选择元素：

	$();

	css();

	省略原生的循环操作
	
	$ == jQuery 
JQ方法函数化 
	
	事件：click()

	内容： 

	html()

JS与	JQ关系
	
	之间不能混写

	函数中返回原生的this,$()选择元素 

取值与赋值的关系

	通过参数决定
	
	属性：attr()

	值 ： val()

	多元素去值：去第一个值 

强大的$():
	
	加载：$(function(){});

	属性选择：[=],[^=],[$=],[*=] ( 这个比较有用重点介绍这个的用法 )
	
	引号问题

JQ的链式操作
	
	$().css().html().click(); 针对设置的时候



集合的长度 
	
	size()

	length 

	$()取到的都是一个集合

class操作

	addClass() 

	removeClass()

	toggleClass()

显示隐藏 ： 

	show()/hide()

	sho()/hide() 与 css的显示隐藏有什么不一样

节点的选择： 

	prev() next()

	prevAll() nextAll()

	siblings() 

	参数表示筛选功能
下标 
	
	eq()

JQ实战小技巧

	命名规范 $div $span

	容错处理 $() 选择到的元素不存在不会报错

	利用length 判断元素是否存在

	利用参数可以解决查找问题 


		

	
