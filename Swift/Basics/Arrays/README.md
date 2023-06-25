# Arrays
* var/let [1, 2, 3] to assign an array
* .append("String") to add to an array
* .count() to count the number of items in an array
* .sorted() to sort alphabetically/numerically
 * .reversed() to sort reverse alphabetically
* .isEmpty() to check if array is empty
* .remove(at: i) to remove i item from array 
* .removeLast() to remove the last item from array
* (array[i]) to access i item in array
```
var beatles = ["John", "Paul", "George", "Ringo"]
var numbers = [4, 8, 15, 16, 23, 42]
var temperatures = [25.3, 28.2, 26.4]

beatles.append("Adrian")

var scores = Array<Int>()
scores.append(100)
scores.append(80)
scores.append(85)
print(scores[1])
print(scores.count)

var albums = Array<String>()
var albums2 = [String]()

var characters = ["Lana", "Pam", "Ray", "Sterling"]
print(characters.count)

characters.remove(at: 2)
print(characters.count)

characters.removeAll()
print(characters.count)

let bondMovies = ["Casino Royale", "Spectre", "No Time to Die"]
print(bondMovies.contains("Frozen"))
let cities = ["London", "Tokyo", "Rome", "Budapest"]
print(cities.sorted())
print(cities.reversed())
```

## Addional reading:
* [Apple Array documentaion](https://developer.apple.com/documentation/swift/array)
* [100 Days of SwiftUI day 3](https://www.hackingwithswift.com/100/swiftui/3)