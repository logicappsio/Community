[![Deploy to Azure](http://azuredeploy.net/deploybutton.png)](https://azuredeploy.net/?repository=https://github.com/drandysip/DarlForms)

[Link to GitHub](https://github.com/drandysip/DarlForms)

Hi,

These API Apps are intended to be free. They make use of a backend with a free and charged level. They implement AI based forms, and I’ve created some interesting logic apps that display forms and trigger other things when filled in, or another that has a conversation over email – twitter, yammer, etc. are possible too – and again triggers further processing when complete.

The app backend is hosted using API Manager and a couple of other Azure sites.

https://darlinf.portal.azure-api.net/

This contains tutorials, documentation and marketing stuff that should explain how this system works.

The Technology behind all this has been tested over many years, but the SaaS set up and of course the Logic App stuff is very new and in Beta. I’d love to hear any feedback, and bugs are welcome too. The developer portal has an issues page.

Andy Edmonds andy@docandys.com

----

# DarlForms

+ [DARL documentation](https://darlinf.portal.azure-api.net/docs)
+ [General tutorial](https://darlinf.portal.azure-api.net/tutorial)

API App for use with Logic Apps in Microsoft Azure.

Behind DARL Forms is a SaaS engine that creates forms, questionnaires and other forms of data capture and inference. 
Our unique insight is that most non-trivial forms are tied to a set of requirements, like a mortgage application, a job appplication, etc. 
The form is used to collect information, and as the basis to make a decision.

Our system does everything at once by getting the user to define the requirements as a set of *rules* using our super-easy rule language, __DARL__. Our engine then creates a form and orders the inputs in the rules by their salience, asking the most important questions first, and not asking at all any questions that are made irrelevant by previous answers.

Thus you can automate the whole process of data collection and generation of a decision, built into a Logic App!

This particular API app displays an embeddable web page containing "n" of the questions at a time, where "n" can be set on the SaaS site.
As the user responds to the questions new questions are shown, and when a result can be inferred a selectable set of the results are displayed and the next stage in the Logic App processing is triggered with the collecteddata and inferred results.

The general pattern is that you create a logic app using connectors as required, and when the user initiates the conversation by messaging a particular address, twitter handle, phone no. etc., the logic app responds with a series of questions. Ultimately the forms engine decides the rules have been satisfied and returns a set of results, and optionally triggers further processing in the logic app with those results.

You create questionnaires using [our site](https://darlinf.portal.azure-api.net/) which contains online editors for the rules, text of questions and responses and general formatting. Multiple languages are supported.

A free account offers sufficient usage to develop and run simple applications. A low cost paid for version offers unlimited usage.
