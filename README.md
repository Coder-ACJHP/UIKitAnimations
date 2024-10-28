# UIKitAnimations
A lot of animations, transitions created using Swift UIKit iOS 11 

Detailed explanation made in my Medium article [Create custom ViewController Transition styles using Core Image Transition Filters](https://medium.com/@onur.isik/create-custom-viewcontroller-transition-styles-using-core-image-transition-filters-f75b3dfbdd63) and [Custom Ripple Effect View Controller Transition in Swift](https://medium.com/@onur.isik/custom-ripple-effect-view-controller-transition-in-swift-200d72340494))

### 26/10/24 
1. Added new custom animated tabBar (path animated and selected tabItem location will be excavated)
2. Added UINavigationController push and back transitions without using UINavigationController (can be selected before presenting ViewController as modalTransitionStyle = .push or .back)
Do not pass true to present method
3. MainViewController ui refactored (Used custom tableView + cell with sections)