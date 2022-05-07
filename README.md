### Hi there 👋 I'm Ilya Zelkin!


- 💻 I like to create apps for IOS
- 📱 I'm Mobile Developer
- ✅ All the time I want to learn something new
- ✨ I improve my skills every day


```Swift 
var mySkillsArray = ["Swift", "UIKit", "SwiftUI", "MVC", "MVP", "MVVM", "Work With APIs", "ARKit", "CoreData", "CocoaPods", "HIG", "Git"]

struct MyProfile: CustomStringConvertible {
    let name = "Ilya"
    var description: String {
     """
     Hello everyone! I'm \(name) and I'm Mobile Developer
     I create app for IOS! Every time I care about the design and
     quality of my applications because I want to create fascinating apps!
     
     """
    }
    func iCanUse() {
        for skills in mySkillsArray {
            print("i can use: \(skills)")
        }
    }
}

let myProfile = MyProfile()
print(myProfile.description)
print(myProfile.iCanUse())
