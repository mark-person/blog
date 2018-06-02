#  关注眼前的麻烦
> "公司里的脏话太多，这让大家很不舒服。"
 
* 在科技行业，有些人不介意脏话，而有些人却介意
* 如果允许，有人辞职
* 如果不允许，有人辞职

* 折中做法很难行的通 P165

> 禁止说脏话只会拒那些优秀人才于千里之外，允许它的存在，但并不意味着你可以用污言秽语恐吓或者骚扰其他人。

# 不要听风就是雨 P217
> "有人穿短裤上班！我们得制定一着装规定！"
* 没必要，只要告诉他不要再穿短裤上班就行了



# 程序题
华为面试题 输入一个n，在屏幕上输出N*N的矩阵

如果不是特殊矩阵，也就不是正方形呢。比如N*1的矩阵该怎么办


# ai速算
```javascript
<script>
function getRand(){
	var s = "";
	for (var i = 0; i < 200; i++) {
		s += parseInt(Math.random()*10%2);
	}
	return s;
}
var my = "10101101100100010101010110010110100101101101011011100101001101110101010101010101100101101010101010110010110100101101101011011010110110101101111001011010010110110101101101010110010110100101101101011011";
document.write("下面哪一组最可能是假的随机数?<br>");
document.write("A:" + getRand() + "<br>");
document.write("B:" + getRand() + "<br>");
document.write("C:" + my + "<br>");
document.write("D:" + getRand() + "<br>");
</script>
```

```javascript
<script>
var one = 0 + Math.pow(25, 0) + Math.pow(25, 1) + Math.pow(25, 2) + Math.pow(25, 3);
var two = 1 + Math.pow(25, 0) + Math.pow(25, 1) + Math.pow(25, 2);
var three = 2 + Math.pow(25, 0) + Math.pow(25, 1);
var four = 3 + + Math.pow(25, 0);
var s = "baca";
var n0 = (s.charCodeAt(0) - 97) * one;
var n1 = (s.charCodeAt(1) - 97) * two;
var n2 = (s.charCodeAt(2) - 97) * three;
var n3 = (s.charCodeAt(3) - 97) * four;
alert(n0 + n1 + n2 + n3 - 1);
</script>
```

error异常 记得住 为什么要故事
为什么要实干 理论作用？
十倍的技术，十倍受益
不用京东 买iphone8plus

# 增量部署
增量部署漏掉内部类 AccessQueueConsumer$AccessQueueThread.class ;别一个是静态变量java和class也是不对应的


一个人每天给他一块钱，哪天不给了他便会记恨；一个人每天给他一巴掌，哪天不给了便会感激，这是什么心理？

斗米养恩，担米养仇




