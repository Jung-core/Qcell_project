<template>
	<!--Login wrap st---->
	<div id="loginWrap">
		<div class="loginbox">
				<div class="loginin_bx">
						<h1>
								クリーンエネルギーで人類の暮らしに貢献する企業、
								<i><img src="../assets/images/common/logo_w_kr.png"></i>
						</h1>
						<ul>
								<li>
										<h3>電子発注システムログイン</h3>
								</li>
								<li class="login_clear">
										<input type="text" class="login block" placeholder="アイディー">
										<label class="form-control-clear icon-remove hidden"></label>
								</li>
								<li class="has-clear">
										<input type="password" class="block" placeholder="パスワード">
										<label></label>
								</li>
								<li class="mt5"><input type="checkbox" id="remember"><label for="remember">ID保存</label></li>
								<li class="mt5"><router-link to="/main">ログイン</router-link></li>
								<li class="copy">登録していないIDか、もしくは間違ったパスワードで.</li>
						</ul>
						<p>IDまたはパスワードを紛失した場合は、担当営業マンにお問い合わせください.</p>
				</div>
		</div>
	</div>
</template>