# flutter_3d_choice_chip

This package provides simple 3D choice chip.

## Getting Started

Import the file.

```
import 'package:flutter_3d_choice_chip/flutter_3d_choice_chip.dart';
```

### Use with default style:

```
ChoiceChip3d(
  style: Button3dStyle.BLUE, // Button3dStyle.RED, Button3dStyle.WHITE
  selected: true,
  onSelected: () {},
  onUnselected: () {},
  child: Text("My Choice"),
);
```

### Use with custom style:

```
ChoiceChip3d(
  style: ChoiceChip3dStyle(
      topColor: Colors.lightGreen,
      backColor: Colors.deepOrange,
      borderRadius: BorderRadius.zero
  ),
  onSelected: () {},
  onUnselected: () {},
  child: Text("My Choice"),
);
```

### Credit

Flutter 3D Choice Chip was inspired by [button3d](https://github.com/nguyenvanduocit/button3d)