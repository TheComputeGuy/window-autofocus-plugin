# Window autofocus plugin: window_to_front

A flutter plugin which brings your windows desktop app into focus when triggered.

## Usage

To import this plugin into your flutter module, do the following:

1. Add the plugin into your project as
```
pub add --path ../window_to_front window_to_front
```
Replace ../window_to_front with the path to the root of this project

2. Import the plugin into your main.dart file
```
import 'package:window_to_front/window_to_front.dart';
```
3. Add the following line in the place when you want to bring the app window into focus:
```
WindowToFront.activate();
```