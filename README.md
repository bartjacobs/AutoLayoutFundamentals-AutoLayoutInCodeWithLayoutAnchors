### Auto Layout Fundamentals: Working With Layout Anchors

#### Author: Bart Jacobs

In the [last lesson](http://bartjacobs.com/auto-layout-fundamentals-auto-layout-in-code/) of [Auto Layout Fundamentals](http://bartjacobs.com/tag/auto-layout-fundamentals/), you learned how to create and manage layout constraints in code. Creating layout constraints in code isn't pretty. It isn't intuitive and it is verbose, even if you decide to use Apple's [Visual Format Language](https://developer.apple.com/library/ios/documentation/UserExperience/Conceptual/AutolayoutPG/VisualFormatLanguage.html).

In iOS 9 and OS X El Capitan, Apple introduced the `NSLayoutAnchor` class to make working with layout constraints in code easier and more intuitive. One of my readers made me aware of the `NSLayoutAnchor` class and I must admit I was a bit skeptical at first. Even the **Visual Format Language** makes it difficult to manage constraints, how would another API make that easier.

Fortunately, I was wrong. The `NSLayoutAnchor` class makes creating and managing constraints almost painless. In addition to the `NSLayoutAnchor` class, Apple added a number of properties to `UIView` and `NSView`. The result is pretty nice.

**Read this article on the [blog](http://bartjacobs.com/auto-layout-fundamentals-working-with-layout-anchors/)**.
