# [HumHub](https://humhub.com/) TWA Application

[![Android CI](https://github.com/GreenMeteor/humhub-twa/actions/workflows/android.yml/badge.svg)](https://github.com/GreenMeteor/humhub-twa/actions/workflows/android.yml) [![Java CI](https://github.com/GreenMeteor/humhub-twa/actions/workflows/gradle.yml/badge.svg?branch=master)](https://github.com/GreenMeteor/humhub-twa/actions/workflows/gradle.yml) [![CodeQL](https://github.com/GreenMeteor/humhub-twa/actions/workflows/codeql.yml/badge.svg)](https://github.com/GreenMeteor/humhub-twa/actions/workflows/codeql.yml)

This is a simple TWA application for HumHub and should be used as such.

### Configurations
The following is how to use this template for your own TWA uses.

- Download & Install [Android Studios](https://developer.android.com/studio).
- Download via git (`git@github.com/GreenMeteor/humhub-twa.git`) or the Download ZIP, there is also the option to Open in Desktop if you have [GitHub Desktop](https://desktop.github.com/) installed
- Find any & all mentions in the whole project of `com.humhub.pwa` and rename it to `com.yourdomain.pwa`.
- Under `/app/src/main/assets/manifest.json` modify it to match your HumHub instance.

### Optional Configurations
Here are some optional configurations that can be done.

- Changing the color is under `/app/src/main/res/values`
- To change the app icons go under `/app/src/main/res/mipmap-hdpi`, `/app/src/main/res/mipmap-mdpi`, `/app/src/main/res/mipmap-xhdpi`, `/app/src/main/res/mipmap-xxhdpi`, and finally `/app/src/main/res/mipmap-xxxhdpi`.

### Requirements
Here's the only requirements that should be needed to run the application once it has been compiled.

- Phone/Tablet running Android 6 (Has not been tested) or 7+ anything lower will not install or work.
- For those wanting to test the application a Android emulator will be needed, of course, Android Studios comes with a built-in one to use, but not everyone wants to go past compiling the app so find a good one that runs the above requirement.

> Note: This is a TWA application so it does not act like a normal application as it requires that you have a mobile browser install on your phone/tablet.
