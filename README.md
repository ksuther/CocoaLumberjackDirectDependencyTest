Demonstration of manually including CocoaLumberjack as a dependency.

- Clone CocoaLumberjack as a submodule: `git submodule update --init --recursive`
- Set a signing team in the project settings
- Run `xcrun xcodebuild -allowProvisioningUpdates -scheme 'TestProject' -configuration Release archive -archivePath 'iOS.xcarchive'`
