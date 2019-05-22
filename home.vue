<template>
<section>
	<div class="main-bg" align="center">
		<div class="pb-5"></div>
		<div class="shadow fixed-top">
			<b-navbar toggleable="lg" type="dark" variant="info">
			<b-navbar-brand href="#">LTE Acc</b-navbar-brand>
			<b-navbar-toggle target="nav-collapse"></b-navbar-toggle>
			<b-collapse id="nav-collapse" is-nav>
			<b-navbar-nav>
			<b-nav-item href="#" active>Home</b-nav-item>
			<b-nav-item href="#">profile</b-nav-item>
			</b-navbar-nav>
			<!-- Right aligned nav items -->
			<b-navbar-nav class="ml-auto">
			<b-nav-item-dropdown text="Lang" right>
			<b-dropdown-item href="#">EN</b-dropdown-item>
			<b-dropdown-item href="#">ES</b-dropdown-item>
			<b-dropdown-item href="#">RU</b-dropdown-item>
			<b-dropdown-item href="#">FA</b-dropdown-item>
			</b-nav-item-dropdown>
			<b-nav-item-dropdown right>
			<!-- Using 'button-content' slot -->
			<template slot="button-content"><em>Account</em></template>
			<b-dropdown-item href="#">Profile</b-dropdown-item>
			<b-dropdown-item href="#">Log Out</b-dropdown-item>
			</b-nav-item-dropdown>
			</b-navbar-nav>
			</b-collapse>
			</b-navbar>
		</div>
		<div class="pb-2"></div>
		
		<b-alert show variant="warning">Emailmu belum aktif, aktifkan <a href="">disini</a></b-alert>
		<div class="shadow">
			<b-card
			overlay
			img-src="https://picsum.photos/1024/480/?image=10"
			img-alt="Card Image"
			text-variant="white"
			title="LTE Access"
			img-height="360"
			>
			<b-card-text>
			Some quick example text to build on the card and make up the bulk of the card's content.
			</b-card-text>
			</b-card>
		</div>
		<div class="pb-3"></div>
		<div class="col-10">
			<div class="trans rounded py-4 px-4 shadow mb-3">
				<h3><b>About</b></h3>
				<hr>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
				tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
				quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
				consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse
				cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
				proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
			</div>
			<div class="trans rounded py-4 px-4 shadow mb-3">
				<h3><b>Our Service</b></h3>
				<hr>
				<div class="d-flex justify-content-center">
					<div class="col-3">
						<b-img src="https://img.icons8.com/ios/420/internet.png" fluid alt="Responsive image" width="80" height="80"></b-img>
						<br>
						<br>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
						tempor incididunt ut labore et dolore magna aliqua.
					</div>
					<div class="col-3">
						<b-img src="https://png2.pngtree.com/svg/20160503/b8d074a79c.png" fluid alt="Responsive image" width="80" height="80"></b-img>
						<br>
						<br>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
						tempor incididunt ut labore et dolore magna aliqua.
					</div>
					<div class="col-3">
						<b-img src="http://cdn.onlinewebfonts.com/svg/img_452038.png" fluid alt="Responsive image" width="80" height="80"></b-img>
						<br>
						<br>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
						tempor incididunt ut labore et dolore magna aliqua.
					</div>
				</div>
			</div>
		</div>
		
		<div>
			<div align="center"class="footer shadow">
				<b>Copyrigt 2019</b>
			</div>
		</div>
	</div>
</section>
</template>