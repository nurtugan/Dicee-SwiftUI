# Dicee-SwiftUI
My Third SwiftUI App

## Learned about...
+ `Spacer()`
+ `.padding(.horizontal)`
+ `Button`
+ `.aspectRatio(1, contentMode: .fit)`
+ `@State property wrapper` -> Read below info
> When we put @State before a property, we effectively move its storage out from our struct and into shared storage managed by SwiftUI. This means SwiftUI can destroy and recreate our struct whenever needed (and this can happen a lot!), without losing the state it was storing.
>> __Attention! ->__ To re-enforce the local nature of @State properties, __Apple recommends you mark them as private__.
>>> __Attention! ->__ @State should be used with simple struct types such as String and Int, and generally __shouldn’t be shared with other views__. If you want to share values across views, you should probably use @ObservedObject or @EnvironmentObject instead – both of those will ensure that all views will be refreshed when the data changes.

Source: https://www.hackingwithswift.com/quick-start/swiftui/what-is-the-state-property-wrapper

## Main view
<img src="https://github.com/nurtugan/Dicee-SwiftUI/blob/master/Screenshots/Screen%20Shot%202020-03-24%20at%202.04.26%20AM.png" alt="" width="371" height="648">

## App icon
<img src="https://github.com/nurtugan/Dicee-SwiftUI/blob/master/Screenshots/Screen%20Shot%202020-03-24%20at%202.04.38%20AM.png" alt="" width="371" height="648">
