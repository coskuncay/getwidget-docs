---
sidebarDepth: 2
description: Pills Button looks like a solid button with rounded corners.
---

# Flutter Pills Button

![Pills Button](https://ik.imagekit.io/ionicfirebaseapp/getwidget/docs/tr:w-800,f-auto/Pills_button-solid_VWUMopUjx_.png)

We will able to get pills shaped button with solid background color with rounded corners by adding property **shape** with `GFButtonShape.pills` .

```dart
import 'package:getwidget/getwidget.dart';

GFButton(
    onPressed: (){},
    text: "primary",
    shape: GFButtonShape.pills,
  ),
```

## Solid Button

![Solid Button](https://ik.imagekit.io/ionicfirebaseapp/getwidget/docs/tr:w-800,f-auto/pills-solid-button-2x_EQT2X6jAl_BLgdXpw26c7E.png)

By default, button **type** set to `GFButtonType.solid` so, we able to get pills shaped button have a solid background color with rounded corners.

The callback that is called when the button is tapped. By adding callback to **onPressed** enables the button.

```dart
import 'package:getwidget/getwidget.dart';

  GFButton(
    onPressed: (){},
    text: "primary",
    shape: GFButtonShape.pills,
  ),
```

## Disabled Button

![Disabled Button](https://ik.imagekit.io/ionicfirebaseapp/getwidget/docs/tr:w-800,f-auto/pills-disabled-2x_lVoPerI-o_-pNn9kds88.png)

If this callback and **onPressed** are null, then the button will be disabled. Default GFButton will be disabled because, **onPressed** set to null.

```dart
import 'package:getwidget/getwidget.dart';

GFButton(
    onPressed: null,
    text: "primary",
    shape: GFButtonShape.pills,
 ),
```

## Block Button

![Block Button](https://ik.imagekit.io/ionicfirebaseapp/getwidget/docs/tr:w-800,f-auto/block-buttons-2x_gd1aXxKLI_YTwXCQ0t0.png)

Block button specify how wide the button should be. By setting **blockButton** state `true`, it will change the button to a full-width block with rounded corners. Default **blockButton** set to `false`.

```dart
import 'package:getwidget/getwidget.dart';

GFButton(
    onPressed: (){},
    text: "primary",
    shape: GFButtonShape.pills,
    blockButton: true,
 ),
```

## Full Width Button

![Full Width Button](https://ik.imagekit.io/ionicfirebaseapp/getwidget/docs/tr:w-800,f-auto/full-width-2x_pKifhtU6P_908jFrHjHx.png)

Full Width button specify how wide the button should be. By setting **fullWidthButton** state `true`, it will change the button to a Full-width button with rounded corners and no border on the left or right. Default **fullWidthButton** set to `false`.

```dart
import 'package:getwidget/getwidget.dart';

GFButton(
    onPressed: (){},
    text: "primary",
    shape: GFButtonShape.pills,
    fullWidthButton: true,
 ),
```

## Button Size

Button size can be varied using **size** property, which specifies the size of the button. Default button size set to `GFSize.MEDIUM`.

```dart
import 'package:getwidget/getwidget.dart';

GFButton(
    onPressed: (){},
    text: "primary",
    shape: GFButtonShape.pills,
    size: GFSize.SMALL,
 ),
```

## Outline Button

![Outline Button](https://ik.imagekit.io/ionicfirebaseapp/getwidget/docs//pills-outline-2x_iq1SEFIpR_yeuxE-DmfT.png)

Outline Button describes as the Button with a transparent background and a visible border. This button can be easily get in GFButton by adding **type** as **`GFButtonType.outline`**.

```dart
import 'package:getwidget/getwidget.dart';

GFButton(
    onPressed: (){},
    text: "primary",
    shape: GFButtonShape.pills,
    type: GFButtonType.outline,
 ),
```

Above mentioned all the properties like `size`, `blockButton`, `fullWidthButton`, enabling and disabling of button works fine in **Outline Button** also.

## Outline2x Button

![Outline2x Button](https://ik.imagekit.io/ionicfirebaseapp/getwidget/docs/tr:w-800,f-auto/pills-outline-2x-2x_Qez5VXh02_zOFwwDB3SRU.png)

Outline2x Button describes as the Button with a transparent background and a visible border with 2x border-width. This button can be easily get in GFButton by adding **type** as **`GFButtonType.outline2x`**.

```dart
import 'package:getwidget/getwidget.dart';

GFButton(
    onPressed: (){},
    text: "primary",
    shape: GFButtonShape.pills,
    type: GFButtonType.outline2x,
 ),
```

Above mentioned all the properties like `size`, `blockButton`, `fullWidthButton`, enabling and disabling of button works fine in **Outline2x Button** also.

