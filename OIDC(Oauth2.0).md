This is a [[Federation]] protocol

Requires
- redirect URI
- Initiate Login URI

During setup you pass client id and secret to the app

This protocol supports attribute mapping so you can send a named value to an app based on an attribute in the [[User profiles]]
You can configure what claims are sent in the assertion in auth server
"sub" is short for subject, and it sends the application username, so be sure to map the appropriate username there

Several flows to login:
- [[OAuth 2 Authorization Code Grant Flow]]