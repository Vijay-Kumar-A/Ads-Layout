

<!DOCTYPE html>
<html >
<head>
	<meta charset="UTF-8">
	<title>Front-end webpage layout </title>
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<link href="https://fonts.googleapis.com/css?family=Open+Sans" rel="stylesheet">
	<link rel="stylesheet" href="css/style.css">
	<link rel="stylesheet" href="http://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">
	<!-- jQuery library -->
	<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/material-design-iconic-font/2.2.0/css/material-design-iconic-font.min.css">
	<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.12.4/jquery.min.js"></script>
	<!-- Latest compiled JavaScript -->
	<script src="http://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>
	<script type="text/javascript">
	
	</script>
	<style type="text/css">
		.box 
		{
    		height: 700px;
    		width: 80%;
    		margin: 50px;
   		 	border-style: solid outset outset solid;
		}

		.table
		{
			border: 2px solid black;
		}

		.logo
		{
			
			width:25%;
			height: 100px;
		    border-right: 1px solid black;
		    border-bottom: 1px solid black;
		    background-color: white;
		   
		}

		.sidenav1
		{
		    padding-top: 5px;
		    background-color: #f1f1f1;
		    height: 260px;
		    border-right: 2px solid;
		    border-bottom: 1px solid;
	    }

		@media screen and (max-width: 767px) 
		{
      		.sidenav1 
      		{
			    height: auto;
			    width: auto;
			    padding: 15px;

	      	}
	      	
    	}

    	.sidenav3
		{
		    padding-top: 20px;
		    background-color: #f1f1f1;
		    height: 450px;
		    width: 25%;
	    }

	    @media screen and (max-width: 767px) 
		{
      		.sidenav3 
      		{
			    height: auto;
			    width: auto;
			    padding: 15px;

	      	}
	      	
    	}

		.bar
		{
			width: 50%;
			height: 43px;
			border-bottom: 1px solid black;	
			background-color: lightblue;
		}

		.bar1
		{
			width: 25%;
			height: 43px;
			border-bottom: 1px solid black;	
			border-left: 1px solid black;
			background-color: cyan;
		}

		 .img
		 {
			width: 100%;
			height: 90px;
		 }

		 .index
		 {
		 	background-color: lightblue;
		 }


	    .link
	    {

		    list-style-type: none;
		    width: 100%;
		    background-color: lightblue;
		}

		.li a 
		{
		    display: block;
		    text-align: left;
		    color: #000;
		    text-decoration: none;
		}

		.li a:hover 
		{
		    background-color: #555;
		    color: white;
		}

		.title
		 {
		 	width: 100%;
		 	height: 100px;
		 	border-bottom: 1px solid black;
		 	background-color: pink;
		 	font-size: 40px;
		 	text-align: center;
		 }

		 .three
		 {
		 	width: 100%;
		 	height:40px;
		 	border-bottom: 1px solid black;
		 	background-color: lightgreen;
		 }

		 .four
		 {

		 	width: 100%;
		 	height: 50px;
		 	border-bottom: 2px solid black;
		 	background-color: cyan;
		 }

		div.absolute 
		{
			    position: relative;
			    bottom:190px;
			    width: 25%;
			    height: 200px;
			    border-right: 2px solid ;
		}

		ul
		{
			    list-style-type: none;
			    margin: 0;
			    padding: 0;
			    overflow: hidden;
		}

		li a
		{
		 	
		 	text-align: center;
   			text-decoration: none;
   			color:black;
		}

		header
		{
			height: 190px;
		}

		footer 
		{
			  position: relative;
		      background-color: rgb(255, 169, 137);
		      color: black;
		      width: 100%;
		      bottom: 200px;
		      height: 55px;
		      border-top: 2px solid;
		      text-align: center;
	    }

	    .breadcrumb 
	    {
    		padding: 8px 15px;
   			margin-bottom: 20px;
    		list-style: none;
		}

		body 
		{
 			 position: relative;
 			 
		}


	</style>
