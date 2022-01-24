<script>
	import '../app.css';
</script>

<svelte:head>
	<link
		rel="stylesheet"
		id="wp-block-library-css"
		href="/wp-includes/css/dist/block-library/style.min.css?ver=5.8.3"
		type="text/css"
		media="all"
	/>
	<link
		rel="stylesheet"
		id="avatar-manager-css"
		href="https://studentradio.org.uk/wp-content/plugins/avatar-manager/assets/css/avatar-manager.min.css?ver=1.2.1"
		type="text/css"
		media="all"
	/>
	<link
		rel="stylesheet"
		id="awards-api-css"
		href="https://studentradio.org.uk/wp-content/plugins/awards-api/style.css?ver=5.8.3"
		type="text/css"
		media="all"
	/>
	<link
		rel="stylesheet"
		id="FlexSlider-css"
		href="https://studentradio.org.uk/wp-content/themes/studentradio/shared/lib/FlexSlider/flexslider.css?ver=5.8.3"
		type="text/css"
		media="all"
	/>
	<link
		rel="stylesheet"
		id="bootstrap-css"
		href="https://studentradio.org.uk/wp-content/themes/studentradio/shared/lib/bootstrap/css/bootstrap.min.css?ver=3.3.6"
		type="text/css"
		media="all"
	/>
	<link
		rel="stylesheet"
		id="sra-font-css"
		href="https://studentradio.org.uk/wp-content/themes/studentradio/shared/lib/sra-font/style.css?ver=5.8.3"
		type="text/css"
		media="all"
	/>
	<link
		rel="stylesheet"
		id="fontawesome-css"
		href="https://studentradio.org.uk/wp-content/themes/studentradio/shared/lib/font-awesome-4.6.3/css/font-awesome.min.css?ver=4.6.2"
		type="text/css"
		media="all"
	/>
	<link
		rel="stylesheet"
		href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css"
		integrity="sha512-Fo3rlrZj/k7ujTnHg4CGR2D7kSs0v4LLanw2qksYuRlEzO+tcaEPQogQ0KaoGN26/zrn20ImR1DfuLWnOo7aBA=="
		crossorigin="anonymous"
		referrerpolicy="no-referrer"
	/>
	<link
		rel="stylesheet"
		id="bootstrap-slider-css"
		href="https://studentradio.org.uk/wp-content/themes/studentradio/shared/lib/bootstrap-slider/bootstrap-slider.css?ver=5.8.3"
		type="text/css"
		media="all"
	/>
	<link
		rel="stylesheet"
		id="theme-style-css"
		href="https://studentradio.org.uk/wp-content/themes/studentradio/association/css/style.css?ver=3"
		type="text/css"
		media="all"
	/>
	<link
		rel="stylesheet"
		id="hacky-jonty-css"
		href="https://studentradio.org.uk/wp-content/themes/studentradio/association/jonty-hacky-styles.css?ver=5.8.3"
		type="text/css"
		media="all"
	/>
	<link
		rel="stylesheet"
		id="royalslider-css"
		href="https://studentradio.org.uk/wp-content/themes/studentradio/shared/lib/cc-royalslider-9.2.0/royalslider/royalslider.css?ver=5.8.3"
		type="text/css"
		media="all"
	/>
	<link
		rel="stylesheet"
		id="rs-minimal-white-css"
		href="https://studentradio.org.uk/wp-content/themes/studentradio/shared/lib/cc-royalslider-9.2.0/royalslider/minimal-white/rs-minimal-white.css?ver=5.8.3"
		type="text/css"
		media="all"
	/>
	<link
		rel="stylesheet"
		id="jetpack_css-css"
		href="https://studentradio.org.uk/wp-content/plugins/jetpack/css/jetpack.css?ver=7.5.2"
		type="text/css"
		media="all"
	/>
	<link
		rel="stylesheet"
		id="googleFonts-css"
		href="//fonts.googleapis.com/css?family=Raleway%3A100%2C200%2C300%2C400%2C500%2C600%7COpen+Sans%3A400%2C600%2C700&#038;ver=5.8.3"
		type="text/css"
		media="all"
	/>
	<link
		rel="stylesheet"
		href="https://studentradio.org.uk/wp-content/plugins/fred-bradley-helper-plugin/socialcount/socialcount-with-icons.css"
	/><link
		rel="stylesheet"
		href="https://studentradio.org.uk/wp-content/plugins/fred-bradley-helper-plugin/socialcount/socialcount-icons.css"
	/>
	<link
		rel="stylesheet"
		href="https://studentradio.org.uk/wp-content/plugins/wordpress-23-related-posts-plugin/static/themes/twocolumns.css?version=3.6.4"
	/>
	<link
		rel="stylesheet"
		href="https://studentradio.org.uk/wp-content/themes/studentradio/association/inc/widgets/countdown/mb-comingsoon.min.css"
		type="text/css"
	/>
