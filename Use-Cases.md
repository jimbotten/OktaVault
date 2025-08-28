# 1

****** Result for Image/Page 1 ******
Info
Use Case 1
Use Case 2 Use Case 3 Use Case 4
Important: Please complete the Email Registration task described on the Info tab before starting work on the Use Cases.
First Name
Alexandra
Last Name
Cooper
Username/Email
alexandra.cooper@oktacertified.com
Password
Testme321!
1. Log into your assigned orgl as User Admin, using the credentials provided. Create the Alexandra Cooper account using the table.
2. After you create the account, ensure Alexandra can log in using Testme321! as the password.
3. Create a new read/write attribute with a Display Name of Preferred Name and a variable name of preferredName.
4. Edit Alexandra's Okta Profile and update the following attributes:
• Title: Sales Associate
• Mobile phone: 800-588-1656
• Street address: 1234 Jones Blvd
• City: Oakland
• State: CA
• Zip Code: 89089
• Division: Contractors
• preferredName: Alex
5. Create an Okta group based on the following:
• Name: Contractors
• Group Description: All contractors
6. Using the Division attribute of Contractors, define logic in Okta to filter users with this attribute defined into the Contractors group. Verify Alexandra is added to the Contractors group using this definition. NOTE: She should not be added to the group manually.


# 2

****** Result for Image/Page 1 ******
Info Use Casel Use Case 2
First Name
Mike
Last Name
Smith
Use Case 3
Use Case 4
Username/Email
michael.smith@oktacertified.com
Password
Testme321!
1. As User Admin, deactivate Mike Smith in orgl .
2. Define mappings to push Title, Division, and preferredName from orgl to org2. Click Force Sync on the attribute mapping. Note: If an attribute does NOT exist in org2, create the missing attribute in org2.
3. Once setup, verify the attribute data in orgl is reflected for Alexandra's user account in org2.
4. Using the credentials in the table, verify that Mike CANNOT sign in to orgl .


# 3

****** Result for Image/Page 1 ******
Info
Use Case 1
Use Case 2
Use Case 3
Use Case 4
1. Set Password and Email as Required in the Default Enrollment Policy for Authenticators.
2. In the Global Session Policy, add a new rule to the Default Policy to "Establish the user session" with a password. Name the new rule Password Rule.
3. Define an authentication policy that requires Password and Email if the user is a member of the Contractors Group and is trying to access the Org20rg application. Name the policy Contractors Policy and the rule Contractors Rule. Enable the following settings in the Contracto
Rule
And Prompt for password authentication: When an Okta global session doesn't exist
And Prompt for all other factors: Every time user signs in to resource
4. If you can, use a personal email address to receive the Email verification code. Otherwise, if you are taking this exam on a device that is locked down, you may have to use a work email address. Edit Alexandra's Okta Profile and set her primary email to the email address that you are
using for this step.
5. Log in as Alexandra to verify that she is prompted for an Email Verification upon clicking the Org20rg icon on her Okta dashboard.
6. Complete the login by accessing the email with Alexandra's verification code.


# 4


****** Result for Image/Page 1 ******
Info
Use Case 1
Use Case 2
Use Case 3
Use Case 4
1 . Set up Okta Org20rg using SAML 2.0 as the sign-on method in orgl . In org2, name the Identity Provider IDprov.
Note: Be sure to search for and select the Okta Org20rg application in the Okta Integration Network.
2. Set up Okta Lifecycle Management for the Okta Org20rg application defined in Step 1 . Enable the following to App provisioning options:
• Create Users
Update user Attributes
• Deactivate I-Jsers
Note: For the Security token, use the API Key provided on the Login Info tab.
3. Assign the Contractors group to the Okta Org20rg app. Set the Initial status to active_with_pass.
4. Verify that Alexandra's identity is pushed successfully to org2.
5. Log in to Okta as Alexandra and verify she can access org2 by clicking the Okta Org20rg icon in his Okta Dashboard.
