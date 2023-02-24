Unscramble App
===================================

Starter code for Android Basics codelab - Store the data in a ViewModel

Unscramble is  a single player game app that displays scrambled words. To play the game, player has
to make a word using all the letters from the displayed scrambled word.

Used in the [Android Basics with Kotlin](https://developer.android
.com/courses/android-basics-kotlin/course) course.


Pre-requisites
--------------

You need to know:
- Knowledge about Fragments.
- How to design a layout in ConstraintLayout.
- Able to write control flow statements (if / else, when statements).
- Able to update the UI of the app based on user input.
- Able to add a click listener to a Button.


Getting Started
---------------

1. Download and run the app.

License
-------

Copyright (C) 2020 The Android Open Source Project.

Licensed to the Apache Software Foundation (ASF) under one or more contributor
license agreements.  See the NOTICE file distributed with this work for
additional information regarding copyright ownership.  The ASF licenses this
file to you under the Apache License, Version 2.0 (the "License"); you may not
use this file except in compliance with the License.  You may obtain a copy of
the License at

  http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS, WITHOUT
WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.  See the
License for the specific language governing permissions and limitations under
the License.

Summary
-------

- The Android app architecture guidelines recommend separating classes that have different responsibilities and driving the UI from a model.
    
- A UI controller is a UI-based class like Activity or Fragment. UI controllers should only contain logic that handles UI and operating system interactions; they shouldn't be the source of data to be displayed in the UI. Put that data and any related logic in a ViewModel.

- The ViewModel class stores and manages UI-related data. The ViewModel class allows data to survive configuration changes such as screen rotations.
    
- ViewModel is one of the recommended Android Architecture Components.

Learn More
----------

- [ViewModel overview](https://developer.android.com/topic/libraries/architecture/viewmodel?authuser=1)
- [Guide to app architecture](https://developer.android.com/jetpack/docs/guide?authuser=1)
- [Hands-on with Material Components for Android: Dialogs](https://medium.com/over-engineering/hands-on-with-material-components-for-android-dialogs-75c6d726f83a)
- [Alert dialog anatomy](https://material.io/components/dialogs#anatomy)
- [MaterialAlertDialogBuilder](https://developer.android.com/reference/com/google/android/material/dialog/MaterialAlertDialogBuilder)
- [Backing Properties](https://kotlinlang.org/docs/reference/properties.html#backing-properties)
- [Android Architecture Components](https://developer.android.com/topic/libraries/architecture)
- Android Material [Dialogs](https://material.io/develop/android/components/dialogs)
- [Properties and Fields: Getters, Setters, const, lateinit](https://kotlinlang.org/docs/reference/properties.html)

