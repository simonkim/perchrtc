source 'https://github.com/CocoaPods/Specs.git'

inhibit_all_warnings!
platform :ios, '8.0'

abstract_target 'basepods' do
    pod 'CocoaLumberjack'
    pod 'nighthawk-webrtc', :podspec => './nighthawk-webrtc-chrome-m45-capture-xcode.podspec'
    pod 'XirSys', :git => 'https://github.com/samsymons/XirSys.git', :tag => '0.4'
    pod 'SocketRocket', :git => 'https://github.com/square/SocketRocket.git'
    pod 'AFNetworking/Reachability'

    target 'PerchRTC' do
    end
    
    target 'PerchRTCTests' do
    end
end
