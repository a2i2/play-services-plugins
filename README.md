# Google Play services Plugins

This project contains plugins to help with using Google Play services and
Firebase libraries.

## Getting Started

The plugins contained in this project are meant to work with the Google Play
services SDK. See https://developers.google.com/android/guides/overview to
get started.

## Contents

### strict-version-matcher-plugin

Helps with managing cross-library version dependencies between components.

### oss-licenses-plugin

Helps apps to display open source software licenses and notices.

### google-services-plugin

Required for firebase applications on android, converts google-services.json to a resource file for use by the app, and references the code in strict-version-matcher.

## Manually add licenses

Create a `third_party_licenses` directory in the root directory of your project. Then add any license as a text file.
The name of the file is used in the list activity, so best to avoid any file extensions like `.txt`. The contents of
the file are shown in the license activity itself.
