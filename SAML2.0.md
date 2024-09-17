Security Markup Lanugage
Federation protocol

Benefits
- Interoperable
* no passwords
* digital signature

Generates assertion (xml doc with auth info)
 - attributes (about a subject)
 - authentication
 - authorization decision

Assertion Consumer Service (ACS)
Assertion MUST be sent to this URL

WIth SP initiated, user hits endpoint that knows to redirect them to IDP

3 Roles:
- end user/principal
- IDP
- SP

To setup a new integration, 
exchagen metadata
- includes entity id's for IDP and SP
- ACS url (Login URL)
- SSO url
- x509 certificate
can copy paste, or upload xml

Binding method
Naming method