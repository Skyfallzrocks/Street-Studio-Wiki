# Intersection editor

Open **Edit intersections & markings** from the Street Studio workspace.

This is the integrated manual junction-marking editor. The original Town Road Lane mod is not required alongside Street Studio.

## Workflow

1. Open the editor and select the junction/node you want to work on.
2. Follow the active tool's prompt to define or select marking geometry.
3. Use the panel's available line styles and filled-area styles.
4. Select existing geometry to adjust its available properties or visibility.
5. Use the relevant delete control to remove unwanted lines or areas.
6. Inspect the junction from above and at road level, then save and reload a test city to check persistence.

The editor exposes lines and area fills as separate editable objects. Its tool bindings can be configured through the intersection settings. Use those bindings and the panel prompts rather than assuming a shortcut from another marking mod will apply.

## What markings do

Treat painted markings as visual editing unless a particular control explicitly changes traffic behavior. Arrows, hatch patterns and colored areas do not automatically alter priorities, signals or lane connections.

The integrated implementation uses its own namespaces, UI bindings and save identities. Its adaptation does not replace the game's vanilla SecondaryLaneSystem or automatically rewrite host lanes.

## Imported assets

The editor and an imported asset are different things. Importing a custom island, sign or traffic-light model does not automatically register it as an editor style or a functioning traffic-control prefab.

## Compatibility

Use one active implementation while testing the integrated editor. Loading the original marking mod as well is not a documented compatibility configuration. Keep a separate save before trying other junction or lane tools.

See [[Credits|Credits]] for the source and GPL licensing of this integration.
