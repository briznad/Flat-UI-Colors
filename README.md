# Flat UI Colors

Extend your color palette with FLatUI colors from https://flatuicolors.com/palette/defo

![alt tag](https://raw.githubusercontent.com/briznad/Swift-Flat-UI-Colors/master/Flat_UI_Palette.png)

## Usage

### Swift
```swift
UIColor.turquoise()
UIColor.greenSea()
UIColor.emerald()
UIColor.nephritis()
UIColor.peterRiver()
UIColor.belizeHole()
UIColor.amethyst()
UIColor.wisteria()
UIColor.wetAsphalt()
UIColor.midnightBlue()
UIColor.sunflower()
UIColor.orange()
UIColor.carrot()
UIColor.pumpkin()
UIColor.alizarin()
UIColor.pomergranate()
UIColor.clouds()
UIColor.silver()
UIColor.concrete()
UIColor.asbestos()
```
Example
```swift
CancelButton.backgroundColor = UIColor.alizarin()
```

### SASS
```sass
map-get($colors, turquoise);
map-get($colors, green_sea);
map-get($colors, emerald);
map-get($colors, nephritis);
map-get($colors, peter_river);
map-get($colors, belize_hole);
map-get($colors, amethyst);
map-get($colors, wisteria);
map-get($colors, wet_asphalt);
map-get($colors, midnight_blue);
map-get($colors, sun_flower);
map-get($colors, orange);
map-get($colors, carrot);
map-get($colors, pumpkin);
map-get($colors, alizarin);
map-get($colors, pomegranate);
map-get($colors, clouds);
map-get($colors, silver);
map-get($colors, concrete);
map-get($colors, asbestos);
```
Example
```sass
.element {
  color: map-get($colors, belize_hole);
}
```
