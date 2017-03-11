<!DOCTYPE html>
<html>
	<head>
		<meta charset="UTF-8">
		 <meta name="viewport" content="width=750, user-scalable=no">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
		<title></title>
		<style type="text/css">
			  * { margin: 0; padding: 0;}
			 html,body {  width: 100%; height: 100%;}
			  .main { min-width: 320px; /* 移动端设备分辨率最小的 */ max-width: 750px;  /* 设计图的宽度 */ margin: 0 auto; }

        header.yhq-header { width: 100%;height: 93px;  text-align: center;  box-sizing: border-box; border-bottom: 2px solid #07ca61;
        position: relative; color: #333;  font: 38px/91px '黑体';}

            .yhq-header .back-button {position: absolute; width: 62px; height: 91px; left: 0;
                top: 0; border: 0; outline: none; background: url('img/icon-back.png') no-repeat center center #fff;  }
          
            #top-txt{min-width: 300px; max-width: 750px;margin: 0 auto; font: 27px/100px  "微软雅黑"; text-align: center; padding: 20px 20px;line-height: 60px;background: #f88266;color:#fff ;}
           #resion{}
            #resion span{width: 100%; font:45px/145px  "微软雅黑"; text-align: center;display: block;color: #333333;}
			#resion a{display: block;text-align: center; text-decoration: none;font:28px/94px  "微软雅黑";line-height: 0; color: #07CA61; margin-bottom:100px;}
		.list {width: 100%; border: 1px solid #ccc; font:31px/100px  "微软雅黑";}
		.list span{margin-left: 25px;}
		.list .checkbox {float: right; width: 40px; height: 40px;border-radius:50% ; border: 1px solid #ccc; margin: 27px 20px 0 0;background: #fff;}
		.list .checkbox:hover{background: #07CA61;}
		#put {min-width: 300px; height: 750px; margin: 0 auto; }
		#put input{font:31px/100px "微软雅黑"; width: 90%; background: #07CA61; margin: 60px 20px; }
		</style>
	</head>
	<body>
		<div class="main">
	        <header class="yhq-header">
	            <button class="back-button"></button>
	            取消订单
	        </header>
    	</div>
    	<div id="top-txt">
    		<span id="">
    			若单日取消订单达到3次，账户将被冻结1天，请谨慎取消
    			您当日已取消 <span id="">2</span>次
    		</span>
    	</div>
    	<div id="resion">
    		<span id="">
    			请您真实告诉我们取消原因
    		</span>
    		<a href=""> 我们会努力为您提供更好的服务</a>
    	</div>
    	<div class="list">
    		<span id="">
    			司机离我太远
    		</span>
    		<label>
    			<input type="checkbox" name="" id="" value="" hidden />
    			<span class="checkbox">
    			</span>
    		</label>
    		
    	</div>
    	<div class="list">
    		<span id="">
    		重复下单或者下错单
    		</span>
    		<label>
    			<input type="checkbox" name="" id="" value="" hidden />
    			<span class="checkbox">
    			</span>
    		</label>
    		
    	</div>
    	<div class="list">
    		<span id="">
    			暂时不需要车
    		</span>
    		<label>
    			<input type="checkbox" name="" id="" value="" hidden />
    			<span class="checkbox">
    			</span>
    		</label>
    		
    	</div>
    	<div class="list">
    		<span id="">
    			司机让我取消订单
    		</span>
    		<label>
    			<input type="checkbox" name="" id="" value="" hidden />
    			<span class="checkbox">
    			</span>
    		</label>
    		
    	</div>
    	<div id="put">
    		<input type="button" name="" id="" value="提交" />
    	</div>
	</body>
</html>
