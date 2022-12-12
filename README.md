<h1 align="center">Based on <a href="https://github.com/tanujnotes/Olauncher">OlauncherAF</a>. Minimal and clean of back links</h1>
</p><h3 align="center">mLauncher is a minimal app launcher for Android.

We try to balance customizability and minimalization well still being simple :)</h3>

<img src="art/Header.png" width="1000">

# Forked with extra features

- Removed bloat, like ads and links
- You can rename apps in the app-drawer _(Renaming apps on the home screen is already supported. Just long-click on an app on the home screen and start typing)_
- Ability to change the app or action when clicking on the clock
- Ability to change the app or action when clicking on the date
- Ability to change the app or action when swiping up, down, left or right
- Align clock and date independently of home apps
- Change alignment of apps in app-drawer
- Change font size
- A lot of people have translated the app to the following languages. Many thanks to you ❤️
  - Albanian
  - Arabic
  - Chinese
  - Croatian
  - Danish
  - English
  - Estonian
  - French
  - German
  - Greek
  - Hawaiian
  - Hebrew
  - Icelandic
  - Indonesian
  - Irish
  - Italian
  - Korean
  - Malay
  - Malayalam
  - Norwegian
  - Persian
  - Portuguese (European)
  - Polish
  - Russian
  - Spanish
  - Swedish
  - Thai
  - Turkish

## Installation

[<img src="https://fdroid.gitlab.io/artwork/badge/get-it-on.png" alt="Get it on F-Droid" height="80">](https://f-droid.org/packages/app.mlauncher/)
[<img src="art/get-it-on-github.png" alt="Get it on Github" height="80">](https://github.com/HeCodes2Much/mLauncher/releases)

- This app is available on [F-Droid](https://f-droid.org/packages/app.mlauncher/) <!-- & [Github](https://github.com/HeCodes2Much/mLauncher/releases/) Useful when relsease will be automatically generated by github -->
- The latest stable version is on the [`main`](https://github.com/HeCodes2Much/mLauncher/tree/main) branch. You can clone it and build the app yourself.
<!-- - A github action should build an apk for every [release](https://github.com/HeCodes2Much/mLauncher/releases). Useful when relsease will be automatically generated by github -->
- The **original app** is also available on [Play Store](https://play.google.com/store/apps/details?id=app.olauncher), [F-Droid](https://f-droid.org/fr/packages/app.olauncher/) & [Github](https://github.com/tanujnotes/Olauncher).

## Contribute

- If you are unhappy with any part of the app or feel like missing something, you can open a pull request or an [**issue**](https://github.com/HeCodes2Much/mLauncher/issues/new/choose) as you like.
- Any help in translating mLauncher into other languages is greatly appreciated. If you don't know how to perform a pull request, feel free to check out our dedicated [**Wiki**](https://github.com/HeCodes2Much/mLauncher/wiki).

## Pull Requests

- Please go through the issues marked as `Bug report`, `Crash report` or `Feature request`
- Please let's discuss before sending pull requests
- Make pull requests to `main` branch


## License

**mLauncher is under open source GPL3 license, meaning you can use, study, change and share it at will.**
Copyleft ensures it stays that way. From the full source, anyone can build, fork and use as you wish

- mLauncher does not have network access.
- mLauncher does not collect or transmit any data in any way whatsoever.

## Permissions

mLauncher uses the following permissions:

- `android.permission.EXPAND_STATUS_BAR`
  - Allows an application to expand or collapse the status bar.
- `android.permission.QUERY_ALL_PACKAGES`
  - Allows query of any normal app on the device, regardless of manifest declarations. Used to show the apps list.
- `android.alarm.permission.SET_ALARM`
  - Allows an application to broadcast an Intent to set an alarm for the user. Used to open the default alarm app if no other clock app is set in the settings.
- `android.permission.REQUEST_DELETE_PACKAGES`
  - Required for issuing the request to remove packages. This does not allow the app to remove apps directly; this only gives the permission to issue the request.
