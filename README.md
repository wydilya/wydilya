### Hi there 👋 I'm Ilya Zelkin!

- 💻 I like to create apps for Mobile Devices
- 📱 I'm a Mobile Developer
- ✅ All the time I want to learn something new
- ✨ I improve my skills every day


```Swift 
let mySkillsArray = [
	"Swift", "Java", "Kotlin", "UIKit", "SwiftUI", "Jetpack Compose", "MVC", "MVP", "MVVM",
	"Work With APIs", "ARKit", "CoreML", "MapKit", "CoreData", "CocoaPods", "HIG", "Firebase",
	"Git", "Figma", "Other Skills"
]

struct MyProfile: CustomStringConvertible {
	let name = "Ilya"
	var description: String {
		"""
		Hello everyone! I'm \(name) and I'm a Mobile Developer
		I create apps for iOS! Every time I care about the design and
		quality of my applications because I want to create fascinating apps!
		
		"""
	}
	func iCanUse() {
		for skills in mySkillsArray {
			print("I can use: \(skills)")
		}
	}
}


let myProfile = MyProfile()
print(myProfile.description)
print(myProfile.iCanUse())
