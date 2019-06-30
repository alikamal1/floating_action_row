# floating_action_row

A Flutter package that provides a widget with a row or column of floating action buttons.

<img src="https://raw.githubusercontent.com/niklas-8/floating_action_row/master/assets/1.jpg" width="220px">

## Usage

To use this plugin, add `floating_action_row` as a [dependency in your pubspec.yaml file](https://flutter.io/platform-plugins/).

This package contains three Widgets: `FloatingActionRow`, `FloatingActionRowButton` and `FloatingActionRowDivider`.

### FloatingActionRow

| Property     | Type                           | Description                   | Default           |
|--------------|--------------------------------|-------------------------------|-------------------|
| children     | List<'FloatingActionRowChild'> | Children of this widget       | -                 |
| axis         | Axis                           | Switch between row and column | Axis.horizontal   |
| elevation    | double                         | Drop shadow                   | 6                 |
| color        | Color                          | Background color              | -                 |
| height       | double                         | -                             | 56                |
| padding      | EdgeInsets                     | -                             | EdgeInsets.all(0) |
| borderRadius | BorderRadius                   | -                             | -                 |
| shape        | ShapeBorder                    | -                             | -                 |
| heroTag      | String                         | Tag for Hero animations       | -                 |

Note: `FloatingActionRowButton` and `FloatingActionRowDivider` both extend `FloatingActionRowChild` so that you can use those two widgets as children.

### FloatingActionRowButton

| Property        | Type               | Description                 | Default            |
|-----------------|--------------------|-----------------------------|--------------------|
| icon            | Icon               | Child of this widget        | -                  |
| color           | Color              | Foreground color for [icon] | -                  |
| size            | double             | -                           | -                  |
| padding         | EdgeInsets         | -                           | EdgeInsets.all(0)  |
| shape           | ShapeBorder        | -                           | -                  |
| backgroundColor | Color              | -                           | Colors.transparent |
| onTap           | GestureTapCallback | -                           | -                  |

### FloatingActionRowDivider

| Property | Type       | Description | Default                            |
|----------|------------|-------------|------------------------------------|
| color    | Color      | -           | -                                  |
| width    | double     | -           | 1                                  |
| padding  | EdgeInsets | -           | EdgeInsets.symmetric(vertical: 10) |

## Issues & Feedback

Please file an [issue](https://github.com/niklas-8/floating_action_row/issues) to send feedback or report a bug. Thank you!

## Contributing

Every pull request is welcome.
