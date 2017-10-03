# Creating RxSwift Project

This should work. The steps are there for starting from an empty directory. All of these steps have been completed. 

- *NOTE:* 1 exception is 
 ``` pod install ```

may need to be ran


*To Start:*
1)   create a Podile
this can be done with vim, and this is the defualt 
```
use_frameworks!
target 'testproj' do
   pod 'RxSwift', '~> 3.0'
   pod 'RxCocoa', '~> 3.0'
  end
  ```
*NOTE:* change testproj to the directory where the Podfile lives
  
2) run pod install
```
pod install 
```

3) init defult xcode project structure 
``` 
swift package init 
```

4) generate xcode project
```
swift package generate-xcodeproj
```

This should be everything
