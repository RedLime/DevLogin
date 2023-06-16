You can use your Azure Client for Microsoft account authentication with `--azureClient` argument.

Usually, using the default Client works just fine, but if it doesn't work or you don't want to use it, you can process this.

## Steps
1. Go to https://portal.azure.com/ and sign in.
2. Click to `Azure Active Directory`.
3. Process `App registration`.
   - ![](https://i.imgur.com/ehLV7IG.png)
      1. Support account type must be `Personal Microsoft accounts only`.
      2. You don't need to fill `Redirect URI`.
4. Make allow public client flows to enable.
   - ![](https://i.imgur.com/ORtgNIs.png)
5. submit your application in here: https://aka.ms/mce-reviewappid
   - Recently, Mojang and Microsoft decided every authentication applications are required approve from them.
   - Details info here: https://aka.ms/AppRegInfo