Custom changes
------------------------------
#### New features:
- Added the parameter `UseAsGrid` to `FlxSprite.loadGraphic` to use the width and height as columns and rows instead
- Added the parameter `Margin` to `FlxSprite.loadGraphic` to set the margin used in the spritesheet
- Added the property `weight` to `FlxObject` to decide which object should push and be pushed

#### Bugfixes:

#### Changes and improvements:
- Made `FlxTween.add` a public method
- Renamed `elasticity` to `bounce` and made it of the type `FlxPoint`
- Changed in `FlxCamera` that not passing `Lerp` in `follow()` doesn't set it to `60 / FlxG.updateFramerate`
