# crud-clean-arch

## Table of contents
* [General info](#general-info)
* [Libraries Used](#libraries-used)

## General info
Simple notes app using clean architecture


## Libraries Used


  * [Android KTX][2] - Write more concise, idiomatic Kotlin code.
* [Architecture][3] - A collection of libraries that help you design robust, testable, and
  maintainable apps. Start with classes for managing your UI component lifecycle and handling data
  persistence.
  * [Data Binding][4] - Declaratively bind observable data to UI elements.
  * [Lifecycles][5] - Create a UI that automatically responds to lifecycle events.
  * [LiveData][6] - Build data objects that notify views when the underlying database changes.
  * [Navigation][7] - Handle everything needed for in-app navigation.
  * [Room][8] - Access your app's SQLite database with in-app objects and compile-time checks.
  * [ViewModel][9] - Store UI-related data that isn't destroyed on app rotations. Easily schedule
     asynchronous tasks for optimal execution.
* [UI][11] - Jetpack Compose
* Third party and miscellaneous libraries
  * [Kotlin Coroutines][14] for managing background threads with simplified code and reducing needs for callbacks
  * [Dagger Hilt][15] for dependency injection



[2]: https://developer.android.com/kotlin/ktx
[3]: https://developer.android.com/jetpack/arch/
[4]: https://developer.android.com/topic/libraries/data-binding/
[5]: https://developer.android.com/topic/libraries/architecture/lifecycle
[6]: https://developer.android.com/topic/libraries/architecture/livedata
[7]: https://developer.android.com/topic/libraries/architecture/navigation/
[8]: https://developer.android.com/topic/libraries/architecture/room
[9]: https://developer.android.com/topic/libraries/architecture/viewmodel
[11]: https://developer.android.com/jetpack/compose
[12]: https://developer.android.com/guide/components/fragments
[13]: https://developer.android.com/guide/topics/ui/declaring-layout
[14]: https://kotlinlang.org/docs/reference/coroutines-overview.html
[15]: https://dagger.dev/hilt/
