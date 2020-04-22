 1、导入jyufou.js
  <script src="jyufou.js"></script>
 2、初始化,需要传入accessKeySecret和accessKeyID
 var access = {
			accessKeySecret: "accessKeySecret",
			accessKeyID: "accessKeyID"
	}
  yufou.init(access);
  3、获取用户信息
    function initUser(data) {
				var d = JSON.parse(data);
				console.log(d["userid"]) 
				console.log(d["username"]) 
				return null;
			}
  
整体代码如下：
    <script src="jyufou.js"></script>
		<script>
			var access = {
				accessKeySecret: "accessKeySecret",
				accessKeyID: "accessKeyID"
			}
			yufou.init(access);
			function initUser(data) {
				var d = JSON.parse(data);
				console.log(d["userid"]) 
				console.log(d["username"]) 
				return null;
			}
		</script>
