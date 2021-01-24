# Uncomment the next line to define a global platform for your project
 platform :ios, '9.3'

def shared
  pod 'SSZipArchive', '2.2.3'
  pod 'MenuItemKit', '3.1.3'
  pod 'AEXML', '4.6.0'
  pod 'RealmSwift', '5.5.0'
  pod 'FontBlaster', '4.1.0'
  pod 'ZFDragableModalTransition', :git => 'https://github.com/alexpopov/ZFDragableModalTransition', :tag => 'merge-carthage-into-zoonooz'
end

target 'FolioReaderKit' do
  use_frameworks!
  
  # Pods for FolioReaderKit
  shared

  target 'FolioReaderKitTests' do
    shared
  end  
end
