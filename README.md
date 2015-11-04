# PodCastAndHockey
Shows broken copy bundle resource phase with cocoa pods and frameworks

1. Run `pod install`
2. Build in Xcode will fail in phase **Copy Bundle Resources**
3. Run `cp Pods-resources-workaround.sh Pods/Target\ Support\ Files/Pods/Pods-resources.sh` to replace automatically generated script.
4. Build suceeds
