<template>
<section>
	<div class="main-bg" align="center">
		<div class="shadow">
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

		<div class="pb-5"></div>
		
		<div class="col-8 trans rounded py-4 shadow">
			<h3>Aktivasi</h3>
			<hr class="my-4">
			<p>Aktivasi email anda </p>
			<b-form-input type="text" placeholder="Email" class="shadow mb-2"></b-form-input>
			<b-form-input type="text" placeholder="Password Baru" class="shadow mb-2"></b-form-input>
			<hr>
			<br>setelah anda menekan kirim, sistem akan mengirim tautan ke email anda untuk aktivasi
			<hr>
			<b-button block variant="success" class="shadow">Kirim</b-button>
		</div>

		<div class="pb-5"></div>

		<div>
			<div align="center"class="footer shadow">
				<b>Copyrigt 2019</b>
			</div>
		</div>
	</div>
</section>
</template>