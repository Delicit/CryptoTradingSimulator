since i could not find free API's for everyone, you have to have bybit account, create read-only API, and then maybe you can experiment with this, i actually dont really know actual required permissions, maybe api only without basically anything, for myself i've decided on everything exept account info, and when it requires - paste keys into console. If there is no question about bybit api - create appsettings.json, with this:

{
  "BybitApi": {
    "ApiKey": "yourkey",
    "SecretKey": "yourkey"
  }
}
you can download .rar or just files, if second -
also create folders (same hierarchy as written) - 
1)runtimes
2)browser
3)lib
4)net8.0
and put there System.Text.Encodings.Web in last folder
