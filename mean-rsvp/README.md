# MEAN-RSVP-Auth0

This is the sample repository for the Real-World Angular Series of tutorials. Begin the tutorials here: [Real-World Angular Series - Part 1](https://auth0.com/blog/real-world-angular-series-part-1).

## Requirements

* Node + npm
* Angular CLI

## Install

Clone this repository, then run:

```
$ npm install
```

## Setup

* Add your Auth0 credentials and remove `.SAMPLE`: `server/config.js.SAMPLE`
* Add your Auth0 credentials: `silent.html`
* Add your Auth0 credentials: `src/app/auth/auth.config.ts`

## Development server

```
$ ng serve
$ NODE_ENV=dev nodemon server
```

Available on `http://localhost:4200/`. 

## Build (local)

```
$ ng build --prod
$ node server
```

Available on `http://localhost:8083`.

## Deploy

To prep the app in this repo for production deployment, follow instructions here: [Real-World Angular Series - Part 8](https://auth0.com/blog/real-world-angular-series-part-8/#deploy).

## What is Auth0?

Auth0 helps you to:

* Add authentication with [multiple authentication sources](https://docs.auth0.com/identityproviders), either social like **Google, Facebook, Microsoft Account, LinkedIn, GitHub, Twitter, Box, Salesforce, amont others**, or enterprise identity systems like **Windows Azure AD, Google Apps, Active Directory, ADFS or any SAML Identity Provider**.
* Add authentication through more traditional **[username/password databases](https://docs.auth0.com/mysql-connection-tutorial)**.
* Add support for **[linking different user accounts](https://docs.auth0.com/link-accounts)** with the same user.
* Support for generating signed [Json Web Tokens](https://docs.auth0.com/jwt) to call your APIs and **flow the user identity** securely.
* Analytics of how, when and where users are logging in.
* Pull data from other sources and add it to the user profile, through [JavaScript rules](https://docs.auth0.com/rules).

## Create a Free Auth0 Account

1. Go to [Auth0](https://auth0.com) and click Sign Up.
2. Use Google, GitHub, or Microsoft Account to log in.

## Issue Reporting

If you have found a bug or if you have a feature request, please report them at this repository issues section. Please do not report security vulnerabilities on the public GitHub issue tracker. The [Responsible Disclosure Program](https://auth0.com/whitehat) details the procedure for disclosing security issues.

## Author

[Auth0](auth0.com)

## License

This project is licensed under the MIT license. See the [LICENSE](LICENSE) file for more info.
