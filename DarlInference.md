[![Deploy to Azure](http://azuredeploy.net/deploybutton.png)](https://azuredeploy.net/?repository=https://github.com/drandysip/DarlInference)

[Link to GitHub](https://github.com/drandysip/DarlInference)

Hi,

These API Apps are intended to be free. They make use of a backend with a free and charged level. They implement AI based forms, and I’ve created some interesting logic apps that display forms and trigger other things when filled in, or another that has a conversation over email – twitter, yammer, etc. are possible too – and again triggers further processing when complete.

The app backend is hosted using API Manager and a couple of other Azure sites.

https://darlinf.portal.azure-api.net/

This contains tutorials, documentation and marketing stuff that should explain how this system works.

The Technology behind all this has been tested over many years, but the SaaS set up and of course the Logic App stuff is very new and in Beta. I’d love to hear any feedback, and bugs are welcome too. The developer portal has an issues page.

Andy Edmonds andy@docandys.com

----
# DarlInference


+ [DARL documentation](https://darlinf.portal.azure-api.net/docs)
+ [General tutorial](https://darlinf.portal.azure-api.net/tutorial)

A Logic App compatible API App that exploits the DARL SaaS inference engine to add an expert system type functionality to Logic Apps or any cloud based system.

You can create a new expert system using our super simple _DARL_ language [here](https://darlinf.portal.azure-api.net/). You then link the App to your subscription and the expert system project using simple keys.

This uses the same inference engine as our forms engine, but permits straight through and fast processing. inputs and results can be simple name value pairs, or more complicated structures permitting the user to both input and receive full uncertainty information including Fuzzy numbers (the fuzzy logic world's version of distributions), alternate categories and possibility/confidence values.

A free account offers sufficient usage to develop and run simple applications. A low cost paid for version offers unlimited usage.
