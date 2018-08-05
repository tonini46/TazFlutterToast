# TazFlutterToast


Android Toast Library for Flutter

> Supported  Platforms
> * Android
> * IOS

## How to Use

```yaml
# add this line to your dependencies
tazfluttertoast: ^0.0.1
```

```dart
Tazfluttertoast.showToast(
        icon: ToastIcon.person,
        msg: "This is Center Short Toast",
        toastLength: Toast.LENGTH_SHORT,
        gravity: ToastGravity.CENTER,
        timeInSecForIos: 1,
        bgcolor: "#e74c3c",
        textcolor: '#ffffff'
    );
```

property | description
--------|------------
icon | ToastIcon.(Material Icon type) (Not Null)(required)
msg | String (Not Null)(required)
toastLength| Toast.LENGTH_SHORT or Toast.LENGTH_LONG (optional)
gravity | ToastGravity.TOP (or) ToastGravity.CENTER (or) ToastGravity.BOTTOM
timeInSecForIos | int (only for ios)
bgcolor | string (color in hex format)
textcolor| '#ffffff'
