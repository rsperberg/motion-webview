$:.unshift("/Library/RubyMotion/lib")
require 'motion/project'

Motion::Project::App.setup do |app|
  # Use `rake config' to see complete project settings.
  app.name = 'WebView'
  app.device_family = [:iphone, :ipad]
  # Set the status bar style, other options are UIStatusBarStyleDefault and UIStatusBarStyleBlackOpaque
  app.info_plist['UIStatusBarStyle'] = 'UIStatusBarStyleBlackTranslucent'
end
