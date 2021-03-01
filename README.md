# newsletterSignUpPage
**Step 1**
-Following these steps to create an account, unique id for audience (can be found in Audience dashboard/ Manage Audience/ Settings) and APIkey for free with [Mailchimp](https://mailchimp.com/developer/marketing/guides/quick-start/)

**Step 2** 
-Clone the project

**Step 3**
-Create a folder name environment. Then create environment.js file in this folder. Inside the file, make an object as followed:
```module.exports.environment = {
  apiKey: “putHereYourObtainedAPIkeyInMailChimp”,
  listID: "putHereYourObtainedUniquireIDForAAudienceInMailChimp"
}```
Then save.


**Step 4**
-Open the project in terminal, run the project with command:
```nodemon app.js```
