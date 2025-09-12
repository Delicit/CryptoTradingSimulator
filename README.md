since i could not find free API's for everyone, you have to have bybit account, create read-only API, and then maybe you can experiment with this, i actually dont really know actual required permissions, maybe api only without basically anything, for myself i've decided on everything exept account info, and when it requires - paste keys into console. If there is no question about bybit api - create appsettings.json, with this:

{
  "BybitApi": {
    "ApiKey": "yourkey",
    "SecretKey": "yourkey"
  }
}
