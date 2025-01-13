# Flutter Utility Snippets

Flutter Utility Snippets is a VSCode extension that provides a collection of frequently used snippets to enhance development efficiency in Flutter and Dart. This extension includes snippets for:

- Flutter: Basic widgets and structures (StatelessWidget, StatefulWidget, Scaffold, etc.)
- Dart: Classes, enums, loops, conditionals, and async processing
- Riverpod: Templates for providers, notifiers, and ConsumerWidget
- Hooks: Support for lifecycle and state management like HookWidget, useEffect, and useState
- Freezed: Templates for Freezed models and JSON support

With this snippet collection, you can speed up your coding process and focus more on building your application.

## Main Features
1. Snippet Categories
- Basic Flutter widgets
- Core Dart structures and async processing
- State management templates with Riverpod
- Lifecycle and state hooks with Flutter Hooks
- Freezed model generation
2. How to Use Snippets
- Open a Dart file in VSCode, type the snippet prefix, and press Tab to expand.
3. Installation
- Download and install this extension in VSCode.
4.Contributing
- Contributions are welcome! Feel free to submit pull requests to improve or add new snippets.

## Snippet List

### Flutter
- `fstless`: Generates a StatelessWidget.
- `fstful`: Generates a StatefulWidget.
- `fscaffold`: Generates a Scaffold widget.
- `frow`: Generates a Row widget.
- `fcolumn`: Generates a Column widget.
- `fstack`: Generates a Stack widget.
- `fcontainer`: Generates a Container widget.
- `fcenter`: Generates a Center widget.
- `ftext`: Generates a Text widget.
- `felevated`: Generates an ElevatedButton widget.
- `ftextbutton`: Generates a TextButton widget.
- `ficonbutton`: Generates an IconButton widget.
- `ficon`: Generates an Icon widget.
- `flisttile`: Generates a ListTile widget.
- `flisttilefull`: Generates a full ListTile widget with leading, title, subtitle, trailing, and onTap callback.
- `fsizedboxwidthheight`: Generates a SizedBox with width and height.
- `fsizedboxwidth`: Generates a SizedBox with width.
- `fsizedboxheight`: Generates a SizedBox with height.
- `fsizedboxshrink`: Generates a SizedBox.shrink().
- `fexpanded`: Generates an Expanded widget.
- `fflexible`: Generates a Flexible widget.
- `fpadding`: Generates a Padding widget.
- `fedgeinsetshorizontal`: Generates EdgeInsets.symmetric(horizontal).
- `fedgeinsetsvertical`: Generates EdgeInsets.symmetric(vertical).
- `fedgeinsetsall`: Generates EdgeInsets.all().
- `fspacer`: Generates a Spacer widget.
- `fdivider`: Generates a Divider widget.
- `fimage`: Generates an Image.asset widget.
- `faddpostframe`: Generates WidgetsBinding.instance.addPostFrameCallback.

### Dart
- `dclass`: Generates a Dart class.
- `denum`: Generates an enum.
- `denumconstructor`: Generates an enum with a constructor.
- `dextension`: Generates an extension on a Dart type.
- `dstring`: Generates the String type.
- `dlist`: Generates a List<dynamic>.
- `dset`: Generates a Set<dynamic>.
- `dmap`: Generates a Map<dynamic, dynamic>.
- `dfuture`: Generates a Future<void> type.
- `dstream`: Generates a Stream<dynamic> type.
- `dvoidmethod`: Generates a void method.
- `dfuturemethod`: Generates a Future method.
- `dstreammethod`: Generates a Stream method.
- `danonfunc`: Generates an anonymous function.
- `darrowright`: Generates a Dart arrow function (=>).
- `dif`: Generates an if statement.
- `difelese`: Generates an if-else statement.
- `delseif`: Generates an else-if statement.
- `delse`: Generates an else statement.
- `dswitch`: Generates a switch statement.
- `dswitchexpr`: Generates a switch expression.
- `dfor`: Generates a for loop.
- `dforin`: Generates a for-in loop.
- `dwhile`: Generates a while loop.
- `dtryoncatch`: Generates a try-on-catch block.
- `dtryoncatchfinally`: Generates a try-on-catch-finally block.
- `dcallback`: Generates a callback function definition.

### Riverpod
- `rkeepalive`: Generates a @Riverpod(keepAlive: true) annotation.
- `rprovider`: Generates a Riverpod Provider template.
- `rasyncprovider`: Generates a Riverpod Async Provider template.
- `rstreamprovider`: Generates a Riverpod Stream Provider template.
- `rnotifier`: Generates a Notifier class template.
- `rfuturenotifier`: Generates a Future Notifier template.
- `rstreamnotifier`: Generates a Stream Notifier template.
- `rlisten`: Generates a ref.listen template.
- `rconsumerwidget`: Generates a ConsumerWidget template.
- `rconsumer`: Generates a Consumer widget.
- `rhookconsumer`: Generates a HookConsumer widget.

### Hooks
- `hhookwidget`: Generates a HookWidget template.
- `huseeffect`: Generates a useEffect template.
- `husestate`: Generates a useState template.
- `husetextcontroller`: Generates a useTextEditingController template.
- `huseonapplifecycle`: Generates a useOnAppLifecycleStateChange template.

Freezed
- `@fmodel`: Generates a Freezed model.
- `@fjson`: Generates a Freezed model with JSON serialization support.
- `@fstate`: Generates a Freezed state template.