# iOS_Learning_Path
This is record of my learning path about iOS development




14th Oct 

Slider: 
init<V>(value: Binding<V>...blabla)
  
  What is Binding<V>? Store state and use
    Bind: A property wrapper type that can read and write a value owned by a source of truth.
    ref) https://developer.apple.com/documentation/swiftui/binding
  
  Why use constant when we need to show example? It returns Binding<Value>
    Constant: static func constant(_ value: Value) -> Binding<Value>
