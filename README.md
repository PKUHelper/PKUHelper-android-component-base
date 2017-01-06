# PKUHelper-android-component-base

This ~~is~~ will be a base part of Android component wrapper for PKU Helper for Android.

To better manage PKU Helper for Android in an *open source way* in the future, [@Luolc](https://github.com/Luolc) has been doing research on **Modular Android Develop** currently and got a preliminary conclusion relatived to this part as following.

- A cross-module **Route Framework** is indispensable.
- To simplify dependencies among the modules, a **Dependency Injection Framework** should be considered. For Android client it could be `Dagger` for most cases.

Since the native implementation by *scheme* in Android is sort of ugly, we had better wrap a lite framework by ourselves, better with `apt` technique.

As a result, [@Luolc](https://github.com/Luolc) is developing a simple Route Framework, until which is completed there will be very likely no progress in the repository.