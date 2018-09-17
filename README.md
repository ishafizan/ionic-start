# ionic setup on osx
### 1. Create ionic account
[sign up](https://dashboard.ionicframework.com/signup)
### 2. Create project directory
example:
```
mkdir ~/Documents/workspace/projects/tutorial/ionic
```
### 3. install Node.js
[install on osx](http://osxdaily.com/2018/06/29/how-install-nodejs-npm-mac/)
```
brew update
brew install node
node -v
```
### 4. install ionic
```
sudo npm install -g ionic
```
### 5. create app
Next, create an Ionic app using “Tabs” app template. This starter project comes complete with three pre-built pages and best practices for Ionic development. With common building blocks already in place, we can add more features easily
```
ionic start photo-gallery tabs
```
- ? Integrate your new app with Cordova to target native iOS and Android? Yes
- ? Install the free Ionic Pro SDK and connect your app? Yes
- Log into your Ionic Pro account. Sign in now to easily access awesome features like Live Deploys later in this tutorial.
- Choose “Create a new app on Ionic Pro.”
- Would you like to create a new app on Ionic Pro? Yes
- Which git host would you like to use? Choose “Ionic Pro.”
- Choose “Automatically setup a new SSH key pair for Ionic Pro” if you haven’t used SSH before.
### 6. change into app directory
```
cd photo-gallery/
```
[dir structure](img/Screen%20Shot%202018-09-17%20at%209.03.56%20AM.png)












