# Contents

1. Step 5

2. Resources Table

3. Front End

4. Animation

5. Back End




## 1. Step 5

1. Read Swift Document 
2. Watch Videos 
3. Read Article about iOS Development
4. Study Open Sourece iOS App
5. Make App that you want to make by changing what you learned a little bit. 
   (This help you get more advice from others and get a sense of accomplishment quickly.)


## 2. Resources Table

| Type | Title | URL |
|:-----:|-------|:------:|
|Document| Swift Document| https://www.swift.org/ |
|Document| Document Archive| https://developer.apple.com/library/archive/ |
|Document| Apple Developer Documentation| https://developer.apple.com/documentation/ |
|Document| Human Interface Guidelines | https://developer.apple.com/design/human-interface-guidelines/ |
| Video | Raywenderlich| https://www.raywenderlich.com/books/combine-asynchronous-programming-with-swift/v2.0 |
| Video | iOS & Swift - The Complete iOS App Development Bootcamp | https://www.udemy.com/course/ios-13-app-development-bootcamp/ |
| Video | Standford iOS Lectures |https://www.youtube.com/watch?v=yOhyOpXvaec|
| Web | SwiftUI Lab | https://swiftui-lab.com/ |
| Web | Swift By Sundell | https://www.swiftbysundell.com/ |
| Web | NSHipster | https://nshipster.com/ |
| Web | Swift Forums | https://forums.swift.org/ |
| Web | Learning Language | https://learnxinyminutes.com/ |
| Web | iOS Open-Source App | https://github.com/dkhamsing/open-source-ios-apps |
| Article | On the road to learn swiftUI | https://karinprater.medium.com/on-the-road-to-learn-swiftui-8b26b528199c |


## 3. Front End

Stack

List

Grid 

Navigation View

Section

Geometry Reader

## 4. Animation

Animation

RotationEffect

Single stage

Multiple stages

Interactive animations

## 5. Back End

Files & Data

User Defalut 

Json 

Property Lists

Core Data

Concurrency

ㄴ NSThread Class

ㄴ POSIX Threads

ㄴ Grand Central Dispatch

ㄴ Queues

Priorities and Cache Policies

URLSession

ㄴ URLSessionDataTask

ㄴ URLSessionUploadTask

ㄴ URLSessionWebSocketTask

ㄴ URLSessionStreamTask

ㄴ URLSessionDownloadTask










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
        

        

    

