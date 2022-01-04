# what is concurrency?

It is more than one task running at the same time.

# why does your app need concurrency?

To keep the user interface responsive.  

If we don't use concurrency, we'll lower the quality of user experience. such as, When downloading and scrolling images, these actions slow down the app.

# how do you use concurrency?

By structuring your app so some tasks can safely run at the same time. 

# what is GCD?

Grand Cetral Dispatch, for simple tasks

# what is Queue?

First in, First out. such as a waiting line to ride a roller coaster.

# what is the Operation?

It is a useful tool, such as being able to specify input, output, and helper methods. Additionally, the act of canceling. and for complex tasks.

# Contents

The Dispatch Framework was created by Apple as the concept of Grand Central Dispatch. Dispatch is Execute code concurrently on multicore hardware by submitting work to dispatch queues managed by the system.

Concurrent VS serial
Synchronous dipatch queues VS Asychronous dipatch queues

There are DispatchQueue.main and DipatchQueue.global(qos: ...) in GCD Queues. The Main queue is used so often for user interface updates. and this is serial.
The other global queues are concurrent they can have more than one tread. qos means quality of service, which has a total of six types.







