<template>
	<div class="container-fluid">
  <div class="row">
    <div class="col-2 all-categories"  >
      全部商品分类
     <button 
	     class="navbar-toggler collapsed" 
	    data-target="#navbarsExampleDefault" 
	    data-toggle="collapse">
	        <span class="line"></span> 
	        <span class="line"></span> 
	        <span class="line"></span>
	</button>
    </div>
    <div class="col-10 merchant" style='border:1px solid red'>
     推荐商家
    </div>
    
  </div>


  <div class="row">
    <div class="col-2" style='padding:0'>
      	<ul>
		  <li>Item #1</li>
		  <li>Item #2</li>
		  <li>Item #3</li>
		  <li>Item #4</li>
		  <li>Item #5</li>
		  <li>Item #1</li>
		  <li>Item #2</li>
		  <li>Item #3</li>
		  <li>Item #4</li>
		  <li>Item #5</li>
		</ul>
    </div>
    <div class="col-8">
      2 of 3 (wider)
    </div>
    <div class="col-2">
      3 of 3
    </div>
  </div>
  
</div>
</template>



<script>


</script>



<style scoped>

.all-categories {
	padding:4px 5px;
	background-color: #ea5118;
	font-size: 14pt;
	color:white;
	text-align:center;
}
.merchant {
	padding:4px 5px;
	padding-left: 35px;
	font-size:14pt;

}

.navbar-toggler{
	width: 40px;
	height: 25px;
	
}

.navbar-toggler .line{
		width: 100%;
		float: left;
		height: 2px;
		background-color: #fff;
		margin-bottom: 5px;
		}



ul {
	
	width:100%;
	padding:0;
}


ul li {
    position: relative;
	font-size:14pt;
    padding:12px 0px;
	background:#181818;
	color:white;
    cursor:pointer;
	border-bottom:1px solid #d7d6e3;
}

ul {
  list-style: none;
}

ul li:after{
   content: '';
   position: absolute;
   border-right:2px solid #fff;
   border-bottom:2px solid #fff;
   background-color:black;
   width:10px;
   height:10px;
   top: calc(50% - 4px);
   right: 20px;
   transform: translateY(-20%) rotate(-45deg);
}






</style>