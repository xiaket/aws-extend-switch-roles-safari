# AWS Extend Switch Roles for Safari

This project takes over [tilfin/aws-extend-switch-roles](https://github.com/tilfin/aws-extend-switch-roles) and make it work on Safari 14 using [Safari Web Extensions](https://developer.apple.com/videos/play/wwdc2020/10665/).

For usage of the plugin, please go to the original project for details.

You'll need to build an app out of it and use it yourself. At the time of writing, we'll have to use Xcode 12 beta to create the app.

During the transformation/migration, I started from the latest addon in [Firefox store](https://addons.mozilla.org/ja/firefox/addon/aws-extend-switch-roles3/). Added version to the manifest.json file and fixed [a few APIs that Safari does not support yet](https://developer.apple.com/documentation/safariservices/safari_web_extensions/assessing_your_safari_web_extension_s_browser_compatibility).

All glory goes to the original author and the project contributors. :)
