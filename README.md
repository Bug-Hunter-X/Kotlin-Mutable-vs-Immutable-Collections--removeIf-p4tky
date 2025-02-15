# Kotlin Mutable vs Immutable Collections: removeIf

This repository demonstrates a common error in Kotlin related to the use of mutable and immutable collections. The `removeIf` function can only be used with mutable collections.  Attempting to use it on an immutable collection results in a compile-time error.

The `Bug.kt` file shows examples of using `removeIf` on `MutableList`, `MutableMap`, and `MutableSet`. The commented-out line demonstrates what happens when you try using `removeIf` on a `List`, which is immutable by default.

The key takeaway is understanding the difference and appropriately using mutable versus immutable collections based on your program's needs.