# auth0-node-passwordless-sample

This sample will show how to use passwordless authentication within a Node.js Regular Web App.

## Key Features

Passwordless scenarios on this Regular Page App samples include:

* Login with a **one time code** via **sms** using **Lock**
* Login with a **one time code** via **email** using **Lock**
* Login with a **magic link** via **email** using **Lock**
* Login with a **Guardian**  using **Lock**
* Login with a **one time code** via **sms** using your **own UI**
* Login with a **one time code** via **email** using your **own UI**
* Login with a **magic link** via **email** using your **own UI**
* Login with a **Guardian** using your **own UI**

You can read more about Passwordless Authentication on our [Doc's Site](https://auth0.com/docs/connections/passwordless), where you will find the complete Regular Web App tutorials for:

* [Authenticate users with a one time code via SMS](https://auth0.com/docs/connections/passwordless/regular-web-app-sms)
* [Authenticate users with a one time code via Email](https://auth0.com/docs/connections/passwordless/regular-web-app-email-code)
* [Authenticate users with a magic link via Email](https://auth0.com/docs/connections/passwordless/regular-web-app-email-link)
* [Authenticate users with Guardian](https://auth0.com/docs/connections/passwordless/guardian)

## Install Locally

In order to run the example locally you would need to:

1. Add a .env file containing your Auth0 credentials. You can use sample.env as template. You can get the clientId, clientSecret and domain from the [Auth0 Dashboard](https://manage.auth0.com).
2. Add `http://localhost:3000/callback` to your App's list of **Allowed Callback URLs** within the [Auth0 Dashboard](https://manage.auth0.com). 
3. Install Node.js v4.0.0 or later
4. Run:

	```
	npm install 
	npm run start
	```

5. Go to http://localhost:3000 and you'll see the app running :).

## Usage

Go to http://localhost:3000 and press the button that corresponds to the feature you want to try. Then follow the login instructions. Once you are logged in, you will see your profile details, and you can logout using the link on the top right corner.

## What is Auth0?

Auth0 helps you to:

* Add authentication with [multiple authentication sources](https://docs.auth0.com/identityproviders), either social like **Google, Facebook, Microsoft Account, LinkedIn, GitHub, Twitter, Box, Salesforce, amont others**, or enterprise identity systems like **Windows Azure AD, Google Apps, Active Directory, ADFS or any SAML Identity Provider**.
* Add authentication through more traditional **[username/password databases](https://docs.auth0.com/mysql-connection-tutorial)**.
* Add support for **[linking different user accounts](https://docs.auth0.com/link-accounts)** with the same user.
* Support for generating signed [Json Web Tokens](https://docs.auth0.com/jwt) to call your APIs and **flow the user identity** securely.
* Analytics of how, when and where users are logging in.
* Pull data from other sources and add it to the user profile, through [JavaScript rules](https://docs.auth0.com/rules).

## Create a free Auth0 Account

1. Go to [Auth0](https://auth0.com) and click Sign Up.
2. Use Google, GitHub or Microsoft Account to login.

## Issue Reporting

If you have found a bug or if you have a feature request, please report them at this repository issues section. Please do not report security vulnerabilities on the public GitHub issue tracker. The [Responsible Disclosure Program](https://auth0.com/whitehat) details the procedure for disclosing security issues.

## Author

[Auth0](auth0.com)

## License

This project is licensed under the MIT license. See the [LICENSE](LICENSE) file for more info.
