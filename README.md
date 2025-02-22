# Flutter Utility Snippets


Flutter Utility Snippets is a VSCode extension that provides a collection of frequently used snippets to enhance development efficiency in Flutter and Dart. This extension includes snippets for:

- Flutter: Basic widgets and structures (StatelessWidget, StatefulWidget, Scaffold, etc.)
- Dart: Classes, enums, loops, conditionals, and async processing
- Riverpod: Templates for providers, notifiers, and ConsumerWidget
- Hooks: Support for lifecycle and state management like HookWidget, useEffect, and useState
- Freezed: Templates for Freezed models and JSON support

With this snippet collection, you can speed up your coding process and focus more on building your application.

![Image](https://github.com/user-attachments/assets/0bc56022-4ed4-4111-b1c0-5e0837e78d6a)

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

Flutter SDK-related snippets use prefixes starting with `f`.

**Widgets**
- `fstateless`: Generates a StatelessWidget with imports.
- `fstatelessnoimport`: Generates a StatelessWidget without imports.
- `fstateful`: Generates a StatefulWidget with imports.
- `fstatefulnoimport`: Generates a StatefulWidget without imports.
- `fscaffold`: Generates a Scaffold widget.
- `fcenter`: Generates a Center widget.
- `fcolumn`: Generates a Column widget.
- `frow`: Generates a Row widget.
- `fstack`: Generates a Stack widget.
- `fcontainer`: Generates a Container widget.
- `ftext`: Generates a Text widget.
- `felevated`: Generates an ElevatedButton widget.
- `ftextbutton`: Generates a TextButton widget.
- `ficonbutton`: Generates an IconButton widget.
- `ficon`: Generates an Icon widget.
- `flisttile`: Generates a ListTile widget.
- `flisttilefull`: Generates a full ListTile widget with leading, title, subtitle, trailing, and onTap callback.

**Layout Widgets**
- `fsizedboxwidthheight`: Generates a SizedBox with width and height.
- `fsizedboxwidth`: Generates a SizedBox with width.
- `fsizedboxheight`: Generates a SizedBox with height.
- `fsizedboxshrink`: Generates a SizedBox.shrink().
- `fexpanded`: Generates an Expanded widget.
- `fflexible`: Generates a Flexible widget.
- `fpadding`: Generates a Padding widget.

**EdgeInsets**
- `fedgeinsetshorizontal`: Generates EdgeInsets.symmetric(horizontal).
- `fedgeinsetsvertical`: Generates EdgeInsets.symmetric(vertical).
- `fedgeinsetsall`: Generates EdgeInsets.all().

**Spacing and Dividers**
- `fspacer`: Generates a Spacer widget.
- `fdivider`: Generates a Divider widget.

**Images**
- `fimage`: Generates an Image.asset widget.

**Utilities**
- `faddpostframe`: Generates WidgetsBinding.instance.addPostFrameCallback.
- `fbuildcontext`: Generates BuildContext context.

---
### Dart

Dart-related snippets use prefixes starting with `d`.

**Class, Enum, and Extension**
- `dclass`: Generates a Dart class.
- `denum`: Generates a Dart enum.
- `denumconstructor`: Generates an enum with a constructor and a field.
- `dextension`: Generates a Dart extension on a specific type.
**Basic Data Types**
- `dstring`: Generates String.
**Collection Types**
- `dlist`: Generates List<dynamic>.
- `dset`: Generates Set<dynamic>.
- `dmap`: Generates Map<dynamic, dynamic>.
**Asynchronous Operations**
- `dfuture`: Generates Future<void>.
- `dstream`: Generates Stream<dynamic>.
**Methods**
- `dvoidmethod`: Generates a void method.
- `dfuturemethod`: Generates an async method that returns Future<void>.
- `dstreammethod`: Generates an async* method that returns Stream<dynamic>.
**Functions**
- `danonfunc`: Generates an anonymous function.
- `darrowright`: Generates the right-hand side of an arrow function.
**Control Structures**
- `dif`: Generates an if statement.
- `difelese`: Generates an if-else statement.
- `delseif`: Generates an else if statement.
- `delse`: Generates an else block.
- `dswitch`: Generates a switch statement.
- `dswitchexpr`: Generates a switch expression with pattern matching.
- `dfor`: Generates a standard for loop.
- `dforin`: Generates a for-in loop.
- `dwhile`: Generates a while loop.
**Exception Handling**
- `dtryoncatch`: Generates a try-on-catch block.
- `dtryoncatchfinally`: Generates a try-on-catch-finally block.
**Callbacks**
- `dcallback`: Generates a callback function signature.

---
### Riverpod

Riverpod-related snippets use prefixes starting with `r`.

**Annotations**
- `rkeepalive`: Generates a @Riverpod(keepAlive: true) annotation.

**Providers**
- `rprovider`: Generates a Riverpod provider template with imports and part directive.
- `rprovidernoimport`: Generates a simplified Riverpod provider template without ****imports and part directive.
- `rasyncprovider`: Generates a Riverpod async provider template with imports and **part directive.
- `rasyncprovidernoimport`: Generates a simplified Riverpod async provider template without imports and part directive.
- `rstreamprovider`: Generates a Riverpod stream provider template with imports and part directive.
- `rstreamprovidernoimport`: Generates a simplified Riverpod stream provider template without imports and part directive.

**Notifiers**
- `rnotifier`: Generates a Riverpod notifier template.
- `rfuturenotifier`: Generates a Riverpod future notifier template.
- `rstreamnotifier`: Generates a Riverpod stream notifier template.

**Listening**
- `rlisten`: Generates a ref.listen statement template.

**Widgets**
- `rconsumerwidget`: Generates a ConsumerWidget class template.
- `rconsumer`: Generates a Consumer widget template.
- `rhookconsumer`: Generates a HookConsumer widget template.

**Utility**
- `rwidgetref`: Generates a WidgetRef ref declaration.

**Patterns**
- rwhen: Generates a Riverpod AsyncValue.when template to handle data, loading, and error states.
- rswitch: Generates a switch statement template for AsyncValue to handle AsyncError, AsyncData, and the default case.

---
### Hooks

Hooks-related snippets use prefixes starting with `h`.

- `hhookwidget`: Generates a HookWidget template.
- `huseeffect`: Generates a useEffect template.
- `husestate`: Generates a useState template.
- `husetextcontroller`: Generates a useTextEditingController template.
- `huseonapplifecycle`: Generates a useOnAppLifecycleStateChange template.

---
### Freezed

Freezed-related snippets use prefixes starting with `@f`.

- `@fmodel`: Generates a Freezed model.
- `@fjson`: Generates a Freezed model with JSON serialization support.
- `@fstate`: Generates a Freezed state template.

---
### Test
Test-related snippets use prefixes starting with `t`.

**Unit Test**
- `tunittesttemp`: Generates a Flutter unit test template with Riverpod support.
- `twidgettesttemp`: Generates a Flutter widget test template with Riverpod.
- `twidgettestpatroltemp`: Generates a Flutter widget test template with Patrol and Riverpod.

**Groups and Tests**
- `tgroup`: Generates a Flutter test group template.
- `ttest`: Generates a Flutter test template.
- `twidgets`: Generates a Flutter testWidgets template.
- `twidgetspatrol`: Generates a Flutter patrolWidgetTest template.
- `tsetup`: Generates a Flutter setUp template for test setup.

**Async Test Operations**
- `trunasyncpatrol`: Generates a runAsync template for Patrol.
- `trunasynctestwidgets`: Generates a runAsync template for testWidgets.

**Tester Usage**
- `tpatroltester`: Generates a basic Patrol tester usage template.
- `ttester`: Generates a basic Flutter tester usage template.

**Mocking**
- `tmockspec`: Generates a MockSpec instance for mocking a class.
- `tmockclass`: Generates a mock class template using Mockito.

---
### Comment

Comment-related snippets use prefixes starting with `c`.

**TODO and Notes**
- `ctodo`: Inserts a // TODO: comments comment.
- `cinfo`: Inserts a // INFO: comments comment.
- `chack`: Inserts a // HACK: comments comment.
- `cfixme`: Inserts a // FIXME: comments comment.

**Coverage**
- `ccoverignorefile`: Inserts a // coverage:ignore-file comment.
- `ccoverignorestart`: Inserts a // coverage:ignore-start comment.
- `ccoverignoreend`: Inserts a // coverage:ignore-end comment.
