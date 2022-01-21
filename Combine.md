# What is Combine?

It provides a declartive approach for how your app processes events. This has core componets such as, Publisher and Subscriber.

# Contents

NotificationCenter

Publisher

Subscriber

Transforming 

Filtering


"Just"

"assign(to: on:)"

"PassthroughSubject"

"CurrentValueSubject"

"Type erasure"


# Operators

.send()

.sink()

.store()

.post()


.collect()

.map()

.replaceNil(with:)

.replaceEnmpty(with:)

.scan()

.flatMap()


.first(where:)

.last(where:)

.prefix()

.drop(while:)

## Combining Operators

.prepend()

.append()

.switchToLatest()

.merger(with:)

.combineLatest()

.zip()



.dataTaskPublisher()

### Map Error

.tryMap{} 

.map{}


## SwiftUI and Combine

@State

@Published

@ObservedObject
