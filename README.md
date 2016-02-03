# picbot-deviantart-plugin

A source plugin for twitter-picbot which retrieves sources from DeviantArt API.

## Credentials

You will need to register an account and
an application in it, once you have both, you will get a **clientId** and **clientSecret**,
place them in the root folder of the plugin into **keys.json** file like:

```
{
  "client_id": "client-id",
  "client_secret": "client-secret"
}
```

## Requirements

Make sure the following npm packages are included in your **twitter-picbot** application.

- client-oauth2
- request
