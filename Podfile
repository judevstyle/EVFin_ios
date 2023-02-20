# Uncomment the next line to define a global platform for your project
source 'https://github.com/CocoaPods/Specs.git'
# workspace 'EVFin'
# platform :ios, '13.0'

CCPod = Struct.new(:name, :version)

# Share
ObjectMapper = CCPod.new('ObjectMapper','~> 3.4')
ToastSwift = CCPod.new('Toast-Swift', '5.0.1')
Moya = CCPod.new('Moya', '15.0.0')
Kingfisher = CCPod.new('Kingfisher', '~> 7.0')
SkeletonView = CCPod.new('SkeletonView', '1.30.4')
MultiSlider = CCPod.new('MultiSlider', '1.13.1')
FittedSheets = CCPod.new('FittedSheets', '2.4.2')
SwiftFormatCLI = CCPod.new('SwiftFormat/CLI', '~> 0.49')
RxSwift = CCPod.new('RxSwift', '6.5.0')
MessageKit = CCPod.new('MessageKit', '3.8.0')

GoogleMaps = CCPod.new('GoogleMaps', '7.1.0')
GooglePlaces = CCPod.new('GooglePlaces', '7.1.0')
GoogleMapsiOSUtils = CCPod.new('Google-Maps-iOS-Utils', '4.1.0')
GoogleSignIn = CCPod.new('GoogleSignIn', '~> 5.0')
GoogleUtilities = CCPod.new('GoogleUtilities', '7.8.0')

Firebase = CCPod.new('Firebase', '9.6.0')
FirebaseAuth = CCPod.new('FirebaseAuth', '9.6.0')
FirebaseCore = CCPod.new('FirebaseCore', '9.6.0')
FirebaseFirestore = CCPod.new('FirebaseFirestore', '9.6.0')
FirebaseFirestoreSwift = CCPod.new('FirebaseFirestoreSwift', '9.6.0')
FirebaseDatabase = CCPod.new('FirebaseDatabase', '9.6.0')
FirebaseMessaging = CCPod.new('FirebaseMessaging', '9.6.0')

FacebookCore = CCPod.new('FacebookCore', '0.9.0')
FacebookLogin = CCPod.new('FacebookLogin', '0.9.0')
FacebookShare = CCPod.new('FacebookShare', '0.9.0')

TOCropViewController = CCPod.new('TOCropViewController', '2.6.1')
Alamofire = CCPod.new('Alamofire', '5.6.4')

def share_pods
  pod ObjectMapper.name, ObjectMapper.version
  pod ToastSwift.name, ToastSwift.version
  pod Moya.name, Moya.version
  pod Kingfisher.name, Kingfisher.version
  pod SkeletonView.name, SkeletonView.version
  pod MultiSlider.name, MultiSlider.version
  pod FittedSheets.name, FittedSheets.version
  pod SwiftFormatCLI.name, SwiftFormatCLI.version
  pod RxSwift.name, RxSwift.version
  pod MessageKit.name, MessageKit.version
  pod TOCropViewController.name, TOCropViewController.version
  pod Alamofire.name, Alamofire.version
end

def google_pods
  pod GoogleMaps.name, GoogleMaps.version
  pod GooglePlaces.name, GooglePlaces.version
  pod GoogleMapsiOSUtils.name, GoogleMapsiOSUtils.version
  pod GoogleSignIn.name, GoogleSignIn.version
  pod GoogleUtilities.name, GoogleUtilities.version
end

def firebase_pods
  pod Firebase.name, Firebase.version
  pod FirebaseAuth.name, FirebaseAuth.version
  pod FirebaseCore.name, FirebaseCore.version
  pod FirebaseFirestore.name, FirebaseFirestore.version
  pod FirebaseFirestoreSwift.name, FirebaseFirestoreSwift.version
  pod FirebaseDatabase.name, FirebaseDatabase.version
  pod FirebaseMessaging.name, FirebaseMessaging.version
end

def facebook_pods
  pod FacebookCore.name, FacebookCore.version
  pod FacebookLogin.name, FacebookLogin.version
  pod FacebookShare.name, FacebookShare.version
end

target 'EVFin' do
  # Comment the next line if you don't want to use dynamic frameworks
  use_frameworks!
  share_pods
  google_pods
  firebase_pods
  facebook_pods
  
  # Pods for EVFin

  target 'EVFinTests' do
    inherit! :search_paths
    # Pods for testing
  end

  target 'EVFinUITests' do
    # Pods for testing
  end

end
