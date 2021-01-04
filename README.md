# Keycloak - OIDC ReactJS

This repository contains a ReactJS example application that demonstrates the implicit flow for OpenID Connect.

## Instructions

1. Clone the Repository
2. RUN `npm install` and wait for the completion of installation of all `node_modules`.
3. Once `node_modules` are installed and RUN `npm run start` to start execution of `react-scripts`.
4. You will receive a localhost URL, open that particular URL in your browser to view your initial screen
5. Configure the OIDC details in the ```src/model/Config.js``` path.
6. Make sure you replace `keycloak-tenant-id` with your TenantID and `keycloak-client-id` with your ClientID.
7. Change `{hostname}` to align your keycloak domain.

### Example

```javascript
Available on:
You can now view keycloak flow started in the browser.

  Local:            http://localhost:3000
  On Your Network:  http://<IP>:3000

Note that the development build is not optimized.
To create a production build, use npm run build.
```

## Approach to work with the implicit flow

1. Click the button for "login".
2. You will be redirected to the user authentication screen of "Keycloak".
3. Complete all of the authentication steps.
4. Depending on the response type you configured, you will receive a token.

## What can I use these for

OpenID Connect is a perfect way to incorporate user authentication to your application, where you are relying on another party to handle user identity.

In this situation, Keycloak handles the identity of the users, allowing it faster to get up and running.

## Single Sign On (SSO)

By integrating OpenID Connect via Keycloak, you are building a session that can be used to single sign-on from your custom app to other applications that your users can access via the Keycloak portal.

If you have any queries / you notice any issues don't hesitate to raise issue.
