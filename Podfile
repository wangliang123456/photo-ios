target 'photo-ios' do
  platform :ios, '9.3'
  pod 'OpenCV'
  pod 'SVProgressHUD', :git => 'https://github.com/SVProgressHUD/SVProgressHUD.git'
  pod 'SDWebImage'
  pod 'Mantle'
  pod 'Masonry'

  post_install do |installer| 
    installer.pods_project.targets.each do |target|
        target.build_configurations.each do |config|
            config.build_settings['SWIFT_VERSION'] = '3.0'
        end
    end
end
end
