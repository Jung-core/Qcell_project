<template>
	<!--header st-->
	<header>
		<div class="toputill">
			<span class="user"><img src="../assets/images/common/log_out.png">ハンファＱセルズジャパン</span>
			<a href="#a" class="log-btn">Logout</a>
		</div>
		<nav>
			<h1 class="logo">
				<router-link to="/main"><img src="../assets/images/common/logo.png"><span class="ml11" style="vertical-align: 7px;">E-Order System</span></router-link></h1>
			<ul id="gnb">
					<li><router-link to="/main">Dashboard</router-link></li>
					<li>
						<router-link to="/sub">見積書管理</router-link>
						<ul class="submenu">
							<li><router-link to="/sub">発注状況照会</router-link></li>
							<li><a href="#a">発注書登録</a></li>
							<li><a href="#a">発注書大量登録</a></li>
						</ul>
					</li>
					<li>
						<a href="#a">発注書管理</a>
						<ul class="submenu">
							<li><a href="#a">発注状況照会</a></li>
							<li><a href="#a">発注書登録</a></li>
						</ul>
					</li>
					<li>
						<a href="#a">未払い金照会</a>
						<ul class="submenu">
							<li><a href="#a">発注状況照会</a></li>
							<li><a href="#a">発注書登録</a></li>
							<li><a href="#a">発注書大量登録</a></li>
							<li><a href="#a">発注書大量登録</a></li>
						</ul>
					</li>
					<li>
						<a href="#a">お知らせ</a>
						<ul class="submenu">
							<li><a href="#a">発注書大量登録</a></li>
						</ul>
					</li>
			</ul>
		</nav>
	</header>
	<!--header ed-->
</template>