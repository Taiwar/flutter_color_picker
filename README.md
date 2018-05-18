# flutter_color_picker

A simple color picker for Flutter

- [x] Material Primary Colors
- [x] Material Accents Colors
- [ ] RGB Colors

### See usage [here](https://github.com/dart-flitter/flitter)

### Basic usage

```dart
Color color = await showDialog(
        context: context,
        builder: (BuildContext context) {
          return new PrimaryColorPickerDialog();
        }
    );

Color color = await showDialog(
        context: context,
        builder: (BuildContext context) {
          return new AccentColorPickerDialog();
        }
    );
```