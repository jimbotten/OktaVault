copies user profile and group membership over to okta on login
will provision okta user immediately

delegated authentication must be enabled
works for okta users
Importing users is not users

works if using login methods; 
Ad delegated
Desktop SSO
Inbound SAML

Benefits: 
- no need to import, confirm and activate users
- dynamically accomodates AD user profile updates in real time



setup
provisioning tab, to okta
- configure JIT provisioning
- Do not import users