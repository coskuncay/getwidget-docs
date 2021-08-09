---
sidebarDepth: 2
description: >-
  Badge contains a number or other characters. They can be used as a
  notification that there are additional items associated with an element and
  indicate how many items there are.
---

# GF Flutter Badge

![GF Flutter Badges Widget](https://ik.imagekit.io/ionicfirebaseapp/getwidget/docs/tr:w-800,f-auto/Badges_v0v7rCbeO.png)

### GF Flutter Badges

Typically GFBadge takes text widget as child, to display number or characters inside badges.

```dart
import 'package:getwidget/getwidget.dart';

GFBadge(
  onPressed: (){},
  child: Text("12"),
),
```

### GF Flutter Badge Size

Badge size can be varied using **size** property, which specifies the size of the badge. Default badge size set to `GFSize.medium`.

```dart
import 'package:getwidget/getwidget.dart';

GFBadge(
    onPressed: (){},
    child: "primary",
    size: GFSize.small,
 ),
```

### GF Flutter Badge Shape

Shape of Badge can be changed by setting property **shape** to `GFIconButtonShape.circle`. Default shape of the Badge set to `GFIconButtonShape.standard` which gives square shaped IconButton with slightly rounded corners.

```dart
import 'package:getwidget/getwidget.dart';

GFBadge(
    onPressed: (){},
    child: "primary",
    shape: GFIconButtonShape.pills,
 ),
```

|  |  |
| :--- | :--- |
| **Description** | The GFBadge Shape |
| **Attribute** | shape |
| **Type** | `GFBadgeShape.standard, GFBadgeShape.square, GFBadgeShape.pills, GFBadgeShape.circle` |
| **Default** | `GFButtonShape.standard` |

### GF Flutter Badge Custom Properties

| Name | Description |
| :--- | :--- |
| **child** | child of type \[widget\] alternative to text |
| **textcolor** | the color to use for this badge;s text |
| **textStyle** | defines the styling of the text |
| **border** | defines the border side |
| **bordershape** | defines the shape of the border |
| **color** | GFColor is used to change the background of the button. |

### Flutter Button with Badges

Badges can be used with button to display, the badges with label and GFButton properties.

```dart
import 'package:getwidget/getwidget.dart';

GFButtonBadge(
  onPressed: () {},
  text: 'primary',
  icon: GFBadge(
    child: Text("12"),
  ),
),
```

Default button **shape** set to `GFButtonShape.standard` so that we will able to get standard shaped button with solid background color with slightly rounded corners.

### Flutter Solid Button Badge

![Flutter Solid Button Badge](https://ik.imagekit.io/ionicfirebaseapp/getwidget/docs/tr:w-800,f-auto/solid-badge-buttons-2x_AEtC9rqrH_9WGUj7cmx.png)

By default, button **type** set to `GFType.solid` so, we able to get buttons have a solid background color with slightly rounded corners.

The callback that is called when the button is tapped. By adding callback to **onPressed** enables the button.

```dart
import 'package:getwidget/getwidget.dart';

GFButtonBadge(
  onPressed: (){},
  text: "primary",
  icon: GFBadge(
    child: Text("12"),
  ),
),
```

### Flutter Disabled Button Badge

![Flutter Disabled Button Badge](https://ik.imagekit.io/ionicfirebaseapp/getwidget/docs/tr:w-800,f-auto/disabled-badge-buttons-2x_pRTAZyWWe_DdAbyhxxOt.png)

If this callback and **onPressed** are null, then the button will be disabled. Default GFButton will be disabled because, **onPressed** set to null.

```dart
import 'package:getwidget/getwidget.dart';

GFButtonBadge(
    onPressed: null,
    text: "primary",
    icon: GFBadge(
       child: Text("12"),
     ),
 ),
```

### Flutter Outline Button Badge 

![Flutter Outline Button Badge ](https://ik.imagekit.io/ionicfirebaseapp/getwidget/docs/tr:w-800,f-auto/outline-badge-buttons-2x-1_-Tow_mzA3_uCCZDyDrN.png)

Outline Button describes as the Button with a transparent background and a visible border. This button can be easily get in GFButton by adding **type** as **`GFType.outline`**.

```dart
import 'package:getwidget/getwidget.dart';

GFButtonBadge(
    onPressed: (){},
    text: "primary",
    icon: GFBadge(
      child: Text("12"),
    ),
    type: GFType.outline,
 ),
```

### Flutter Pills Button Badge   

We will able to get pills shaped button with solid background color with rounded corners by adding property **shape** with `GFButtonShape.pills` .

```dart
import 'package:getwidget/getwidget.dart';

  GFButtonBadge(
    onPressed: (){},
    text: "primary",
    icon: GFBadge(
      child: Text("12"),
    ),
    shape: GFButtonShape.pills,
  ),
```

### Flutter Button Badge Size

Button size can be varied using **size** property, which specifies the size of the button. Default button size set to `GFSize.medium`.

```dart
import 'package:getwidget/getwidget.dart';

GFButtonBadge(
    onPressed: (){},
    text: "primary",
    icon: GFBadge(
      child: Text("12"),
    ),
    size: GFSize.small,
 ),
```

### GF Badge Custom Properties

GF Button Badge can be styled with several attributes to look a specific way. Each and every attribute is described below.

#### How to change flutter badge color?

GFColor is used to change the background of the button.

|  |  |
| :--- | :--- |
| **Description** | The color to use from application's color pallete |
| **Attribute** | color |
| **Type** | `GFColor` |
| **Default** | `GFColor.primary` |

#### How to change badge size in flutter?

|  |  |
| :--- | :--- |
| **Description** | The GFButtonBadge Size |
| **Attribute** | size |
| **Type** | `GFSize.large,  GFSize.medium, GfSize.small` |
| **Default** | `GFSize.medium` |

#### Flutter badge shape

|  |  |
| :--- | :--- |
| **Description** | The GFButtonBadge Shape |
| **Attribute** | shape |
| **Type** | `GFButtonShape.standard, GFButtonShape.square, GFButtonShape.pills` |
| **Default** | `GFButtonShape.standard` |

#### Flutter Badges Type 

|  |  |
| :--- | :--- |
| **Description** | The GFButtonBadge Type |
| **Attribute** | type |
| **Type** | `GFType.solid, GFType.outline, GFType.outline2x, GFType.transparent` |
| **Default** | `GFType.solid` |

#### Flutter Badge custom position properties

|  |  |
| :--- | :--- |
| **Description** | The GFButtonBadge Position |
| **Attribute** | position |
| **Type** | `GFPosition.start, GFPosition.end` |
| **Default** | `GFPosition.start` |

### GF Badge More custom Properties

| Name | Description |
| :--- | :--- |
| **onPressed** | callback i.e, called when the button is tapped |
| **onLongPressed** | callback i.e, called when the button is long-pressed |
| **text** | text of type \[string\] to describe button's label. text will be priority over child |
| **icon** | icon of type \[widget\] to describe button's label with icon |
| **child** | child of type \[widget\] alternative to text |
| **textcolor** | the color to use for this button's text when the button is enabled |
| **textStyle** | defines the styling of the text |
| **disabledColor** | the fillcolor of  the button when the button is disabled |
| **disabledTextColor** | the color to use for this button's text when the button is disabled |
| **borderSide** | defines the border side |
| **bordershape** | defines the shape of the border |
| **buttonBoxShadow** | if `true,` default boxShadow appears around button. |
| **boxShadow** | defines the boxShadow |
| **fullWidthButton** | if `true,` defines the full width of the button. |
| **blockButton** | if `true`, defines the block button. |
| **padding** | defines internal padding of the button |
| **focusColor** | fillColor of the button when it has the input focused |
| **hoverColor** | fillColor of the button when the pointer is hovered over it |
| **splashColor** | indicates that the button has been touched |
| **highlightColor** | indicates that the button is actively being pressed |

### Flutter Icon Badge Button  

Badges can be used with button to display, the badges with icons and GFIconButton properties.

```dart
import 'package:getwidget/getwidget.dart';

GFIconBadge(
  child: GFIconButton(
   onPressed: (){},
   icon: Icon(Icons.ac_unit),
  ),
  counterChild: GFBadge(
    child: Text("12"),
  ),
),
```

Default icon button **shape** set to `GFButtonShape.standard` so that we will able to get standard shaped button with solid background color with slightly rounded corners.

### Flutter Icon Button Badge Size

Button size can be varied using **size** property, which specifies the size of the button. Default button size set to `GFSize.medium`.

```dart
import 'package:getwidget/getwidget.dart';

GFIconBadge(
  child: GFIconButton(
   onPressed: (){},
   icon: Icon(Icons.ac_unit),
   size: GFSize.large,
  ),
  counterChild: GFBadge(
    child: Text("12"),
  ),
),
```

### Flutter Icon Button Badge Type

Button type can be changed using property **type** by setting to `GFType.outline`. Default type of the IconButton will be `GFType.solid`.

```dart
import 'package:getwidget/getwidget.dart';

 GFIconBadge(
  child: GFIconButton(
   onPressed: (){},
   icon: Icon(Icons.ac_unit),
   type: GFType.outline,
  ),
  counterChild: GFBadge(
    child: Text("12"),
  ),
),
```

### Flutter Icon Button Badge Shape

Shape of Icon Button can be changed by setting property **shape** to `GFIconButtonShape.circle`. Default shape of the IconButton set to `GFIconButtonShape.standard` which gives square shaped IconButton with slightly rounded corners.

```dart
import 'package:getwidget/getwidget.dart';

GFIconBadge(
  child: GFIconButton(
   onPressed: (){},
   icon: Icon(Icons.ac_unit),
   shape: GFIconButtonShape.pills,
  ),
  counterChild: GFBadge(
    child: Text("12"),
  ),
),
```

|  |  |
| :--- | :--- |
| **Description** | The GFIconButton Shape |
| **Attribute** | shape |
| **Type** | `GFIconButtonShape.standard, GFIconButtonShape.square, GFIconButtonShape.pills, GFIconButtonShape.circle` |
| **Default** | `GFIconButtonShape.standard` |

### Flutter Icon Button Custom Properties

| Name | Description |
| :--- | :--- |
| **child** | child of type \[widget\] alternative to text |
| **textcolor** | the color to use for this badge;s text |
| **textStyle** | defines the styling of the text |
| **borderSide** | defines the border side |
| **bordershape** | defines the shape of the border |
| **color** | GFColor is used to change the background of the button. |
| **iconSize** | defines the size of icon |
| **buttonBoxShadow** | if `true,` default boxShadow appears around button. |
| **boxShadow** | defines the boxShadow |

