
Passwords alone are inadequate for modern threats
MFA is not convenience

Assurance uses many factors to ensure the identity
1 or more authenticators, and the characteristics of the authenticators

Authenticators act as a filter

Remediation of data from users can be enforced
Including [[MFA]] can encourange assurance 

Assuance level
- Low - password, security question, any single factor auth (OTP)
- Medium - 2 factors password + mobile app OTP, or password + mobile push
- High - phishing resistant (password+webauthn with biometric, verify OTP+webauthn)



[[[Global Session Policy]] and [[AuthN Policy]] must be met to grant the *assurance level*
OID policies such as [[Enrollment policy]] and [[Password policy]] work with assurance as well.

You can require the factors  with [[SignOn Policy]]