</svelte:head>
<div>
	<header id="masthead" class="site-header max-h-64" role="banner">
		<div class="container container-header max-h-full">
			<div class="row max-h-full">
				<div class="col-sm-4 site-logo">
					<a rel="external" href="/">
						<img
							class="img-responsive max-h-64"
							src="https://studentradio.org.uk/wp-content/themes/studentradio/association/img/logo.png"
							alt="Student Radio Association"
						/>
					</a>
				</div>
				<div id="top-adsense" class="col-sm-8" style="text-align: right" />
			</div>
		</div>
	</header>

	<section class="global-nav">
		<span id="the_nav_bars">
			<div class="container">
				<nav class="navbar navbar-default sra-main-nav" role="navigation">
					<div class="navbar-header">
						<button
							type="button"
							class="navbar-toggle"
							data-toggle="collapse"
							data-target="#main-site-navigation"
						>
							<span class="sr-only">Toggle navigation</span>
							<span class="icon-bar" />
							<span class="icon-bar" />
							<span class="icon-bar" />
						</button>
					</div>

					<div class="collapse navbar-collapse sra-nav-collapse" id="main-site-navigation">
						<ul id="menu-primary-navigation" class="nav navbar-nav">
							<li
								id="menu-item-4561"
								class="menu-item menu-item-type-custom menu-item-object-custom menu-item-4561"
							>
								<a rel="external" title="Home" href="/"
									><i class="fa fa-home" style="display: inline" />&nbsp;Home</a
								>
							</li>
							<li
								id="menu-item-4910"
								class="menu-item menu-item-type-post_type menu-item-object-page menu-item-has-children menu-item-4910 dropdown"
							>
								<a
									rel="external"
									title="About"
									href="#"
									data-toggle="dropdown"
									class="dropdown-toggle"
									aria-haspopup="true"
									><i class="fa fa-info-circle" style="display: inline" />&nbsp;About
									<span class="caret" /></a
								>
								<ul role="menu" class="dropdown-menu">
									<li
										id="menu-item-4911"
										class="menu-item menu-item-type-post_type menu-item-object-page menu-item-4911"
									>
										<a rel="external" title="About the SRA" href="/about/">About the SRA</a>
									</li>
									<li
										id="menu-item-8505"
										class="menu-item menu-item-type-post_type menu-item-object-page menu-item-8505"
									>
										<a rel="external" title="Partnerships &#038; Support" href="/support/"
											>Partnerships &#038; Support</a
										>
									</li>
									<li
										id="menu-item-4980"
										class="menu-item menu-item-type-post_type menu-item-object-page menu-item-4980"
									>
										<a rel="external" title="Join The SRA" href="/about/join-the-sra/"
											>Join The SRA</a
										>
									</li>
									<li
										id="menu-item-7504"
										class="menu-item menu-item-type-post_type menu-item-object-page menu-item-7504"
									>
										<a rel="external" title="SRA Officers" href="/connect/officers/">SRA Officers</a
										>
									</li>
									<li
										id="menu-item-4981"
										class="menu-item menu-item-type-post_type menu-item-object-page menu-item-4981"
									>
										<a
											rel="external"
											title="Honorary Life Members"
											href="/about/honorary-life-members/">Honorary Life Members</a
										>
									</li>
									<li
										id="menu-item-4958"
										class="menu-item menu-item-type-post_type menu-item-object-page menu-item-4958"
									>
										<a rel="external" title="Governance" href="/about/governance/">Governance</a>
									</li>
									<li
										id="menu-item-4960"
										class="menu-item menu-item-type-post_type menu-item-object-page menu-item-4960"
									>
										<a rel="external" title="Company Documentation" href="/about/documentation/"
											>Company Documentation</a
										>
									</li>
								</ul>
							</li>
							<li
								id="menu-item-6819"
								class="menu-item menu-item-type-post_type menu-item-object-page menu-item-has-children menu-item-6819 dropdown"
							>
								<a
									rel="external"
									title="News &amp; Jobs"
									href="#"
									data-toggle="dropdown"
									class="dropdown-toggle"
									aria-haspopup="true"
									><i class="fa fa-newspaper-o" style="display: inline" />&nbsp;News &#038; Jobs
									<span class="caret" /></a
								>
								<ul role="menu" class="dropdown-menu">
									<li
										id="menu-item-6821"
										class="menu-item menu-item-type-post_type menu-item-object-page menu-item-6821"
									>
										<a rel="external" title="SRA News" href="/news/">SRA News</a>
									</li>
									<li
										id="menu-item-6820"
										class="menu-item menu-item-type-post_type menu-item-object-page menu-item-6820"
									>
										<a rel="external" title="Industry News" href="/news/industry/">Industry News</a>
									</li>
									<li
										id="menu-item-10542"
										class="menu-item menu-item-type-post_type menu-item-object-page menu-item-10542"
									>
										<a rel="external" title="Jobs" href="/news/jobs/">Jobs</a>
									</li>
									<li
										id="menu-item-11174"
										class="menu-item menu-item-type-taxonomy menu-item-object-category menu-item-11174"
									>
										<a rel="external" title="Technology" href="/category/technology/">Technology</a>
									</li>
								</ul>
							</li>
							<li
								id="menu-item-5004"
								class="menu-item menu-item-type-post_type menu-item-object-page menu-item-5004"
							>
								<a rel="external" title="Awards" href="/awards/"
									><i class="fa fa-trophy" style="display: inline" />&nbsp;Awards</a
								>
							</li>
							<li
								id="menu-item-7853"
								class="menu-item menu-item-type-post_type menu-item-object-page menu-item-7853"
							>
								<a rel="external" title="Conference" href="/conference/"
									><i class="fa fa-graduation-cap" style="display: inline" />&nbsp;Conference</a
								>
							</li>
							<li
								id="menu-item-10801"
								class="menu-item menu-item-type-custom menu-item-object-custom menu-item-has-children menu-item-10801 dropdown"
							>
								<a
									rel="external"
									title="Music"
									href="#"
									data-toggle="dropdown"
									class="dropdown-toggle"
									aria-haspopup="true">Music <span class="caret" /></a
								>
								<ul role="menu" class="dropdown-menu">
									<li
										id="menu-item-10800"
										class="menu-item menu-item-type-post_type menu-item-object-page menu-item-10800"
									>
										<a rel="external" title="SRA Music" href="/music/">SRA Music</a>
									</li>
									<li
										id="menu-item-11383"
										class="menu-item menu-item-type-post_type menu-item-object-page menu-item-11383"
									>
										<a rel="external" title="SRA Playlist" href="/music/sra-playlist/"
											>SRA Playlist</a
										>
									</li>
									<li
										id="menu-item-11621"
										class="menu-item menu-item-type-post_type menu-item-object-post menu-item-11621"
									>
										<a rel="external" title="SRA Class of 2020" href="/2019/11/sra-class-of-2020/"
											>SRA Class of 2020</a
										>
									</li>
									<li
										id="menu-item-10802"
										class="menu-item menu-item-type-taxonomy menu-item-object-category menu-item-10802"
									>
										<a rel="external" title="Music News" href="/category/music/">Music News</a>
									</li>
									<li
										id="menu-item-7028"
										class="menu-item menu-item-type-post_type menu-item-object-page menu-item-7028"
									>
										<a rel="external" title="Chart Show" href="/chart/">Chart Show</a>
									</li>
								</ul>
							</li>
							<li
								id="menu-item-4982"
								class="more test menu-item menu-item-type-custom menu-item-object-custom menu-item-4982"
							>
								<a rel="external" title="Stations" href="/stations"
									><i class="fa fa-rss" style="display: inline" />&nbsp;Stations</a
								>
							</li>
							<li
								id="menu-item-7425"
								class="menu-item menu-item-type-post_type menu-item-object-page menu-item-7425"
							>
								<a rel="external" title="Contact" href="/contact/"
									><i class="fa fa-comments-o" style="display: inline" />&nbsp;Contact</a
								>
							</li>
						</ul>
						<ul class="nav navbar-nav navbar-right" style="display: none">
							<li style="display: none">
								<a rel="external" href="#" data-toggle="modal" data-target="#modal-login"
									><i class="fa fa-fw fa-user" /> Login / Register</a
								>
							</li>
						</ul>
					</div>
				</nav>
			</div>
		</span>
	</section>
