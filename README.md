# Kotlin `removeIf` Unexpected In-Place Modification

This example demonstrates a potential pitfall when using the `removeIf` function in Kotlin.  `removeIf` modifies the original collection directly instead of returning a new one, which can be unexpected and lead to subtle bugs.

The `removeIfBug.kt` file shows how this can lead to incorrect results if you're not aware of this in-place modification. The `removeIfSolution.kt` file demonstrates a safer way of achieving the same result using a different approach that avoids modifying the original list and map.