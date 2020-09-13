Custom changes
------------------------------
#### New features:
- Added the parameter `UseAsGrid` to `FlxSprite.loadGraphic` to use the width and height as columns and rows instead
- Added the parameter `Margin` to `FlxSprite.loadGraphic` to set the margin used in the spritesheet
- Added the property `weight` to `FlxObject` to decide which object should push and be pushed
- Added the property `z` to `FlxObject` to use it for sorting with `byZ` in `FlxSort`
- Added the method `finalize()` to `FlxBasic` for after the object has been created and potentially added to a `FlxState` 

#### Bugfixes:

#### Changes and improvements:
- Made `FlxTween.add()` a public method
- Renamed `elasticity` to `bounce` and made it of the type `FlxPoint`
- Changed in `FlxCamera` that not passing `Lerp` in `follow()` doesn't set it to `60 / FlxG.updateFramerate`
- Changed in `FlxCamera` that when passing `null` as `Target` in `follow()` the `deadzone` is not set
