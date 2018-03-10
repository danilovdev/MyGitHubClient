# MyGitHubClient

There are four variations for my github client project. They are different in complexity and using technologies.

1. Simple. MVC Architecture

  a) Storyboard, 
  b) URLSession for networking 
  c) Core Data for stroing data
  d) Parsing JSON with JSONSerialization
  e) No Cocoa Pods
  f) No Unit Tests

2. Medium. MVVM Architecture + Closure bindings

  a) Storyboard, 
  b) Alamofire for networking 
  c) Core Data for stroing data
  d) Parsing JSON with Codable
  e) Using Cocoa Pods
  f) Using Unit Tests

3. Hard. MVVM Architecture + RxSwift

  a) No stroyboard, 
  b) NSLayoutConstraints for autolayout 
  c) Alamofire for networking
  d) Core Data for stroing data 
  e) Parsing JSON with Codable
  f) Using Cocoa Pods
  g) Using Unit Tests
  h) Auto rotation and iPad adaptation
  i) Color themes changing

4. Progressive. VIPER Architecture

  a) No stroyboard, 
  b) SnapKit for autolayout
  c) Alamofire for networking
  d) Moya for networking layer
  e) realm database for storing data
  f) Parsing JSON with Codable
  g) Using Cocoa Pods
  h) Using Unit Tests
  i) Auto rotation and iPad adaptation
  j) Storing user passwords in Keychain 
  k) Using Touch ID and Face ID
  l) Color themes changing
