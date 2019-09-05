# Useful Swift tips 

[#1 Namespacing with nested types]


## [#1 Namespacing with nested types]

This func gives you the top view controller name log. its usefull for unknown projects.

```swift

    func printTopViewControllerName(){
        let topC = self.navigationController?.topViewController
        if let _name = topC?.className{
            print("top viewController name = " + _name)
        }
    }
    
```