</head>
<body data-spy="scroll" data-target="#navbar-example" >
<div class="box">
		<div class="col-md-12">
				<header>
						<div class="row">
							<div class="col-sm-3 col-md-6 col-lg-2 logo">
								<a href="#"> <img src="images/vtiger.png" class="img" ></a>
							</div>

							<div class="col-sm-6 col-md-6 col-lg-7 bar">
								<ul class="breadcrumb" style="float:right; background-color:lightblue">
									<li><a href="#calendar">Calendar</a></li>
									<li><a href="#a-z">A-Z Index</a></li>
								</ul>
							</div>

							<div class="col-sm-3 col-md-6 col-lg-3 bar1">
								<input type="text" name="Search" style="margin-top:5px"></input>
								<button type="button" class="btn btn-xs"> Go </button>
							</div>

							<div class="title">Vtiger CRM Solutions</div>
						</div>

						<div class="row">
							<div class="three">
    							<ul class="breadcrumb" style="float:right; background-color:lightgreen">
									<li><a href="#home"> Home</a></li>
									<li><a href="#page1"> Page 1</a></li>
									<li><a href="#page2"> Page 2</a></li>
									<li><a href="#contact">Contact Us</a></li>
								</ul>
							</div>
						
							<div class="four">
						
								<ul class="nav nav-tabs" style="position:relative; top:5px; left:270px; border:transparent">
									<li><a data-toggle="tab" href="#select">SelectedTabStyle</a></li>
									<li style="border:1px solid; left:10px; background-color:lightblue"><a data-toggle="tab" href="#html" >Unselected Tab</a></li>
									<li style="border:1px solid; left:20px; background-color:lightblue"><a data-toggle="tab" href="#css">Unselected Tab</a></li>     
								</ul>
						
							</div>
						</div>
				</header>
				<div class="row">
					<div class="text-center">
					    <div class="col-sm-3 col-md-3 col-lg-3 sidenav1" style="background-color:lightblue">
					    	<ul class="link">
						      <p class="li"><a href="#">Homepage of site</a></p>
						      <p class="li"><a href="#">Common list tables</a></p>
						      <p class="li"><a href="#">Subscription Link</a></p>
						      <p class="li"><a href="#">Most visited</a></p>
						      <p class="li"><a href="#">Unsubscription Link</a></p>
						      <p class="li"><a href="#">Results</a></p>
						      <p class="li"><a href="#">Infrastructure</a></p>
						      <p class="li"><a href="#">Comments</a></p>
						    </ul>
					    </div>

					    <div class="col-sm-6 col-md-6 col-lg-6 text-left" id="navbar-example">
					    	<div class="container-fluid tab-pane fade" id="select">
					    	<div style="" class="tab-content clearfix">
								<div class="tab-pane active">
									<div class="row" style="height: 400px; overflow-x: hidden; overflow-y: scroll">
					      				<nav class="breadcrumb" id="up" style="background-color:white">
											<li><a class="breadcrumb-item" href="#homepage">HomePage</a></li>
											<li><a class="breadcrumb-item" href="#selectionmenu">Selection Menu</a></li>
											<li><a class="breadcrumb-item" href="#submenu">Sub Menu</a></li>
											<br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>
											<a href="#up">
									          <span class="glyphicon glyphicon-chevron-up"></span>
									        </a>jump-to-top
										</nav>
									</div>
								</div>
							</div>	
							</div>
							<div class="tab-pane fade" id="html">
							
							</div>
							<div class="tab-pane fade" id="css">
							
							</div>

						</div>

					    <div class="col-sm-3 col-md-6 col-lg-4 sidenav3" style="border-left: 2px solid">
					    </div>
					</div>
				</div>

				<div class="row">
					<div class="col-md-3 absolute">
						    	
					</div>
				</div>
				
				<div class="row">
					<footer>
						<p>
							Vtiger CRM Solutions, 12th main road, 3rd block, Rajajinagar, Bangalore-10<br>
							<p> Copyright <span class="glyphicon glyphicon-copyright-mark"></span> 2004, Vtiger, All rights reserved, Tel:092436 02352</p>
						</p>
					</footer>	
				</div>
		</div>	
	
</div>
</body>
