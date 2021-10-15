# Flutter Basics

Nick Manning has a wonderful YouTube course and also available in the freecodecamp which clearly explains how to build a simple navigation app. (Tourism doc)


Overall - this is one of the best video on flutter I have seen so far.


Summary of the Video

- flutter can be used to develop apps for web, iOS and android

- Flutter main.dart is the file it starts
- pubspec.yaml is the default project file for flutter
- the pubspec flie contains the assets, fonts to be used, and also the package dependencies.
- flutter uses mainaxisalignment a concepts similar to cuss flex box to arrange items
- the dart language seems to be more suitable to arrange the components in a ui similar to react components
- each component in flutter is called as widget. This corresponds to a class widget
- we can build any complex ui by just using widget class and wrapping the elements


Widget building
- the default method build widget in the main function in the app is responsible for creating the main container
- through route factory we can route to different screens
- supports generics `List<location>`
- syntax almost similar to modern programming with few differences in using the parentheses and curly braces.
- flutter uses the curly braces for function declarations and most of the time it uses the parenthesis to initialise a class directly via the default constructor.
- flutter uses single quote for strings


```
class LocationDetail(){

final fact=''

LocationDetail(this.fact) // => this is directly initialise the class variable.

}

```











