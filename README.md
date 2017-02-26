# badcss
badCss is a free open-source css framework.
*** Built by peter bou saada, aka b4db0y17 ***

*** Copyrighted Peter Bou Saada ***

list of classes:

// Layout
.row

.col-sm-*		(* between 1 and 24)
.col-md-*		(* between 1 and 24)
.col-lg-*		(* between 1 and 24)

.col-offset-*	(*between 1 and 11)

//navbar
.navbar

.navbar-default

.navbar-fixed-top
.navbar-fixed-left
.navbar-fixed-bottom
.nabar-fixed-right

.navbar-left	(left section, top section if using navbar-fixed-left or navbar-fixed-right)
.navbar-right	(right section , bottom section if using navbar-fixed-left or navbar-fixed-right)

.navbar-brand

//buttons		(add atribute disabled to make it look disabled)
.btn

.btn-default
.btn-primary
.btn-danger
.btn-alert
.btn-success
.btn-info

.btn-3d 		(makes button 3d)

How to use the classes:

//layout
<div class="row"> 	(div width 100%)
 	<div class="col-sm-*">
	</div>
	<div class="col-sm-*>
	</div>
</div>
// Sum of * must be equal to 24 total

//navbar
<div class="navbar navbar-default navbar-fixed-*">
	<div class="navbar-left">
		<div class="navbar-brand">Brand</div>
		<ul>
			<li>item #1</li>
			<li>item #2</li>
			<li>item #3</li>
			<li>item #4</li>
		</ul>
	</div>
	<div class="navbar-right">
		<ul>
			<li>item #1</li>
			<li>item #2</li>
		</ul>
	</div>
</div>
<div class="menu-*-accompany">
	// Other content goes here
</div>

// * = top, left, right, bottom	(should be the same in menu-*-accompany and navbar-fixed-*

//buttons
//each button must have .btn and .btn-* class
<button class="btn btn-*">Regular button</button>
<button class="btn btn-* btn-3d">3D Button</button>
<button class="btn btn-*" disabled>Regular button (disabled)</button>
<button class="btn btn-* btn-3d" disabled>3D Button (disabled)</button>

//btn-* = default, primary, danger, alert, success, info 
