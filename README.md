# RNLoadingButton

RNLoadingButotn is based on [RNLoadingButton](https://github.com/souzainf3/RNLoadingButton) write in Objective-C.

An easy-to-use UIButton subclass with an activity indicator.

The activity state is configurable and can hide the image or text while the activity indicator is displaying .
You can Also choose the position of easily activity indicator or Set It up with a spacing.



[![](https://raw.githubusercontent.com/souzainf3/RNLoadingButton-Swift/master/RNLoadingButtonDemo/Screens/screen1.png)](https://raw.githubusercontent.com/souzainf3/RNLoadingButton-Swift/master/RNLoadingButtonDemo/Screens/screen1.png)
[![](https://raw.githubusercontent.com/souzainf3/RNLoadingButton-Swift/master/RNLoadingButtonDemo/Screens/screen2.png)](https://raw.githubusercontent.com/souzainf3/RNLoadingButton-Swift/master/RNLoadingButtonDemo/Screens/screen2.png)


## Adding RNLoadingButton to your project


#### Cocoapods
1. Add a pod entry for RNActivityView to your Podfile `pod 'RNLoadingButton'`
2. Install the pod(s) by running `pod install`.

#### Swift Package Manager (SPM)
1. Open Swift Package Manager, copy `https://github.com/tommyming/RNLoadingButton-Swift-SPM` to the search bar
2. For version, you may use tags or master branch.

#### Manually
1. Drag `LoadingButton.swift` to your project

## Using RNLoadingButton

`RNLoadingView` is available in Interface Builder

```swift
// Mark: Buttons From Nib
// Configure State
btn1.hideTextWhenLoading = false
btn1.isLoading = false
btn1.activityIndicatorAlignment = .right
btn1.activityIndicatorEdgeInsets = UIEdgeInsets(top: 0, left: 50, bottom: 0, right: 10)
btn1.setTitleColor(UIColor(white: 0.673, alpha: 1.0), for: UIControlState.disabled)
btn1.setTitle("connecting", for: UIControlState.disabled)
btn1.activityIndicatorColor = .blue // Change the activity indicator color
```


### Properties

* Loading state
```swift
isLoading: Bool
```

* Hide image when loading is visible
```swift
hideImageWhenLoading: Bool
```

* Hide text when loading is visible
```swift
hideTextWhenLoading: Bool
```

* Edge Insets to set activity indicator frame. Default is .zero
```swift
activityIndicatorEdgeInsets: UIEdgeInsets
```

* Activity Indicator Alingment. Default is '.center'
```swift
activityIndicatorAlignment: ActivityIndicatorAlignment
```

* Activity Indicator style. Default is '.gray'
```swift
activityIndicatorViewStyle: UIActivityIndicatorViewStyle
```

* Color to activityIndicatorView. Default is 'nil'
```swift
activityIndicatorColor: UIColor
```


##### Apps using this control (send your to souzainf3@yahoo.com.br )
- [Zee - Personal Finances](https://itunes.apple.com/us/app/id422694086).
