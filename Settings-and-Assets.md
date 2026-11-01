# Settings and assets

Open the game's Options screen and choose Street Studio. The integrated intersection editor also registers its own settings.

## Main settings

The current source exposes options for toolbar visibility, playset isolation, saving used roads, thumbnail arrows, automatic game-road conversion and several appearance replacements.

Appearance settings include traffic lights, far-side traffic-light placement, signs, street lights, sidewalk textures, road textures and lane-line display. A visible setting does not guarantee that a suitable replacement asset is available or that every road type supports the change.

Advanced options include unrestricted lanes, lock requirements, safety measures and automatic side sections. These change validation or generation behavior. Keep the defaults while learning the tool.

The older all-roads vanilla-marking mutation system is not registered in the current mod initialization. Do not interpret its retained setting name as a supported city-wide marking replacement workflow.

## Optional assets

| Feature | Requirement |
| --- | --- |
| US traffic-light appearance replacement | Loaded US Traffic Lights and Street Lights Pack; the UI identifies Paradox Mods item 165222. |
| RRFB crossing beacons | Loaded compatible RRFB assets; the original project documentation identifies Rectangular Rapid Flashing Beacons Set, item 159237. |
| Picker islands | The corresponding built island models loaded in the active playset. |
| Parking meters | SolarPayStation asset plus an adjacent sidewalk. |
| Birch planters | Compatible birch and planter objects. |
| Object/texture swaps | A compatible, loaded replacement object or surface. |

These are optional visual dependencies, not a requirement to install the original Road Builder or Town Road Lane code mods.

## Object and texture swaps

The **More** tab provides entries to swap signs, bollards and other objects, and to swap sidewalk, road and crosswalk textures. Choose replacements appropriate to the object/surface being replaced. Appearance swaps do not change simulation rules automatically.

## Broad conversions

**Convert every game road in the city** and **Convert every road of this type** affect many segments and explicitly warn that they cannot be undone. Save a separate copy of your city before using either command.

## Local storage

```text
Designs:  %USERPROFILE%\AppData\LocalLow\Colossal Order\Cities Skylines II\ModsData\StreetStudio
Settings: %USERPROFILE%\AppData\LocalLow\Colossal Order\Cities Skylines II\ModsSettings\StreetStudio
```

Back up the city and its Street Studio data together. Do not delete these folders as a routine fix for a missing texture or an unavailable asset.
