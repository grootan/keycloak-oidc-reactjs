# Keycloak - OIDC ReactJS

This repo contains ReactJS example app that demonstrate OpenId Connect's Implicit flow with Keycloak.

## Instructions

1. Clone the Repository
2. RUN `npm install` and wait for the completion of installation on `node_modules`
3. Once `node_modules` are installed and RUN `npm run start` to start execution of `react-scripts`
4. You will receive a localhost URL, open that specific URL in the browser to view your initial screen
5. You can configure your OIDC related information in ```src/model/Config.js``` path
6. Make sure you replace `keycloak-tenant-id` with your TenantID and `keycloak-client-id` with your ClientID.
7. Change `{hostname}` to match your keycloak domain.

### Example

```
Available on:
You can now view keycloak flow started in the browser.

  Local:            http://localhost:3000
  On Your Network:  http://<IP>:3000

Note that the development build is not optimized.
To create a production build, use npm run build.
```

## Approach to work with the implicit flow

1. Click on "login" button
2. You will be redirected to "Keycloak" user authentication screen
3. Complete all authentication steps
4. You will receive Token based on the response type which you configured

## What can I use these for

OpenId Connect is a great way to add user authentication to your application where you are depending on another party to manage the user identities.

In this case Keycloak will manage the identity of your users making it faster to get up and running.

## Single Sign On (SSO)

By implementing OpenId Connect via Keycloak you are creating a session which can be used to single sign on from your custom app into other apps that your users may have access to via the Keycloak portal

If you have any queries / you notice any issues don't hesitate to raise issue.