</div>
<div id="main" class="site-main min-h-[calc(100vh-350px)]">
	<style>
		.homepage .unit-feature {
			position: relative;
			padding-bottom: 10px;
		}
		.homepage .unit-feature:not(:last-child) {
			border-bottom: 1px solid #ddd;
		}
		.homepage .unit-feature .unit-title {
			line-height: 1.2em;
			height: 3.6em;
			white-space: normal;
		}
		.homepage .unit-feature .meta {
			position: absolute;
			bottom: 8px;
		}
		.sliderContainer .rsGCaption {
			color: #000000 !important;
		}
	</style>
	<div class="container homepage">
		<div id="primary" class="content-area">
			<div class="row min-h-full">
				<slot />
				<div class="col-md-4">
					<div id="secondary" class="well well-sm" role="complementary">
						<a rel="external" side id="mailchimp" class="widget">
							<div class="row">
								<div class="col-md-12">
									<form
										action="//studentradio.us3.list-manage.com/subscribe/post?u=a16dccc207ae079564e01a9b1&amp;id=287395c00d"
										method="post"
										id="mc-embedded-subscribe-form"
										name="mc-embedded-subscribe-form"
										class="validate"
										role="form"
										target="_blank"
										novalidate
									>
										<h3><i class="fa fa-envelope" /> Subscribe</h3>
										<p>Receive our weekly mailing list.</p>
										<div class="form-group">
											<div class="col-xs-8 text-input">
												<input
													type="email"
													value=""
													placeholder="Email Address"
													name="EMAIL"
													class="form-control input-lg required email"
													id=""
												/>
											</div>
											<div class="col-xs-4 submit-input">
												<input
													type="submit"
													value="Submit"
													name="Confirm"
													id="mc-embedded-subscribe"
													class="input-lg form-control button btn btn-success"
												/>
											</div>
										</div>
										<div id="mce-responses" class="clear">
											<div class="response" id="mce-error-response" style="display: none" />
											<div class="response" id="mce-success-response" style="display: none" />
										</div>
										<div class="clear" />
									</form>
								</div>
							</div>

							<a rel="external" side id="social" class="widget">
								<div class="row">
									<div class="col-md-12">
										<style>
											#twitter-icon.fixed {
												position: fixed;
												top: 10px;
											}
										</style>
										<div id="twitter-icon" class="social-icon">
											<p style="margin: 0 0 -5px">
												<a
													rel="external"
													class="twitter-timeline"
													height="400"
													width="100%"
													data-chrome="noheader noborders nofooter"
													href="https://twitter.com/SRA"
													data-widget-id="506830386756734976">Tweets by @SRA</a
												>
											</p>
										</div>
									</div>
								</div>
							</a></a
						>
					</div>
				</div>
			</div>
		</div>
	</div>
