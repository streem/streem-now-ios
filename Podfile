source 'https://github.com/twilio/cocoapod-specs'
source 'https://github.com/CocoaPods/Specs.git'

use_frameworks!

platform :ios, '11.0'

target 'StreemNow' do
  pod 'StreemKit', '~> 0.20.0', :source => 'https://github.com/streem/cocoapods'
  pod 'AppAuth', '~> 1.4'
end

post_install do |installer|
  load './Pods/StreemKit/configure_streemkit.rb'
  configure_streemkit(installer)
end
