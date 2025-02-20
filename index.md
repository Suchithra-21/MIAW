<html>
<body>
<script type='text/javascript'>
	function initEmbeddedMessaging() {
		try {
			embeddedservice_bootstrap.settings.language = 'en_US'; // For example, enter 'en' or 'en-US'

			embeddedservice_bootstrap.init(
				'00DEX0000000B57',
				'ALLAgents_MIAW_Flow_PreChat_Bot',
				'https://schedulerorg.perf2n.my.pc-rnd.site.com/ESWALLAgentsMIAWFlowPr1739886204213',
				{
					scrt2URL: 'https://schedulerorg.perf2n.my.pc-rnd.salesforce-scrt.com'
				}
			);
		} catch (err) {
			console.error('Error loading Embedded Messaging: ', err);
		}
	};
</script>
<script type='text/javascript' src='https://schedulerorg.perf2n.my.pc-rnd.site.com/ESWALLAgentsMIAWFlowPr1739886204213/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>
</body>
</html>
