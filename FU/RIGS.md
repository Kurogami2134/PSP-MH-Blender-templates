# Bone mappings for MHFU hunter assets

Note: Some models have special animations, so the info in this file may not be accurate for every model. It just contains the data found in most cases.

* Armor rigs are from [Xenthos research](https://github.com/Xenthalos/Blender-Vertex-Group-Renamer/blob/main/presets/MHFU_armor.json).

## Armor

### Head

|Id|Function|
|-|-|
|000|Root|
|001|Bust|
|002|Neck|
|003|Head|

### Body

|Id|Function|
|-|-|
|000|Root|
|001|Hip|
|002|Waist|
|003|Bust|
|004|L_Clavicle|
|005|L_Shoulder|
|006|R_Clavicle|
|007|R_Shoulder|
|008|Neck|
|009|Head|

### Arms

|Id|Function|
|-|-|
|000|Root|
|001|Bust|
|002|L_Clavicle|
|003|L_Shoulder|
|004|L_Elbow|
|005|L_Hand|
|006|R_Clavicle|
|007|R_Shoulder|
|008|R_Elbow|
|009|R_Hand|

### Waist

|Id|Function|
|-|-|
|000|Root|
|001|Hip|
|002|Waist|
|003|L_Leg|
|004|L_Knee|
|005|R_Leg|
|006|R_Knee|

### Legs

|Id|Function|
|-|-|
|000|Root|
|001|?|
|002|Hip|
|003|L_Leg|
|004|L_Knee|
|005|L_Foot|
|006|R_Leg|
|007|R_Knee|
|008|R_Foot|
|009|Waist|
|010|Bust|

## Weapons

#### Notes

* Shields are upside down
* Heavy bowguns are in their sheathed state
* Weapons with special animations may have extra bones that are not detailed here.

### Great Sword

|Id|Function|
|-|-|
|000|Root|
|001|Sword|
|002|Slides down when sheathed|
|003|Scales when unsheathed|

### Long Sword

|Id|Function|
|-|-|
|000|Root|
|001|Sword|
|002|Handle|
|003|?|

* Longsword sheathe appears to be rigged to bone 001 and differentiated only by material in fu. Materials 003 and 004 determine sheathe (for iron katana, may be different in other cases).

### Sword and Shield

|Id|Function|
|-|-|
|000|Root|
|001|Sword|
|002|Stretch when unsheathed|
|003|Shield root|
|004|Shield|

### Dual Blades

|Id|Function|
|-|-|
|000|Left root|
|001|Left sword|
|002|Left tip|
|003|Right root|
|004|Right sword|

### Hammer

|Id|Function|
|-|-|
|000|Root|
|001|Hammer|
|002|?|
|003|?|

### Hunting Horn

|Id|Function|
|-|-|
|000|Root|
|001|Horn|
|002|Swinging part|
|003|Oscilating part|

### Lance

|Id|Function|
|-|-|
|000|Root|
|001|Lance|
|002|Tip|
|003|Shield root|
|004|Shield|

### Gunlance

|Id|Function|
|-|-|
|000|Root|
|001|Body|
|002|Tip|
|003|Wyvern Exhaust|
|004|Shield root|
|005|Shield|

### Bowguns

|Id|Function|
|-|-|
|000|Root|
|001|Body|
|002|Bendable|
|003|Bow|

### Bow

|Id|Function|
|-|-|
|000|Root|
|001|Top arm of the bow|
|002|Bottom arm of the bow|
|003|String|
|004|Quiver Root|
|005|Quiver|
