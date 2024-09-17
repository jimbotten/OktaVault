[!Which type of okta group can include users from varius sources such as okta sources, di sources, app sources?]-
	okta group
[!When an AD group is impored into OKta, the Okta admin has the ability to make membership changes to this grou pin okta and these are synchronized back to the source directory]-
	False
[!What happens when a group rule in okta is deactivated?]-
	The rule stops adding new users to the group but does not remove existing users
[!Group rules are case-sensitive only for certain attributes in okta]-
	False
[!How does Okta allow you to login to legacy apps?]-
	SWA and the browser plugin
[!What Federation Standards does Okta Support]-
	OIDC, SAML, WS-Fed
[!What is the easiest way to confiugre salesforce for SAML SSO?]-
	upload metadata xml file
[!How does salesforce get the x.509 certificate?]-
	Uploaded in the metadata XML file
[!What is a broswer requirement for using SWA?]-
	Okta Browser Plugin
[!What does SWA Mean?]]-
	Secure Web Authentication
[!A common issue is that users haven't trusted their account in the plugin]-
	True
[!What plugin options can a user enable?]-
	- Prompt to save apps to your okta dashboard
	X Auto-launch the app (Not this)
	- Disable browser password prompts
	- Recommend strong passwords
[!Where does Okta store credentials used by the plugin]-
	Okta hosted database encrypted with AES-256
[!Which URIs does okta require for OIDC?]-
	- Redirect URI
	- Initiate Login URI
[!The user can initiate the login using okta dashboard or wordpress]-
	True
[!Which claim is required for OIDC?]-
	openid
[!What application types are supported by AIW?]-
	- SAML
	- OIDC
	- SWA
[!For more complex SWA apps or SAML 1.1 apps you would use a template instead of AIW]- 
	TRUE
[!Where can you find the IdP metadata for an Okta SAML app?]- 
	Under SAML Signing Certs
	The Metadata URL under SAML 2.01
[!What app types can be selected for OIDC?]-
	- Web app - Server side app with auth and tokens handled on server
	- Single Page App - run in broswer where client receives tokens (js, angular, react, vue)
	- Native Desktop/mobile app run on device and redirect to non-http callback
[!Which pieces of information do you need to configure your custom OIDC app in the okta.env file?]-
	- okta client id
	- okta org URL
	- client secret
[!SCIM is a standard Okta leveragfes to automatically exchange user identity info with a service provider]-
	True
[!Which strategies are offererb by Okta to perform provisioning operations on downstream applications?]-
	- API Based
	- Agent Based
[!Who determines whether an applciation supports provisioning features?]- 
	Application service provider
[!When Okta Lifecycle Management (Provisioning) is enabled for a supproted app, all previsously assigned users are provisiong into the app]-
	False
[!Okta User Profile starts with 31 attrs, 4 of which are required to create a new account in Okta]-
	True
[!The variable name is what is used to map data from one profile to another and cannot contain symbols or spaces]-
	True
[!Okta can automatically detect and adjust the priority of the applications being used as a source of truth]-
	False
[!You can connect more than one external application to use as a source of truth with Okta]-
	True
[!How does Okta ThreatInsight work?]-
	- It helps protect customers from credential-based attacks
	- It monitors all authentications across Okta's network
[!Default API rate limits may vary depending on the specific endpoint URI being accessed]-
- True
[!What is the purpose of setting up Network Zones in Okta?]-
	To create geographic restrictions for user access
	To control access to specific resources based on IP Address
[!An IP Zone is used to define a range of gateway or proxy IPs while a Synamic Zone defines a zone by country region ASN or IP type?]-
- True
[!Okta requires assurance levels are satisfied before it allows the end user to access an app. The Assurance levels are specified in]- 
	Global session policies
	Authentication policies
[!Which is an example of authenitcator method with device bound and hardware protected characteristivs]-
	Okta Verify Push
[!What is assurance in the context of Okta's Security Policy Framework?]-
	The level of confidence in the security needs of a system
[!What determines the order in which policies or rules are evaluated for a context match in Okta?]-
	The priority assigned to each policy or rule
[!The Okta Admin has seup an authenticator (MFA) challenge when any user signs into Okta from any location. If an authenticaotr enrollment policy is not created, the default policy will force authenticator enrollment during the Okta sign-on flow.]-
	True
[!Which is the purpose of an authenticator enrollment policy?]-
	Controls how end users enroll in authenticators
	Determines which authenticators are optional to setup
[!Preset authentication policies are only available for certain types of applications]-
	False
[!Which of the following statement is correct about authentication policies?]-
	Only evaluated if a valid Okta session already exists
[!What does the Global session policy control in Okta?]-
	The duration of a session
[!Global session policies are evaluated after authentication policies]-
	False
[!What settings can administrators configure in the password policy in Okta Identity Engine?]-
	- Password complexity and length requirements
	- Self-service recovery options
[!All the self-service recovery authenticators can be used for authentication]-
	True
[!Passwordless authentication can be implemented for our Workforce Identity users with: ]-
	- Webauthn
	- Device Trust
	- Okta Fastpass
[!Select the WebAuthn-enabled authenticatos]-
	- Windows Hello
	- IOS Touch ID
	- YubiKey
[!Passwordless authentication should be deployed after completing this technical process]-
	Require enroll in MFA
[!BEFORE Okta Device Context can be leveraged to manage your devices you must FIRST:]-
	Create enrollment policy to prompt your users to enroll their devices in okta verify
	Set okta verify as an authenticator for your users
[!Managed device means that:]-
	This device has been configured and managed by a device management solution
	Device used to enroll in Verify
	Device is registered in Universal Directory
[!This Okta access control feature can integrate with decvice management solutions to collect data for application sign on poliy to allow step up or deny access for any device]-
	Device Trust
[!WHen users sing in to Okta FastPass with Okta Verify the default user verification for biometrics is ]- 
	preferred
[!When you select the Show the "sign in with okta fastpass" button checkbox in the okta fastpass sign-in page option, okta will: ]
	present a backup if okta verify does not load
	wwalk first-time users through installing okta verify
	offer an alternative for users whos configurations do not allow the silent sign on
[!The order of passwordless authentication rollout best practice:]-
	Configure Global Session Policy
	Enroll users in okta verify
	Configure auth policy
	enable fastpass
[!Only one Okta AD Agent can be installed per AD domain]-
	False
[!The Okta AD Agent must be installed on a Domain Controller]- 
	False
[!JIT Provisioning is enabled by default in Okta]- 
	false
[!JIT Provisioning does not require delegated authentication]-
	false
[!Why are mathing rules important]-
	A user can be modified form multiple profile sources
[!Matching rules cannot provide automatic confirmation for updated users]-
	False
[!Installing multiple AD Agents in close geographical proximity enhances performance: ]-
	False
[!If my AD deployment has 30-100k users how many agents shoudl be deployed]-
	3
[!Okta can only integrate with OpenLDAP]-
	False
[!Okta must import from LDAP as JIT is only availabel with AD]-
	False
[!Branding provides an alternative to setting up multiple Okta orgs, which can require higher maintenance]-
	False
[!Okta email notifications are available as customizable templates in every language]-
	False
[!The Features page allows super admins to bypass okta support and enable self-service early access and beta featuers for their org]-
	True
[!Super Admins can only grant okta support access for 4 hours]-
	False
[!What is a reason for a Yellow Degredation status for agents]-
	Fail-over agent not configured
	agent requires upgrade
	one of more agents are down
[!Match]-
	App accounts need de-provisioning: To-do
	App can be updated to use provisioning: Info
	agent down: Error
[!Order of steps to view a current assignments report]
	Open he reports page
	set parameters for the report
	click request report
	wait for the email
	click download in the email
	view the csv file