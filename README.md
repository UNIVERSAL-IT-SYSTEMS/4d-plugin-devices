# 4d-plugin-devices
List connected CD/DVD drives

Example
---
```
PLATFORM PROPERTIES($platform)

Case of 
: ($platform=Mac OS)

DEVICES LIST (\
$displayNames;\
$physicalInterconnects;\
$vendorNames;\
$productNames;\
$writesCDs;\
$writesDVDs)

: ($platform=Windows)

DEVICES LIST (\
$logicalDriveStrings;\
$mediaType)

End case 
```
