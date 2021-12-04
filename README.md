## iOS_Learning_Path
This is record of my learning path about iOS development

| Type | Title | Resource |
|:-----:|-------|:------:|
| Video | Raywenderlich| https://www.raywenderlich.com/books/combine-asynchronous-programming-with-swift/v2.0 |
| Video | iOS & Swift - The Complete iOS App Development Bootcamp | https://www.udemy.com/course/ios-13-app-development-bootcamp/ |
|Document| SwiftUI Document| https://developer.apple.com/documentation/swiftui/ |
|Article | On the road to learn swiftUI | https://karinprater.medium.com/on-the-road-to-learn-swiftui-8b26b528199c |

## Good Reference to start Swift

https://www.youtube.com/watch?v=yOhyOpXvaec

https://swiftui-lab.com/

https://learnxinyminutes.com/

<details>
    <summary>Swift Document</summary>
    
    Structures and Classes
    
    in coomon 
    properties, methods, subscripts, initializers, Be extended, conform to protocols
    
    class have aditional capabilities
    Inheritance, Type Casting, Deinitializers, Automatic Reference Counting 
    
</details>
    


<details>
    <summary>Raywenderlich</summary>
<details>
    <summary>Raywenderlich_Making Bullseye App</summary>
    14th Oct 

Slider: 
  init<V>(value: Binding<V>...blabla)
  
   What is Binding<V>? Store state and use
  
     Bind: A property wrapper type that can read and write a value owned by a source of truth.
     ref) https://developer.apple.com/documentation/swiftui/binding
  
   Why use constant when we need to show example? It returns Binding<Value>
  
      Constant: static func constant(_ value: Value) -> Binding<Value>

15th Oct
  
  Padding:
   func padding(_ length: CGFloat) -> some View
  
  

16th Oct
  
  Rounded:
   func rounded() -> Double
  
17th Oct
  
  Text: 
    Text("String")
  
18th Oct
  
  abs():
    func abs<T>(_ x: T) -> T where T : Comparable, T : SignedNumeric
  
19th Oct
  
  padding():
    func padding(_ length: CGFloat) -> some View
  
      Return Value A view that pads this view by the amount you specify. 
  
      Order is matter.
    
23th Nov

  onDelete(perform: ):
  func onDelete(perform action: Optional<(IndexSet) -> Void>) -> some DynamicViewContent
     Sets the deletion action for the dynamic view.    
</details>


<details>
    <summary>Raywenderlich_Swift fundamentals</summary>
    <details>
    <summary>More Collections</summary>
Introduction
        
Creating & Populating Dictionaries
        
Accessing & Working with Dictionaries
        
Challenge: Dictionaries
        
Working with Sets
        
Challenge: Sets
        
Conclusion
        
</details>
    <details>
    <summary>Function and Types</summary>
        
Functions
        
Closure
        
Enumerations
        
Properties & Methods
        
Protocols & Inheritance        
        

        

    

