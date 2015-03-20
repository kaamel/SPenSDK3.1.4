# SPenSDK3.1.4
Static Library for Samsung SDK for SPEn version 3.1.4

For background information please refer to Samsung Developer website [here](http://developer.samsung.com/forum/thread/spensdk-314-static-version-on-android-studio/201/278707)

I created this library since Samsung's [documentation](http://developer.samsung.com/technical-doc/view.do?v=T000000201) as of Feb 6, 2015  for using their SDK in the static mode was incomplete, inaccurate, or unclear, depnding on one's point of view.

To use it, just add it as a library module to your project and then make it a dependancy. You will not need the other SPen libraries (or assets, etc) since they are all included in this library. Make sure to clean the project (and you might even need to invalidate caches and restart). Also make sure your app targets 5.0+ and min SDK set to 15. I have tested it with the sample which was included in the Samsung SDK. I changed the example 2 to use the library in static mode while keeping the rest of the examples as is. When I try any example other than example 2, it asks me to donwload the missing apk, but example 2 works without apk.

Please feel free to improve and enhance as you see fit.


