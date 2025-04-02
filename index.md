<html>
  <body>
    <script type='text/javascript'>
	function initEmbeddedMessaging() {
		try {
			embeddedservice_bootstrap.settings.language = 'pt_BR'; // For example, enter 'en' or 'en-US'

			embeddedservice_bootstrap.init(
				'00DHa000002CopX',
				'MessagingWebChat',
				'https://momentum-page-4472--devsoteria.sandbox.my.site.com/ESWMessagingWebChat1743429300556',
				{
					scrt2URL: 'https://momentum-page-4472--devsoteria.sandbox.my.salesforce-scrt.com'
				}
			);
		} catch (err) {
			console.error('Error loading Embedded Messaging: ', err);
		}
	};
</script>
<script type='text/javascript' src='https://momentum-page-4472--devsoteria.sandbox.my.site.com/ESWMessagingWebChat1743429300556/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>

  </body>
</html>
