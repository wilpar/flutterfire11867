# flutterfire issues 11867

- Build successfully with firebase_core 2.21 in pubspec, and ios sdk 10.16 preloaded in podfile

- change to 2.22 / 10.17

- remove podfile.lock, run pod install

- flutter run

- fail!

```
✗ flutter run
Launching lib/main.dart on iPhone 15 Pro in debug mode...
Running pod install...                                              5.0s
Running Xcode build...                                                  
 └─Compiling, linking and signing...                         6.1s
Xcode build done.                                           86.0s
Failed to build iOS app
Error (Xcode): Undefined symbols:


Error (Xcode): Linker command failed with exit code 1 (use -v to see invocation)


Could not build the application for the simulator.
Error launching application on iPhone 15 Pro.
```