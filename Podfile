# Uncomment the next line to define a global platform for your project
# platform :ios, '18.0'

post_install do |installer|
  installer.pods_project.targets.each do |target|
    target.build_configurations.each do |config|
      config.build_settings['IPHONEOS_DEPLOYMENT_TARGET'] = '17.0'
    end
  end
end

target 'InstaCashSDK' do
  # Comment the next line if you don't want to use dynamic frameworks
  use_frameworks!
  
  # Pods for InstaCashSDK
  
  #pod 'FirebaseAnalytics'
  #pod 'FirebaseCrashlytics'
  #pod 'FirebaseDatabase'
  #pod 'FirebaseMessaging'
  #pod 'QRCodeReader.swift'
  #pod 'Alamofire'
  #pod 'AlamofireImage'
  
  pod 'SwiftyJSON'
  pod 'SwiftGifOrigin'
  pod 'DKCamera'
  pod 'BiometricAuthentication'
  pod 'INTULocationManager'
  pod 'Luminous'
  pod 'JGProgressHUD'
  pod 'PopupDialog'
  pod 'Toast-Swift'
  
  #pod 'AACameraView'
  pod 'CameraManager'
  pod 'Mute'
  
  
end
