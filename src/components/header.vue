<template>

<div class="a-header">
		<input type="checkbox" name="main-nav" id="main-nav" class="burger-check">
		<label for="main-nav" class="burger menu"><span></span></label>
        <a href="https://signifly.com/" class="logo">Signifly</a>
		<ul>
				<li><a href="#">ABOUT US</a></li>
				<li><a href="#" class="active">WORK</a></li>
				<li><a href="#">SERVICES</a></li>
                <li><a href="#">APPROACH</a></li>
		</ul>
        
</div>

</template>
<style scoped>
@import url(https://fonts.googleapis.com/css?family=Raleway:400,200);


/* BURGER MENU */

html,
body {
		width: 100%;
		height: 100%;
		overflow-x: hidden;
		margin-top: 0;
		margin-bottom: 0;
}

*,
*:before,
*:after {
		-webkit-transition: all 0.3s;
		transition: all 0.3s;
		box-sizing: border-box;
}


.burger-check {
		display: none;
}

.burger {
		position: relative;
		float: left;
		margin-left: 10px;
		width: 60px;
		height: 60px;
		cursor: pointer;
}

.burger span,
.burger span:before,
.burger span:after {
		position: absolute;
		left: 10px;
		top: 22px;
		width: 25px;
		height: 3px;
		background: black;
		border-radius: 0.2em;
}

.burger span:before,
.burger span:after {
		content: '';
		left: 0;
}

.burger span:before {
		top: -8px;
}

.burger span:after {
		top: 8px;
}

.burger-check:checked + .burger:after {
		content: '';
}


.burger-check:checked + .burger span {
		height: 0;
		width: 0;
}   

.burger-check:checked + .burger span:before,
.burger-check:checked + .burger span:after {
		top: 6px;
}

.burger-check:checked + .burger span:before {
		-webkit-transform: rotate(225deg);
		-ms-transform: rotate(225deg);
		transform: rotate(225deg);
}

.burger-check:checked + .burger span:after {
		-webkit-transform: rotate(-225deg);
		-ms-transform: rotate(225deg);
		transform: rotate(-225deg);
}

span.boo {
		width: auto;
		margin-top: 0;
		line-height: 60px;
		height: 0;
		overflow: hidden;
}

#main-nav-test:checked ~ .boo {
		height: 50px;
}

.logo {
    float: right;
    font-weight: 800;
    font-size: 1.5rem;
    margin-top: 1vw;
    margin-right: 1vw;
    text-decoration: none;
    color: black;
	position: sticky;
}

.a-header {
		position: relative;
		width: calc(100% - 20px);
		margin: 0;
		min-height: 50px;
		background: #fff;
		overflow: hidden;
        
}

.a-header ul {
		position: relative;
		float: left;
		width: 100%;
		list-style: none;
		margin: 0;
		padding: 0;
}

.a-header ul a {
		position: relative;
		float: left;
		width: 100%;
		height: 0;
		line-height: 50px;
		padding: 0 15px;
		text-decoration: none;
		overflow: hidden;
		color: black;
		text-align: left;
}

.a-header ul a:hover,
.a-header ul a:active,
.a-header ul a:focus,
.a-header ul a:visited {
		text-decoration: none;
		background: #fff;
		border-bottom-color: #08c;
}

#main-nav:checked ~ ul a {
		height: 50px;
}

.a-header a:active {
background: #4F00CF;
}

@media all and (max-width: 576px) {
	h1,h2 {
		font-size: 2rem;
	}
}
</style>