---
sidebarDepth: 2
description: GFImage typically manages assets and dispalys the images
---

# GF Image

![GW Images](https://ik.imagekit.io/ionicfirebaseapp/getwidget/docs/tr:w-800,f-auto/Images-Square_QR9kAzRqOXD.png)

## Images

### Asset Image

Asset image is used to display the images stored locally in the assets folder.

```dart
import 'package:getwidget/getwidget.dart';

GFImageOverlay(
  height: 200,
  width: 300,
  image: AssetImage('your asset image')
)
```

### Network Image

Network image is used to display an image from the internet.

```dart
import 'package:getwidget/getwidget.dart';

GFImageOverlay(
  height: 200,
  width: 300,
  image: NetworkImage('your network image')
)
```

### Image Overlay

![Image Overlay](https://ik.imagekit.io/ionicfirebaseapp/getwidget/docs/tr:w-800,f-auto/Images_-_basic_3x_uHCFyLq7s.png)

Image Overlay is used to set the image in the background and text in the foreground with the `colorFilter` property that takes two colors, and outputs one color

```dart
import 'package:getwidget/getwidget.dart';

GFImageOverlay(
  height: 200,
  width: 300,
  child: Center(
    child: Text('Light Overlay', style:TextStyle(color: GFColors.LIGHT)),
  ),
  image: AssetImage('your asset image'),
  colorFilter: new ColorFilter.mode(Colors.black.withOpacity(0.3),
   BlendMode.darken),
),
```

### Circular Image

![Circular Image](https://ik.imagekit.io/ionicfirebaseapp/getwidget/docs/tr:w-800,f-auto/Images-circular_3x_DOdazHv_R.png)

```dart
import 'package:getwidget/getwidget.dart';

 GFImageOverlay(
   height: 200,
   width: 200,
   shape: BoxShape.circle,
   image:AssetImage('your asset image'),
   boxFit: BoxFit.cover,
 )
```

### Custom Properties

|  |  |
| :--- | :--- |
| **height** | defines the height of the image |
| **width** | defines the width of the image |
| **color** | defines the background color of the image |
| **margin** | image's outer container margin |
| **padding** | image's outer container padding |
| **alignment** | to align the child within the image |
| **boxFit** | how to image should be inscribed into the box |
| **borderRadius** | the corners of the image |
| **border** | the border above the image |

