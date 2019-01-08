<template>
	

	 <!-- Navigation -->
    <nav class="navbar navbar-expand-lg fixed-top top-bar-header">
      
        <a href="#" class='home'><span class='home-icon glyphicon glyphicon-home'>易购首页</span></a>
       <a class='map' href="#"><span class='map-icon glyphicon glyphicon-map-marker'></span>天津</a>

        <div class="collapse navbar-collapse" id="navbarResponsive">

          <ul class="navbar-nav ml-auto">
          	<li class='nav-item '>
          		<p style='margin-top:5px;margin-right:5px'>你好，请登录  </p>
          	</li>
            <li class="nav-item active">
              <a class="nav-link" href="#">免费注册
                <span class="sr-only">(current)</span>
              </a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">我的订单   </a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">手机众享  </a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">帮助中心   </a>
            </li>
          </ul>
        </div>
      
    </nav>



</template>






<script>

export default {



}


</script>


<style scoped>
	
.top-bar-header {
        

	    background: #f8f8f8;
	    height:0.542in;
	    font-weight: bold;
	    font-size: 16px;
	    boder: 3px solid black;
	    text-decoration: none;
	    color:black;

}

.home-icon {
	padding-left: 0.170in;
	margin-top:3px;

}


.home {
	font-family: 'Microsof Yahei';
	font-size: 12pt;
	color:black;
}
.home-icon > i {
	font-size: 18px;
}


.map {
	text-decoration: none;
	color:black;
	margin-top:3px;
	margin-left: 10px;
}
.map-icon {
	color:red;
	font-size: 18px;
}

ul > li a {
	color:black !important;
}

ul > li:not(:last-child) a:after {
  content: "|";
  }



ul > li a:last-child {
	content: '';
	
}

.active a {
	color: red !important;
}

</style>