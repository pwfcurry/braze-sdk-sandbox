Braze SDK in a new Expo project

- `yarn build-ios`
- (install on simulator)
- `yarn start`

The logLevel has been set to 0 (verbose) but no Braze logs appear in the console.

https://www.braze.com/docs/developer_guide/platform_integration_guides/react_native/react_sdk_setup/#step-2-complete-native-setup

> The log level for your application. The default log level is 8 and will minimally log info. To enable verbose logging for debugging, use log level 0.

Config option is definitely in built app's Info.plist:
- `plutil -convert xml1 brazesdksandbox.app/Info.plist`
- see committed file actualInfo.plist
