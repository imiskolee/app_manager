# app_manager
A Desktop Flutter Plugin to manager your application native features

# Features

## Flutter Window Manager

[] Set window position
[] set window max / min
[] enabled / disabled resize window

## File Associate

[] Registing file extension to system, double click file for open it to your application.

##  Application Restart & Safely Exit

[] Restart - Restart your application await your registed callback
[] Exit - Ovveride system exit function and await you exit callback (eg: save your project)


# Examples

```dart

AppManager.registerExitCallback(()async {
  await saveMyProject();
  // ......
});

AppManager.exit();
```












