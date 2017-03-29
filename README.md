#  Barambe (Mobile)
[Download on Android](https://play.google.com/store/apps/details?id=com.barambe)

[![js-standard-style](https://img.shields.io/badge/code%20style-standard-brightgreen.svg?style=flat)](http://standardjs.com/)

* Standard compliant React Native App Utilizing [Ignite](https://github.com/infinitered/ignite)

## Setting Up Docs

* [Yarn Cheatsheet](https://shift.infinite.red/npm-vs-yarn-cheat-sheet-8755b092e5cc#.1ckrhd77a)

* [React Native: Getting Started](https://facebook.github.io/react-native/docs/getting-started.html)

* [React Native: Android Setup](https://facebook.github.io/react-native/releases/0.23/docs/android-setup.html)

* [Genymotion Personal Edition](https://www.genymotion.com/fun-zone/)

## React-Native Request Notes

* [Connect localhost with Android Emulator](https://github.com/facebook/react-native/issues/10404#issuecomment-280553649)

* [react-native-fetch-blob](https://www.npmjs.com/package/react-native-fetch-blob) 

* [Manually Link Package in react-native](https://github.com/wkh237/react-native-fetch-blob/wiki/Manually-Link-Package)

* [Using Native JavaScript Fetch()](https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API/Using_Fetch)

* [React-Native Using Fetch](https://facebook.github.io/react-native/docs/network.html) 


## :arrow_up: How to Setup

**Step 1:** git clone this repo:

**Step 2:** cd to the cloned repo:

**Step 3:** Install the Application with `npm install`


## :arrow_forward: How to Run App

1. cd to the repo
2. Run Build for either OS
  * for iOS
    * run `react-native run-ios`
  * for Android
    * Run Genymotion
    * run `react-native run-android`

## :no_entry_sign: Standard Compliant

[![js-standard-style](https://cdn.rawgit.com/feross/standard/master/badge.svg)](https://github.com/feross/standard)
This project adheres to Standard.  Our CI enforces this, so we suggest you enable linting to keep your project compliant during development.

**To Lint on Commit**

This is implemented using [ghooks](https://github.com/gtramontina/ghooks). There is no additional setup needed.

**Bypass Lint**

If you have to bypass lint for a special commit that you will come back and clean (pushing something to a branch etc.) then you can bypass git hooks with adding `--no-verify` to your commit command.

**Understanding Linting Errors**

The linting rules are from JS Standard and React-Standard.  [Regular JS errors can be found with descriptions here](http://eslint.org/docs/rules/), while [React errors and descriptions can be found here](https://github.com/yannickcr/eslint-plugin-react).

## :closed_lock_with_key: Secrets

This project uses [react-native-config](https://github.com/luggit/react-native-config) to expose config variables to your javascript code in React Native. You can store API keys
and other sensitive information in a `.env` file:

```
API_URL=https://myapi.com
GOOGLE_MAPS_API_KEY=abcdefgh
```

and access them from React Native like so:

```
import Secrets from 'react-native-config'

Secrets.API_URL  // 'https://myapi.com'
Secrets.GOOGLE_MAPS_API_KEY  // 'abcdefgh'
```

The `.env` file is ignored by git keeping those secrets out of your repo.

## :open_file_folder: Related Articles
Ignite Documentation - [Ignite Wiki https://github.com/infinitered/ignite/wiki](https://github.com/infinitered/ignite/wiki)
