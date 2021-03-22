# Agile Delivery Course

The course will teach you the importance of **Agile and Rapid Delivery**. Through a defined pipeline, where each stage of an app can be tested, I'll walk you through the process of adding a new feature to an existing app. We'll learn the importance of having different environments when developing, we'll strive for a bug-free production app.

We'll be working on a hybrid app with React Native, being able to run in different platforms such as Web, Android, and iOS (with active account). Please make sure to complete the initial setup for this course and follow along!

### Initial Setup

We'll be using [Expo](https://expo.io/), a framework for hybrid app development that will help us develop, build and deploy our app with faster iterations, aiming for quick and rapid deliveries.

The first thing you'll need is a free account at [Expo](https://expo.io/). Once your registration is complete, go ahead and create an **Access Token** (Settings > Access Tokens > Create). Store it in a safe place for now since you won't be able to display it in the future.

Next, download this project's repository, available [here](https://link). Open `expo-github.yml` under `.github/workflows`. This is a special folder Github uses to detect configured workflows. In this case `expo-github.yml` is describing a **Build and Publish** action. Edit **expo-token** with your access token.

Create a new repository on Github and add the remote to the recently downloaded project. You'll be needing it for automatic deploys to Expo and Heroku. In your new repository, add **EXPO_TOKEN** to your secrets (Settings > Secrets > New repository secret).

Create a new project called **ToDoList**. Write down slug name.

In `app.json` change the `owner` key to match your Expo user name and make sure `slug` field matches your recently created Expo app slug.

#### Web App
Create a free account on [Heroku](https://www.heroku.com). You'll be using Heroku to host your web app. Create an **API key** (Account Settings > API key).

Add your new API key to Github secrets as **HEROKU_API_KEY**.

#### Android App
Download an Android emulator. I'll be using Android Studio's emulator.

