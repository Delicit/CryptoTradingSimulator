you have to have bybit account, create read-only API, allow it to see everything except your account info (maybe you can experiment with this, i actually dont really know actual required permissions, maybe api only without basically anything, and when it required paste in into console. If not - create appsettings.json, with this:

{
  "BybitApi": {
    "ApiKey": "yourkey",
    "SecretKey": "yourkey"
  }
}