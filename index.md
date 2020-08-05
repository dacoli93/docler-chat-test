<html>
	<head>
		<meta name="viewport" content="width=device-width, initial-scale=1, minimum-scale=1">

		<title>LiveJasmin</title>		

		<!-- <link rel="stylesheet" type="text/css" href="https://static3.dditscdn.com/jsm2/site/livejasmin/css/main.f4aee.css" /> -->
		<!-- <link rel="stylesheet" type="text/css" href="https://static1.dditscdn.com/jsm2/site/livejasmin/css/controller/staticpage_controller.3a93f.css" /> -->
		<link rel="stylesheet" type="text/css" href="https://static1.dditscdn.com/jsm2/site/livejasmin/css/main.85825.css" />
		
		<style type='text/css'>
	.embeddedServiceHelpButton .helpButton .uiButton {
		background-color: #005290;
		font-family: "Arial", sans-serif;
	}
	.embeddedServiceHelpButton .helpButton .uiButton:focus {
		outline: 1px solid #005290;
	}
</style>

<script type='text/javascript' src='https://service.force.com/embeddedservice/5.0/esw.min.js'></script>
<script type='text/javascript'>
	var initESW = function(gslbBaseURL) {
		embedded_svc.settings.displayHelpButton = true; //Or false
		embedded_svc.settings.language = ''; //For example, enter 'en' or 'en-US'

		//embedded_svc.settings.defaultMinimizedText = '...'; //(Defaults to Chat with an Expert)
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
			'https://eu13.salesforce.com',
			'https://oranumpilot.secure.force.com/chattest',
			gslbBaseURL,
			'00D2X000000t0ed',
			'Chat_Deployment',
			{
				baseLiveAgentContentURL: 'https://c.la1-c2-frf.salesforceliveagent.com/content',
				deploymentId: '5722X0000008gu3',
				buttonId: '5732X0000008hGj',
				baseLiveAgentURL: 'https://d.la1-c2-frf.salesforceliveagent.com/chat',
				eswLiveAgentDevName: 'EmbeddedServiceLiveAgent_Parent04I2X000000TalyUAC_173bf020b7f',
				isOfflineSupportEnabled: false
			}
		);
	};

	if (!window.embedded_svc) {
		var s = document.createElement('script');
		s.setAttribute('src', 'https://eu13.salesforce.com/embeddedservice/5.0/esw.min.js');
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
