This guide explains how to deploy prototypes to CQC's Heroku account.

After following this guide your prototype will automatically deploy any changes that you push to GitHub.

## Before you start

You'll need to be a member of the [cqc-design (comming soon)](#) Heroku team and have your prototype in [CQC's GitHub account](https://github.com/CQCDigital).

If you don't have access to these, email design-system@cqc.org.uk and whoever is managing support that day should be able to add you.

<!-- If you don't know how to setup GitHub read the [version your prototype](#) guide. -->

## Setting up Heroku

TBC

## Creating an app

TBC

## Setting a username and password

Prototypes require a username and password when published online. This stops members of the public coming across your prototype by accident.

There are a few different ways you can do this. Here are the instructions for setting this via the Heroku web interface.

1. from your pipeline view click the app name in the production column, this will take you to the overview of the app
2. click the 'setting' tab at the top of the page
3. in the section titled 'Config Vars' click the button 'Reveal Config Vars'
4. in the 'KEY' field type `USERNAME` (all uppercase), in the corresponding 'VALUE' field type your chosen username and click 'Add'
5. a new set of empty fields will appear, in the 'KEY' field type `PASSWORD` (all uppercase), in the corresponding 'VALUE' field type your chosen password and click 'Add'

You can now navigate back to the pipeline and open the app in a browser to test the username and password.

If this has worked you should see a modal dialogue asking for a username and password.

## Deploying your prototype

TBC

## Configure automatic deploys

Automatic deploys mean that every push to the `master` branch will deploy a new version of this app.

TBC

## Enable review apps

TBC
