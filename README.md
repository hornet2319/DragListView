# DragListView
DragListView can be used when you want to be able to re-order items in a list, grid or a board.
It also supports horizontal swiping of items in a list.

YouTube demo video<br>
[![Android drag and drop list and board](http://img.youtube.com/vi/Hxc7l06xhv4/0.jpg)](https://www.youtube.com/watch?v=Hxc7l06xhv4)

# Source
Original library are located here: https://github.com/woxblom/DragListView    
Added more flexibility to UI. Column's UI can be customized

## Features
* Re-order items in a list, grid or board by dragging and dropping with nice animations.
* Add custom animations when the drag is starting and ending.
* Get a callback when a drag is started and ended with the position.
* Disable and enable drag and drop
* Swipe list items

## Download lib with gradle

    repositories {
       maven { url "https://dl.bintray.com/lsherhsun/DragListView" }
    }

    dependencies {
        implementation 'com.lshershun.view:draglistview:0.0.1'
    }

Add this to proguard rules, otherwise animations won't work correctly

    -keep class com.woxthebox.draglistview.** { *; }

## License

If you feel like it then drop me a mail at woxthebox@gmail.com and tell me what app you have included this lib in. It is always fun to hear!

    Copyright 2014 Magnus Woxblom

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
