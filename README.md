# Firebase iOS Auth usage demo

## Getting started!

### Configure Facebook Login in the App
- Go to [Facebook for developers portal](https://developers.facebook.com/)
- Click on My APPS -> Add a new App
- Fill the form and then click on Create App ID
- On the left column search for Facebook Login quick start, click and select iOS
- Add your bundle identifier in step 2 (Same as you put in the app) - If you dont remember, check your project file under Bundle Identifier in the Identity Tab
- Enable Single Sign On on step 3
- Open the Info.plist and replace `CFBundleURLSchemes` and `FacebookAppID` with the values you got

# Get Facebook ID and Secret
- Go to [Facebook for developers portal](https://developers.facebook.com/)
- Open your app from the MY APPs menu
- On the left pane click on Settings - Basic

# Configure Firebase Auth for Facebook
- Go to https://console.firebase.google.com/
- Open the Auth configuration
- Setup Sign in method
- Enable facebook (Add App ID and Secret)
- Copy the OAuth redirect URI that you got (?))(?)(?))?
- Save
