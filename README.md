<!DOCTYPE html>
<html>
	<head>
  		<meta charset="utf-8">
  		<title>Online Food</title>
		<meta name="viewport" content="width=device-width, initial-scale=1.0, minimum-scale=1.0, maximum-scale=1.0, user-scalable=0">
		<meta name="author" content="flip.hr">
		<meta name="apple-mobile-web-app-capable" content="yes">
		<meta name="apple-mobile-web-app-status-bar-style" content="black">
	
	
		<link href="https://fonts.googleapis.com/css?family=Roboto:300,400,500" rel="stylesheet">
		<link href="css/bootstrap.min.css" rel="stylesheet">
		<link href="css/font-awesome.min.css" rel="stylesheet">
		<link href="css/style.css" rel="stylesheet">
	</head>

	<body>

		<nav class="navbar navbar-collapse-xs navbar-expand-md fixed-top">
	    	
	    	<div class="container">
		    	<a class="navbar-brand" href="#"><i class="fa fa-map-marker"></i> Food-Court</a>
		      	
		      	<button class="navbar-toggler" data-toggle="collapse" data-target="#main-menu">
		        	<span class="navbar-toggler-icon"></span>
		      	</button>

	      		<div class="collapse navbar-collapse" id="main-menu">
	        		<ul class="navbar-nav ml-auto">
			        	<li class="nav-item active">
			            	<a class="nav-link" href="#">Home</a>
			          	</li>
	          			<li class="nav-item dropdown">
					        <a href="#" class="nav-link dropdown-toggle" data-toggle="dropdown">
					          Browse
					        </a>
					        <div class="dropdown-menu">
								<a class="dropdown-item" href="#">French Ice Creams</a>
					        	<a class="dropdown-item" href="#">Light Ice Creams</a>
					        	<a class="dropdown-item" href="#">Organic Ice Creams</a>
					          	<a class="dropdown-item" href="#">No Sugar Ice Creams</a>
					          	<a class="dropdown-item" href="#">Lactose-Free Ice Creams</a>
					          	<a class="dropdown-item" href="#">Gluten-Free Ice Creams</a>
					        </div>
					    </li>
	          			<li class="nav-item">
	            			<a class="nav-link" href="#">Partner with Us!!</a>
	          			</li>
	          			<li class="nav-item">
	            			<a class="nav-link" href="#" data-toggle="modal" data-target="#account-modal" data-case="login" >Login</a>
	          			</li>
	          			<li class="nav-item">
	            			<a class="nav-link" href="#" data-toggle="modal" data-target="#account-modal" data-case="register">Register</a>
	          			</li>
	        		</ul>

					
	      		</div><!-- .collapse -->
      		</div><!-- .container -->
    	</nav><!-- nav -->

	    <div class="home-hero">
	    	<div class="container">
	    		<div class="row">
	    			<div class="col-md-12">
	    				<div class="content-box">
	    					<h2>Explore nearby Ice-cream Parlors</h2>
			    			<form method="GET" action="#">
			  					<div class="form-group">
									<input type="text" class="form-control" placeholder="What do you want to order today?">
									<input type="submit" class="btn btn-green" value="Search">
			  					</div><!-- .form-group -->
		  					</form>
	    				</div><!-- .content-box -->
	    			</div><!-- .col-md-12 -->
	    		</div><!-- .row -->
	    	</div><!-- .container -->
	    </div><!-- .home-hero -->

	    <div class="place-list">
	    	<div class="container">
	    		<div class="row">
	    			<div class="col-md-9 push-md-3">
	    				<div class="row">
			    			<div class="col-sm-6 col-md-6 col-lg-4 order-last">
				    			<div class="card">
									<img class="card-img-top" src="https://unsplash.it/350/250" alt="Place 1">
								  	<div class="card-block">
								    	<h4 class="card-title">IceKraft</h4>
								    	<p class="card-text">This is cute dessert parlor doles out a wide range of sweet treats!!!</p>
								    	<a href="place.html" class="btn btn-purple">More about IceKraft <i class="fa fa fa-angle-double-right"></i></a>
								  	</div><!-- .card-block -->
								</div><!-- .card -->
							</div><!-- .col-md-4 -->
							<div class="col-sm-6 col-md-6 col-lg-4">
				    			<div class="card">
									<img class="card-img-top" src="https://unsplash.it/350/250" alt="Place 1">
								  	<div class="card-block">
								    	<h4 class="card-title">Cream Stone</h4>
								    	<p class="card-text">It is a <span data-toggle="tooltip" data-placement="left" data-html="true" title="2nd Floor Livery Place<br>35 Livery Street<br>Colmore Business District<br>Birmingham B3 2PB<br>United Kingdom">nice spot  </span> to satiate the sweet tooth with tasty, sweet treats.</p>
								    	<a href="#" class="btn btn-purple" data-toggle="popover" title="Did you know?" data-content="And here's some amazing content. It's very engaging. Right?" data-trigger="focus">More about Cream Stone<i class="fa fa fa-angle-double-right"></i></a>
								  	</div><!-- .card-block -->
								</div><!-- .card -->
							</div><!-- .col-md-4 -->
							<div class="col-sm-6 col-md-6 col-lg-4">
				    			<div class="card">
									<img class="card-img-top" src="https://unsplash.it/350/250" alt="Place 1">
								  	<div class="card-block">
								    	<h4 class="card-title">Rajmandir Ice Cream</h4>
								    	<p class="card-text"> One of the great establishments of the area!!! </p>
								    	<a href="#" class="btn btn-purple dynamic-popover" data-bind="#popover-1">More about Rajmandir <i class="fa fa fa-angle-double-right"></i></a>
								  	</div><!-- .card-block -->
								</div><!-- .card -->
							</div><!-- .col-md-4 -->
							<div class="col-sm-6 col-md-6 col-lg-4">
				    			<div class="card">
									<img class="card-img-top" src="https://unsplash.it/350/250" alt="Place 1">
								  	<div class="card-block">
								    	<h4 class="card-title">Khatri Bandhu</h4>
								    	<p class="card-text">Here are amazing flavors available which consists of flavors like mastani, anjeer, butter scotch mastani, and chocolate mastani.</p>
								    	<a href="#" class="btn btn-purple">More about Khatri Bandhu <i class="fa fa fa-angle-double-right"></i></a>
								  	</div><!-- .card-block -->
								</div><!-- .card -->
							</div><!-- .col-md-4 -->
							<div class="col-sm-6 col-md-6 col-lg-4">
				    			<div class="card">
									<img class="card-img-top" src="https://unsplash.it/350/250" alt="Place 1">
								  	<div class="card-block">
								    	<h4 class="card-title">Giani's Ice-cream</h4>
								    	<p class="card-text">Giani is here for generations and proved itself to be one of the best dessert places.</p>
								    	<a href="#" class="btn btn-purple">More about Giani's <i class="fa fa fa-angle-double-right"></i></a>
								  	</div><!-- .card-block -->
								</div><!-- .card -->
							</div><!-- .col-md-4 -->
							<div class="col-sm-6 col-md-6 col-lg-4">
				    			<div class="card">
									<img class="card-img-top" src="https://unsplash.it/350/250" alt="Place 1">
								  	<div class="card-block">
								    	<h4 class="card-title">Frozen bottle</h4>
								    	<p class="card-text">The Frozen bottle has the most scrumptious frozen ice creams, shakes desserts and much more! </p>
								    	<a href="#" class="btn btn-purple">More about Frozen bottle<i class="fa fa fa-angle-double-right"></i></a>
								  	</div><!-- .card-block -->
								</div><!-- .card -->
							</div><!-- .col-md-4 -->
						</div><!-- .row -->
					</div><!-- .col-md-9 -->
	    			<div class="col-md-3 pull-md-9">
						<ul class="list-group">
						  	<a href="#" class="list-group-item active">All categories</a>
							<a href="#" class="list-group-item list-group-item-action">French Ice Creams</a>
						  	<a href="#" class="list-group-item list-group-item-action">Organic Ice Creams</a>
						  	<a href="#" class="list-group-item list-group-item-action">No Sugar Ice Creams</a>
							<a href="#" class="list-group-item list-group-item-action">Lactose-Free Ice Creams</a>
							<a href="#" class="list-group-item list-group-item-action">Gluten-Free Ice Creams</a>
						</ul>
					</div><!-- .col-md-3 -->
				</div><!-- .row -->
			</div><!-- .container -->
	    </div><!-- .place-list -->


	    <div class="modal fade" id="test-modal">
  			<div class="modal-dialog">
    			<div class="modal-content">
			    	<div class="modal-header">
			        	<h5 class="modal-title">Modal title</h5>
			        	<button type="button" class="close" data-dismiss="modal">
			          		<span aria-hidden="true">&times;</span>
			        	</button>
			      	</div><!-- .modal-header -->
				   
      				<div class="modal-footer">
				        <button type="button" class="btn btn-secondary" data-dismiss="modal">Close</button>
				        <button type="button" class="btn btn-primary">Save changes</button>
        			</div><!-- .modal-footer -->
    			</div><!-- .modal-content -->
  			</div><!-- .modal-dialog -->
		</div><!-- .modal -->




	    <div class="modal fade" id="account-modal">
 			<div class="modal-dialog">
    			<div class="modal-content">
    				<a href="#" class="close-modal" data-dismiss="modal"><i class="fa fa-times"></i></a>
			      	<div class="modal-body">
			        	<div class="form-box">
			        		<div id="login-case">
	    						<h3>Login to your account</h3>
	    						<p>If you already a member login to your Neighborhood account.</p>
		    					<form method="POST" action="#" class="validate">
				  					<div class="form-group">
			    						<label class="form-control-label">E-mail</label>
			    						<input type="email" class="form-control" data-fv-notempty="true">
				  					</div><!-- .form-group -->
				  					<div class="form-group">
			    						<label class="form-control-label">Password</label>
			    						<input type="password" class="form-control" data-fv-notempty="true">
				  					</div><!-- .form-group -->
								  	<div class="form-group">
								  		<input type="submit" value="Login" class="btn btn-green">
								  	</div><!-- .form-group -->
		  						</form>
	  						</div><!-- #login-case -->
	  						<div id="register-case" style="display: none;">
	    						<h3>Create an account</h3>
		    					<p>Register on our great website to become a part of your Neighborhood.</p>
			    				<form method="POST" action="#">
				    				<div class="form-group">
			    						<label class="form-control-label">Your name</label>
			    						<input type="text" class="form-control" placeholder="Please enter your full name" data-fv-notempty="true">
				  					</div><!-- .form-group -->
				  					<div class="form-group">
			    						<label class="form-control-label">E-mail</label>
			    						<input type="email" class="form-control" placeholder="Please enter your e-mail address" data-fv-notempty="true">
				  					</div><!-- .form-group -->
				  					<div class="form-group">
			    						<label class="form-control-label">Password</label>
			    						<input type="password" class="form-control" data-fv-notempty="true">
				  					</div><!-- .form-group -->
				  					<div class="form-check">
									    <label class="form-check-label">
									      <input type="checkbox" class="form-check-input">
									      I agree to your awesome Terms of service
									    </label>
								  	</div><!-- .form-check -->
								  	<div class="form-group">
								  		<input type="submit" value="Become a member" class="btn btn-green">
								  	</div><!-- .form-group -->
			  					</form>
	  						</div><!-- #login-case -->
  						</div><!-- .form-box -->
			      	</div><!-- .modal-body -->
    			</div><!-- .modal-content -->
  			</div><!-- .modal-dialog -->
		</div><!-- .modal -->

		<div style="display:none;">
			<div id="popover-1">
		    	<div class="data-title">More about parlor</div>
		    	</div>
		</div>


		<script src="//ajax.googleapis.com/ajax/libs/jquery/3.1.1/jquery.min.js"></script>
		<script src="js/tether.min.js"></script>
		<script src="js/bootstrap.min.js"></script>
		<script src="js/jquery.site.js"></script>
			
	</body>
</html>
