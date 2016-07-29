# Sticky Navigation
Data supports that websites should have a sticky navigation as it allows a user to quickly visit different pages. [Solodev](https://www.solodev.com/) provides an easy-to-use sticky navigation using Bootstrap. 

## Tutorial

For detailed instructions, view Solodev's [Add a Sticky Nav to your Website with Bootstrap](https://www.solodev.com/blog/web-design/code-examples/add-a-sticky-nav-to-your-website-with-bootstrap.stml) article.

## Demo

Check out a working example on [JSFiddle](https://jsfiddle.net/solodev/ex1ypdtu/).

## HTML

A basic, fixed navigation is set up with the following HTML:
```
<nav class="navbar navbar-default navbar-fixed-top">
  <div class="container">
	<div class="navbar-header">
	  <button type="button" class="navbar-toggle collapsed" data-toggle="collapse" data-target="#navbar" aria-expanded="false" aria-controls="navbar">
		<span class="sr-only">Toggle navigation</span>
		<span class="icon-bar"></span>
		<span class="icon-bar"></span>
		<span class="icon-bar"></span>
	  </button>
	  <a class="navbar-brand" href="#">
		 <img src="images/logo.png" alt="Logo Solodev">
	  </a>
	</div>
	<div id="navbar" class="navbar-collapse collapse navbar-right"">
	  <ul class="nav navbar-nav">
		<li><a href="#">Home</a></li>
		<li><a href="#about">About</a></li>
		<li><a href="#contact">Contact</a></li>
		<li class="dropdown">
		  <a href="#" class="dropdown-toggle" data-toggle="dropdown" role="button" aria-haspopup="true" aria-expanded="false">Dropdown <span class="caret"></span></a>
		  <ul class="dropdown-menu">
			<li><a href="#">Action</a></li>
			<li><a href="#">Another action</a></li>
			<li><a href="#">Something else here</a></li>
			<li role="separator" class="divider"></li>
			<li class="dropdown-header">Nav header</li>
			<li><a href="#">Separated link</a></li>
			<li><a href="#">One more separated link</a></li>
		  </ul>
		</li>
	  </ul>
	  <ul class="nav navbar-nav navbar-right">
		<li><a href="./">Fixed top <span class="sr-only">(current)</span></a></li>
	  </ul>
	</div><!--/.nav-collapse -->
  </div>
</nav>
```

## CSS

CSS for this repository is primarily based on default Bootstrap classes. Of particular importance is the "navbar-fixed-top" class.

## External Includes

The form includes the following third-party resources:
```
<link href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.6/css/bootstrap.min.css" rel="stylesheet" type="text/css"/>
	
<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.12.4/jquery.min.js" type="text/javascript"></script>
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.6/js/bootstrap.min.js" type="text/javascript"></script>
```

