<template>
	<div class="product-search">
		<div class="container-fluid">
		  <div class="row" >
		    <div class="col-2" >
		      <div>
		      	<img class='img-fluid' src="../../images/logo.png" alt="">
		      </div>
		    </div>
		    <div class=" col-8 form-cover" >
		      
		      	<form class='searchBox'  role="form" id="form-buscar">
					<div class="form-group">
						<div class="input-group">
							<input id="1" class="form-control" type="text" name="search" placeholder="韩国大宇空气炸锅" required/>
							<span class="input-group-btn">
							<button class="btn btn-success" type="submit">
							<i class="glyphicon glyphicon-search" aria-hidden="true"></i> 搜索
							</button>
							</span>
						</div>
						<span class='search-description'>大家都在搜：破壁机 扫地机器人 梦洁暖芯羽丝被 鸿运煲 麦饭石回飞炒锅</span>
					</div>
				</form>
		      
		    </div>
		    <div class="col-2" >
		       <div>
		      	
		      </div>
		    </div>
		  </div>
		  
		 
		</div>
	</div>


</template>


<script>
       
       

   export default {




   }




</script>



<style scoped>
	
  .product-search {
  	 margin-top: 55px;
  }

* {
  -webkit-border-radius: 1px !important;
     -moz-border-radius: 1px !important;
          border-radius: 1px !important;
}


.btn-success{
	background-color: #ea5118 !important;
}
.searchBox {
	width:70%;
	align-items: center;
	float:right;
	margin-top:20px;

}

.form-control:focus {
    border-color: red !important;
}

.search-description {
	font-size:13px;
}

#logo {
color: #666;
width:100%;   
}
#logo h1 {
    font-size: 60px;
    text-shadow: 1px 2px 3px #999;
    font-family: Roboto, sans-serif;
    font-weight: 700;
    letter-spacing: -1px;
}
#logo p{
  padding-bottom: 20px;
}


#form-buscar >.form-group >.input-group > .form-control {
    height: 40px;
}
#form-buscar >.form-group >.input-group > .input-group-btn > .btn{
        height: 40px; 
        font-size: 16px;
        font-weight: 300; 
         
       
}
#form-buscar >.form-group >.input-group > .input-group-btn > .btn .glyphicon{
 margin-right:12px;   
}    


#form-buscar >.form-group >.input-group > .form-control {
    font-size: 16px;
    font-weight: 300;
   
}

#form-buscar >.form-group >.input-group > .form-control:focus {
  border-color: #33A444;
  outline: 0;
  -webkit-box-shadow: inset 0 1px 1px rgba(0,0,0,.075), 0 0 1px rgba(0, 109, 0, 0.8);
          box-shadow: inset 0 1px 1px rgba(0,0,0,.075), 0 0 1px rgba(0, 109, 0, 0.8);
}
</style>