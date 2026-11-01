# Getting started

## Install a local release

1. Close Cities: Skylines II.
2. Extract the complete Street Studio release.
3. Copy the entire `StreetStudio` payload folder into:

```text
%USERPROFILE%\AppData\LocalLow\Colossal Order\Cities Skylines II\Mods
```

For the development folder, the payload is `Package\StreetStudio`.

The resulting installation should contain:

```text
Mods\StreetStudio\StreetStudio.dll
```

Keep the accompanying UI files, native libraries, icons, images and packaged assets together. Copying only the DLL is not a complete installation.

Use one installation of Street Studio. Avoid loading both a manually installed copy and a subscribed copy. Keep installation backups outside the game's data folders so they cannot be discovered as duplicate mods.

The supplied `Install-StreetStudio.ps1` can install the payload. Its `-Update` option backs up an existing installation before updating it. Read the script before running it.

## First launch

Start with a test city and a separate save. For initial testing, disable Road Builder in that playset; interactions between both road generators are not established by this documentation.

Open Street Studio using its road icon. The game Options screen also contains Street Studio settings and configurable tool bindings.

## Make your first street

1. Place a short normal road with the game road tool.
2. Open Street Studio and select the segment.
3. Use **Use As Template** when offered to start a separate design.
4. Open **Lanes** and drag a piece into the street layout.
5. Drag pieces to rearrange them. Click a piece to edit its available options.
6. Check the width, direction and editing-scope message above the layout.
7. Choose **Build road** to place more road using the design.

Individual layout edits update live. Street-style recipes use **Apply Design** to replace the cross-section with the selected recipe.

## Save and reuse

Use **More → Save Template** to keep the design in your local library. **My templates** opens the library. **Copy design** creates a separate design for independent changes.

Editing a shared design can update every segment using it. A template file is a road design, not a backup of your city.
