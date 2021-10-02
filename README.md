[![Use this template](https://github.com/stack-instance/badge.svg)](https://github.com/stack-instance?stack_template_owner=3loka&stack_template_repo=flutter-android-playstore-stack)
                  
 <p>
    Do you have an idea and want to convert that idea to a Android app? <b>Use this stack</b> to get going in minutes
</p>


## Why should you use this stack?
If you are new to Android Application development and want to skip the boring setup stuff and get going quikly, You have come to the right place.
This stack generates a flutter based Android app, mentioned in this [tutorial](https://flutter.dev/docs/get-started/codelab). 

A Sample app is not just generated but even deployed to android play store at the same time you are creating your repository. Dont worry, if you dont have a Google Developer account, you can skip that part, but we have the automation covered so you can come and set it up later.

The stack also sets up a proper Github CI/CD environment by taing care of the following things
- creating a "main" branch and protecting it with one code reviewer. 

## What are the inputs to pass while setting up the stack?
```
- App Name (Only this is required)
- Flutter, Ruby & Java Versions - We will default it 
- A checkbox if you want to deploy to google app store - If you check it, then we will need below inputs
Inputs needed to publish to play store
- Base64 encoded Android Keystore for signing
- Android Package Name
- Google service account key
```

#### Github apps installed with this stack
Code Coverage

## How to setup local development server?
This is where you will love the stack. Codespaces is configured to work with the new repository you will create. You dont need to install flutter sdks, java sdks, ruby versions, emulators etc. Just create a codespace and your dev environment is ready in less than a minute.

#### Security guide
Please see our guide lines for reporting issues related to [security.md](/.github/stacks/security.md).

#### Contributor guide
Please see our guide lines for [contributing.md](/.github/stacks/contributing.md).

## Contributors 
- Trilok Ramakrishna ([@3loka](https://twitter.com/3loka))

## License
Unless otherwise noted, this GitHub Stack is distributed under the Apache Version 2.0 license found in the LICENSE file.
