source 'https://github.com/CocoaPods/Specs.git'
source 'https://github.com/twilio/cocoapod-specs'
source 'https://github.com/streem/cocoapods'

use_frameworks!

platform :ios, '10.3'

target 'StreemNow' do
  #pod 'Streem', :podspec => '../streem-app/streem-sdk/ios/cocoapods/Streem/0.6.0/Streem.podspec.json'
  pod 'Streem', '~> 0.9.17'

  target 'StreemNow_Tests' do
    inherit! :search_paths

    pod 'Quick', '~> 1.2.0'
    pod 'Nimble', '~> 7.0.2'
    pod 'FBSnapshotTestCase' , '~> 2.1.4'
    pod 'Nimble-Snapshots' , '~> 6.3.0'
  end
end
