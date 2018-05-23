```javascript
<script>
var n = 9;
var x = 0; 
var y = 0;
var action = "123";
function getAction() {
	var t = 1;
	for (var i = 0; i < action.length; i++) {
		if (action.charAt(i) == t) {
			action = action.substring(0, i) + t++ + action.substring(i);
		}
		t = t == 5 ? 1 : t;
	}	 
	if (action.charAt(action.length - 1) == "3") action += "41";
	else if (action.charAt(action.length - 1) == "1") action += "23";
}

for (var i = 2; i < n; i++) {
	getAction();
}

var r = [];
r.push([x,y]);
for (var i = 0; i < action.length; i++) {
	if (action.charAt(i) == "1") {x++};
	if (action.charAt(i) == "2") {y++};
	if (action.charAt(i) == "3") {x--};
	if (action.charAt(i) == "4") {y--};
	r.push([x,y]);
}

var rMap = {};
for (var i = 0; i < r.length; i++) {
	rMap[r[i] + ""] = (i + 1);
}

var table = "<table border=1>";
for (var y = 0; y < n; y++) {
	table += "<tr>";
	for (var x = 0; x < n; x++) {
		var index = [x,y] + "";
		table += "<td>" + rMap[index] + "</td>";
	}
	table += "</tr>";
}
table += "</table>";
document.write(table);
</script>
```
