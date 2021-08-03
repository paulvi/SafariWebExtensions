# SafariWebExtensions
examples for Safari Web Extensions


# Convertion of exisintg web extention project into XCode project
1. cd into folder with web extentions (containing `manifest.json`)
2. run `xcrun safari-web-extension-converter .`

- [Creating a Safari Web Extension](https://developer.apple.com/documentation/safariservices/safari_web_extensions/creating_a_safari_web_extension)

1. Example #1 "Sea Creator", download zip from [Developing a Safari Web Extension](https://developer.apple.com/documentation/safariservices/safari_web_extensions/developing_a_safari_web_extension)
(Also required running converter for build to work

`xcrun safari-web-extension-converter ./Sea\ Creator\ Extension/Resources`
)

- From https://github.com/artemnovichkov/wwdc21-samplecode/tree/main/AdoptingNewSafariWebExtensionAPIs

Safari 15 (for iOS 15) will support web extensions.
