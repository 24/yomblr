platform :ios, '9.0'

target 'yomblr' do
  use_frameworks!
  
  pod 'TMTumblrSDK', git: 'https://github.com/tumblr/TMTumblrSDK.git'

  target 'yomblrTests' do
    inherit! :search_paths
  end

end

plugin 'cocoapods-keys', {
  :project => 'yomblr',
  :keys => [
    "OAuthConsumerKey",
    "OAuthConsumerSecret"
  ]
}
