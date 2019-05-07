# Ev-Drive
The Electric-Vehicle Drive (EV-Drive) application provide us to Track report of Vehicle. and user can track drive history accroding to daily basis, weekly basis, monthly basis and whole drive. and get the accurate cost of drive. EV-Drive avaliable on Android and iOS both.  

# Version-

react-native version: 0.56.0

node version: 10.5.0

npm version: 6.1.0


 

# iOS installation pod file-

# platform :ios, '9.0'

target 'FuelChecker' do
 rn_path = '../node_modules/react-native'
  rn_maps_path = '../node_modules/react-native-maps'

  #### See http://facebook.github.io/react-native/docs/integration-with-existing-apps.html#configuring-cocoapods-dependencies
  pod 'yoga', path: "#{rn_path}/ReactCommon/yoga/yoga.podspec"
  pod 'React', path: rn_path, subspecs: [
    'Core',
    'CxxBridge',
    'DevSupport',
    'RCTActionSheet',
    'RCTAnimation',
    'RCTGeolocation',
    'RCTImage',
    'RCTLinkingIOS',
    'RCTNetwork',
    'RCTSettings',
    'RCTText',
    'RCTVibration',
    'RCTWebSocket',
  ]

  pod 'DoubleConversion', :podspec => "#{rn_path}/third-party-podspecs/DoubleConversion.podspec"
  pod 'glog', :podspec => "#{rn_path}/third-party-podspecs/glog.podspec"
  pod 'Folly', :podspec => "#{rn_path}/third-party-podspecs/Folly.podspec"

  # react-native-maps dependencies
  pod 'react-native-maps', path: rn_maps_path
  pod 'react-native-google-maps', path: rn_maps_path
  pod 'GoogleMaps'
  pod 'Google-Maps-iOS-Utils'
  pod 'ReactNativeFabric', :path => '../node_modules/react-native-fabric'

 pod 'RNBackgroundGeolocation', :path => '../node_modules/react-native-background-geolocation'
 pod 'RNBackgroundFetch', :path => '../node_modules/react-native-background-fetch'
end



# Dependencies linking other libraries:-

react-native-appsee
compileSdkVersion : 23 (Android)
buildToolsVersion : 27.0.3 (Android)
support link : https://www.npmjs.com/package/react-native-appsee

react-native-audio-player-recorder
compileSdkVersion : 23 (Android)
buildToolsVersion : 27.0.3 (Android)
support link : https://www.npmjs.com/package/react-native-audio-player-recorder

react-native-background-geolocation
compileSdkVersion : 26 (Android)
buildToolsVersion : 26.0.2 (Android)
support link : https://github.com/transistorsoft/react-native-background-geolocation

react-native-ble-manager
compileSdkVersion : 26 (Android)
buildToolsVersion : 26.0.1 (Android)
support link : https://github.com/innoveit/react-native-ble-manager

react-native-bluetooth-serial
compileSdkVersion : 23 (Android)
buildToolsVersion : 23.0.1 (Android)
support link : https://github.com/rusel1989/react-native-bluetooth-serial

react-native-fabric
compileSdkVersion : 23 (Android)
buildToolsVersion : 23.0.1 (Android)
support link : https://github.com/corymsmith/react-native-fabric

react-native-maps
compileSdkVersion : 25 (Android)
buildToolsVersion : 25.0.3 (Android)
support link : https://github.com/react-native-community/react-native-maps



