# Flutter Training Outline

### 1. Introduction
#### 1.1. Goal
- This is an outline for the interns to learning Flutter.
- The mentor will base on this document to orientate and evaluate the knowledge of interns.
#### 1.1. Timing
- Total: ~400 hours.
### 2. References

- Dart document: [Here](https://dart.dev/guides).
- Flutter document: [Here](https://flutter.dev/docs).
- Course: [Flutter & Dart - The Complete Guide](https://www.udemy.com/course/learn-flutter-dart-to-build-ios-android-apps/).

### 3. Syllabus
#### 3.1. Dart programing language (~40 hours)

No | Topic | Content | Reading | Exercise | Timing (hours)
--- | --- | --- | --- | --- | ---
1 | Variables | - Declaring variables <br> - Default value <br> - Late variables <br> - Final and const <br> - Sound null safety | [1] [Variables](https://dart.dev/guides/language/language-tour#variables) <br> [2] [Null safety](https://dart.dev/null-safety) | [1] [Variables](Exercises/Dart/1.%20Variables)| 4
2 | Data Types | - Numbers (int, double) <br> - Strings <br> - Booleans <br> - Lists <br> - Sets <br> - Maps <br> - Runes <br> - Symbols <br> - The value null | [1] [Data Types](https://dart.dev/guides/language/language-tour#built-in-types) <br> [2] [Numbers](https://dart.dev/guides/language/numbers) | | 4
3 | Functions | - Parameters <br> - The main() function <br> - Anonymous functions <br> - Return values | [1] [Functions](https://dart.dev/guides/language/language-tour#functions) | | 4
4 | Operators | - Arithmetic operators <br> - Equality and relational operators <br> - Type test operators <br> - Assignment operators <br> - Logical operators <br> - Bitwise and shift operators <br> - Conditional expressions <br> - Cascade notation <br> - Other operators | [1] [Operators](https://dart.dev/guides/language/language-tour#operators) | | 4
5 | Control flow statements | - If and else <br> - For loops <br> - While and do-while <br> - Break and continue <br> - Switch and case <br> - Assert | [1] [Control flow statements](https://dart.dev/guides/language/language-tour#control-flow-statements) | | 4
6 | Exceptions | - Throw <br> - Catch <br> - Finally | [1] [Exceptions](https://dart.dev/guides/language/language-tour#exceptions) | [1] [Exceptions](Exercises/Dart/6.%20Exceptions)| 4
7 | Classes | - Constructors <br> - Abstract classes <br> - Class Inheritance <br> - Class Mixins | [1] [Classes](https://dart.dev/guides/language/language-tour#classes) <br> [2] [Extension methods](https://dart.dev/guides/language/extension-methods) | | 8
8 | Asynchronous programming | - Handling Futures <br> - Declaring async functions <br> - Streams | [1] [Asynchrony support](https://dart.dev/guides/language/language-tour#asynchrony-support) <br> [2] [Async-await](https://dart.dev/codelabs/async-await) <br> [3] [Streams](https://dart.dev/tutorials/language/streams) | | 4
9 | Effective Dart | - The guides <br> - Summary of all rules | [1] [Effective Dart](https://dart.dev/guides/language/effective-dart) <br> [2] [Predefined rule sets](https://dart.dev/tools/linter-rules#predefined-rule-sets) | | 4

#### 3.2. Flutter (~200 hours)

No | Topic | Content | Reading | Exercise | Timing (hours)
--- | --- | --- | --- | --- | ---
1 | Introducing Flutter | - Widgets <br> - Stateful and stateless widgets <br> - Widget lifecycle events <br> - Widget tree and element tree <br> - Keys <br> - Hot reload <br> - External packages | [1] [Widget intro](https://flutter.dev/docs/development/ui/widgets-intro) <br> [2] [Stateless widget](https://api.flutter.dev/flutter/widgets/StatelessWidget-class.html) <br> [3] [Stateful widget](https://api.flutter.dev/flutter/widgets/StatefulWidget-class.html) <br> [4] [Hot reload](https://flutter.dev/docs/development/tools/hot-reload) <br> [5] [Using packages](https://flutter.dev/docs/development/packages-and-plugins/using-packages) <br> [6] [Understanding the Flutter Architecture](https://www.udemy.com/course/learn-flutter-dart-to-build-ios-android-apps/learn/lecture/10459794#overview) <br> [7] [How Flutter & Dart Code Gets Compiled To Native Apps](https://www.udemy.com/course/learn-flutter-dart-to-build-ios-android-apps/learn/lecture/15311806#overview) <br> [8] [Flutter & Material Design](https://www.udemy.com/course/learn-flutter-dart-to-build-ios-android-apps/learn/lecture/10811208#overview) <br> [9] [Stateful & Stateless Widgets](https://www.udemy.com/course/learn-flutter-dart-to-build-ios-android-apps/learn/lecture/14912646#overview) | | 16
2 | Common widgets | - Material Components widgets: <br> &nbsp;&nbsp;&nbsp;&nbsp;+ Material App <br> &nbsp;&nbsp;&nbsp;&nbsp;+ Scaffold <br> &nbsp;&nbsp;&nbsp;&nbsp;+ App Bar <br> - Text widgets: <br> &nbsp;&nbsp;&nbsp;&nbsp;+ Rich Text <br> &nbsp;&nbsp;&nbsp;&nbsp;+ Text <br> - Images and icon widgets: <br> &nbsp;&nbsp;&nbsp;&nbsp;+ Icon <br> &nbsp;&nbsp;&nbsp;&nbsp;+ Image <br> - Input widgets: <br> &nbsp;&nbsp;&nbsp;&nbsp;+ Form <br> &nbsp;&nbsp;&nbsp;&nbsp;+ FormField <br> - Layout widgets: <br> &nbsp;&nbsp;&nbsp;&nbsp;+ Container <br> &nbsp;&nbsp;&nbsp;&nbsp;+ Column <br> &nbsp;&nbsp;&nbsp;&nbsp;+ Row <br> &nbsp;&nbsp;&nbsp;&nbsp;+ Center <br> &nbsp;&nbsp;&nbsp;&nbsp;+ Expanded <br> &nbsp;&nbsp;&nbsp;&nbsp;+ Padding <br> &nbsp;&nbsp;&nbsp;&nbsp;+ SizedBox <br> - Button widgets: <br> &nbsp;&nbsp;&nbsp;&nbsp;+ Elevated Button <br> &nbsp;&nbsp;&nbsp;&nbsp;+ Outlined Button <br> &nbsp;&nbsp;&nbsp;&nbsp;+ Text Button <br> &nbsp;&nbsp;&nbsp;&nbsp;+ Popup Menu Button <br> &nbsp;&nbsp;&nbsp;&nbsp;+ Floating Action Button <br> &nbsp;&nbsp;&nbsp;&nbsp;+ Dropdown Button <br> &nbsp;&nbsp;&nbsp;&nbsp;+ Icon Button <br> - Stack | [1] [Widgets](https://flutter.dev/docs/development/ui/widgets) <br> [2] [Widgets intro](https://flutter.dev/docs/development/ui/widgets-intro) <br> [3] [Layout](https://flutter.dev/docs/development/ui/layout) <br> [4] [Assets and images](https://flutter.dev/docs/development/ui/assets-and-images) <br> [5] [Images](https://flutter.dev/docs/cookbook/images) <br> [6] [Forms](https://flutter.dev/docs/cookbook/forms) | [1] [Common widgets](Exercises/Flutter/2.%20Common%20widgets/README.md) | 24
3 | Scrolling widgets | - Single Child Scroll View <br> - Custom Scroll View <br> - List View <br> - Grid View <br> - Page View | [1] [Scrolling widgets](https://flutter.dev/docs/development/ui/widgets/scrolling) <br> [2] [Lists](https://flutter.dev/docs/cookbook/lists) | [1] [Scrolling widgets](Exercises/Flutter/3.%20Scrolling%20widgets/README.md) | 24
4 | Animations | - Animate a page route transition <br> - Animate a widget using a physics simulation <br> - Animate the properties of a container <br> - Fade a widget in and out | [1] [Page route animation](https://flutter.dev/docs/cookbook/animation/page-route-animation) <br> [2] [Physics simulation](https://flutter.dev/docs/cookbook/animation/physics-simulation) <br> [3] [Animated Container](https://flutter.dev/docs/cookbook/animation/animated-container) <br> [4] [Opacity animation](https://flutter.dev/docs/cookbook/animation/opacity-animation) | | 16
5 | Navigation | - Navigator <br> - Bottom Navigation Bar <br> - Bottom App Bar <br> - Tab Bar and Tab Bar View <br> - Drawer | [1] [Navigation](https://flutter.dev/docs/cookbook/navigation) <br> [2] [Bottom Navigation Bar](https://api.flutter.dev/flutter/material/BottomNavigationBar-class.html) <br> [3] [Bottom App Bar](https://api.flutter.dev/flutter/material/BottomAppBar-class.html) <br> [4] [Tab Bar](https://api.flutter.dev/flutter/material/TabBar-class.html) <br> [5] [Drawer](https://flutter.dev/docs/cookbook/design/drawer) | | 24
6 | Gestures | - GestureDetector <br> - InkWell <br> - Dismissible | [1] [Handling taps](https://flutter.dev/docs/cookbook/gestures/handling-taps) <br> [2] [Ripples](https://flutter.dev/docs/cookbook/gestures/ripples) <br> [3] [Dismissible](https://flutter.dev/docs/cookbook/gestures/dismissible) | | 8
7 | Networking | - Make HTTP request <br> - Make authenticated requests <br> - JSON and serialization <br> - Using packages: http, dio, retrofit | [1] [Networking](https://flutter.dev/docs/cookbook#networking) <br> [2] [JSON and serialization](https://flutter.dev/docs/development/data-and-backend/json) <br> [3] [http package](https://pub.dev/packages/http) <br> [4] [dio package](https://pub.dev/packages/dio) <br> [5] [retrofit package](https://pub.dev/packages/retrofit) <br> [6] [json_serializable package](https://pub.dev/packages/json_serializable) | | 24
8 | Persistence | - Persist data with SQLite <br> - Read and write files <br> - Store key-value data on disk | [1] [SQLite](https://flutter.dev/docs/cookbook/persistence/sqlite) <br> [2] [Read and write files](https://flutter.dev/docs/cookbook/persistence/reading-writing-files) <br> [3] [Store key-value data on disk](https://flutter.dev/docs/cookbook/persistence/key-value) <br> [4] [shared_preferences package](https://pub.dev/packages/shared_preferences) | | 24
9 | State management | - Inherited Widget & Inherited Model <br> - Provider <br> - Riverpod  | [1] [State management](https://flutter.dev/docs/development/data-and-backend/state-mgmt) <br> [2] [Riverpod](https://riverpod.dev/) | | 40

#### 3.3. Build an app (~160 hours)
- An app for debuting with the team.
- Plan the schedule.
- Compliant with Gitflow.
- The mentor reviews code.
