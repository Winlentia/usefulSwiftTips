# Useful Swift tips 

[#1 TopViewController Class Name](https://github.com/Winlentia/usefulSwiftTips/blob/master/README.md#1-topviewcontroller-class-name)


## [#1 TopViewController Class Name]

This func gives you the top view controller name log. its usefull for unknown projects.

```swift

    func printTopViewControllerName(){
        let topC = self.navigationController?.topViewController
        if let _name = topC?.className{
            print("top viewController name = " + _name)
        }
    }
    
```
