<html>
	<head>
		<meta name="viewport" content="width=device-width, initial-scale=1, minimum-scale=1">

		<title>LiveJasmin</title>		

		<!-- <link rel="stylesheet" type="text/css" href="https://static3.dditscdn.com/jsm2/site/livejasmin/css/main.f4aee.css" /> -->
		<!-- <link rel="stylesheet" type="text/css" href="https://static1.dditscdn.com/jsm2/site/livejasmin/css/controller/staticpage_controller.3a93f.css" /> -->
		<link rel="stylesheet" type="text/css" href="https://static1.dditscdn.com/jsm2/site/livejasmin/css/main.85825.css" />
		
		<style type="text/css">
			.embeddedServiceHelpButton .helpButton .uiButton
			{
				background-color: #f98706 !important;
				font-family: "Arial", sans-serif !important;
			}
			
			.embeddedServiceHelpButton .helpButton .uiButton:focus
			{
				outline: 1px solid #f98706 !important;
			}
		</style>
	</head>
	
	<body id="staticpage.contactus" class="new-listpage layout-basic no-script livejasmin">
		<script type="text/javascript">
			document.body.className=document.body.className.replace("no-script","");var Config={},isAppletFullInited=!1,appInitCalled=!1,appletFullInited=function(){"function"===typeof appInit?appInit():isAppletFullInited=!0};
			xhr=new XMLHttpRequest;xhr.open("GET","https://static2.dditscdn.com/jsm2/site/livejasmin/icomoon/symbol-defs.4f78b.svg",!1);xhr.onload=function(){200===xhr.status&&document.body.appendChild(xhr.responseXML.documentElement)};xhr.send("");
		</script>
		
		<div id="header_container">
			<div id="header">
				<div class="header_1280 env_livejasmin">
					<div class="left_side">
						<a id="logo" href="#" class="livejasmin_logo" target="_top">LiveJasmin - Chat With Both Demonstration</a>
					</div>
				</div>
			</div>
		</div>

		<div id="" data-size="medium" class="grid--medium newLayout"/>
		<br/><br/><br/>
		<div class="content_box" id="contactus">
			<div class="content_box_header">
				<h2>Login Failed - Password is incorrect</h2>
			</div>
			<div class="content_box_container" align="center">
				<div class="content_column_left">
					<!--
					<div class="contact_container" id="choose_contact" >
						<a id="online_support_link" href="?page=online-support" class="contact_content_container">
						<span class="icon online_support">&nbsp;</span>
						<strong>Contact Online Support</strong>
						<small>For immediate online assistance click on chat button</small>
						</a>
					</div>
					-->
					<img src="https://image.flaticon.com/icons/png/512/1000/1000984.png" height="50%"/>
				</div>

				<div class="clear"></div>
			</div>
		</div>

		<script type='text/javascript' src='https://service.force.com/embeddedservice/5.0/esw.min.js'></script>
		<script type='text/javascript'>
			var initESW = function(gslbBaseURL) {
				embedded_svc.settings.displayHelpButton = true; //Or false
				embedded_svc.settings.language = ''; //For example, enter 'en' or 'en-US'

				embedded_svc.settings.defaultMinimizedText = 'Chat with a Bot'; //(Defaults to Chat with an Expert)
				//embedded_svc.settings.disabledMinimizedText = '...'; //(Defaults to Agent Offline)

				//embedded_svc.settings.loadingText = ''; //(Defaults to Loading)
				//embedded_svc.settings.storageDomain = 'yourdomain.com'; //(Sets the domain for your deployment so that visitors can navigate subdomains during a chat session)

				// Settings for Chat
				//embedded_svc.settings.directToButtonRouting = function(prechatFormData) {
					// Dynamically changes the button ID based on what the visitor enters in the pre-chat form.
					// Returns a valid button ID.
				//};
				//embedded_svc.settings.prepopulatedPrechatFields = {}; //Sets the auto-population of pre-chat form fields
				//embedded_svc.settings.fallbackRouting = []; //An array of button IDs, user IDs, or userId_buttonId
				//embedded_svc.settings.offlineSupportMinimizedText = '...'; //(Defaults to Contact Us)

				embedded_svc.settings.enabledFeatures = ['LiveAgent'];
				embedded_svc.settings.entryFeature = 'LiveAgent';

				embedded_svc.init(
					'https://kkakevska-20200113-demo.my.salesforce.com',
					'https://sdodemo-main-166ce2cf6b6-16f9edde2f5.force.com/consumer',
					gslbBaseURL,
					'00D3X000002MNBN',
					'Sunny_Bot',
					{
						baseLiveAgentContentURL: 'https://c.la1-c1-cdg.salesforceliveagent.com/content',
						deploymentId: '5723X000000HDba',
						buttonId: '5733X000000HEKG',
						baseLiveAgentURL: 'https://d.la1-c1-cdg.salesforceliveagent.com/chat',
						eswLiveAgentDevName: 'EmbeddedServiceLiveAgent_Parent04I1N0000004H9WUAU_16b67004022',
						isOfflineSupportEnabled: false
					}
				);
			};

			if (!window.embedded_svc) {
				var s = document.createElement('script');
				s.setAttribute('src', 'https://kkakevska-20200113-demo.my.salesforce.com/embeddedservice/5.0/esw.min.js');
				s.onload = function() {
					initESW(null);
				};
				document.body.appendChild(s);
			} else {
				initESW('https://service.force.com');
			}
		</script>
	</body>
</html>