</div>
<footer id="colophon" class="site-footer min-h-[12rem]" role="contentinfo">
	<div class="container container-footer">
		<div class="site-info pull-left">
			<p>
				&copy; 2022 The Student Radio Association Ltd<br />
				<small
					>Registered in England and Wales as a Company Limited by Guarantee, No. 12182816</small
				><br />
			</p>

			<div class="btn-group">
				<a rel="external" href="/credits" class="btn btn-xs btn-default">Credits</a>
				<a rel="external" href="/legal" class="btn btn-xs btn-default">Legal</a>
			</div>
		</div>
		<div class="back-to-top pull-right">
			<a
				rel="external"
				target="_blank"
				href="https://www.facebook.com/studentradio"
				class="btn btn-large btn-link social-link facebook"
				><i class="fa-brands fa-fw fa-facebook fa-3x" /></a
			>
			<a
				rel="external"
				target="_blank"
				href="https://www.twitter.com/sra"
				class="btn btn-large btn-link social-link twitter"
				><i class="fa-brands fa-fw fa-twitter fa-3x" /></a
			>
			<a
				rel="external"
				target="_blank"
				href="https://www.instagram.com/studentradioassociation"
				class="btn btn-large btn-link social-link instagram"
				><i class="fa-brands fa-fw fa-instagram fa-3x" /></a
			>

			<a
				rel="external"
				target="_blank"
				href="https://www.youtube.com/StudentRadioUK"
				class="btn btn-large btn-link social-link youtube"
				><i class="fa-brands fa-fw fa-youtube fa-3x" /></a
			>
		</div>
	</div>
</footer>
