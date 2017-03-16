# Facebook-Firebase-Login-Example

Follow instructions here https://firebase.google.com/docs/auth/ios/facebook-login

Code taken from different resources online to get FB data pulling to work. 

Podfile looks like this

```# Uncomment the next line to define a global platform for your project
# platform :ios, '9.0'

target 'Facebook Login' do
  # Comment the next line if you're not using Swift and don't want to use dynamic frameworks
  use_frameworks!

  # Pods for Facebook Login
  pod 'Firebase/Core'
  pod 'Firebase/Auth'

  # Pods for Facebook
  pod 'Bolts'
  pod 'FBSDKCoreKit'
  pod 'FBSDKLoginKit'

  target 'Facebook LoginTests' do
    inherit! :search_paths
    # Pods for testing
  end

  target 'Facebook LoginUITests' do
    inherit! :search_paths
    # Pods for testing
  end

end
```
