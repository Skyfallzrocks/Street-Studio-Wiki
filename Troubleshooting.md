# Troubleshooting

## Street Studio does not appear

Check that the complete mod payload is installed and that code mods are enabled for your session. A DLL without its matching UI files is incomplete. Check for a duplicate local/subscribed installation, restart the game and review the mod log.

## An island card is disabled

**Asset not loaded in this playset** means the picker cannot find that model. Enable the corresponding built asset package and restart. A Blender file or unbuilt FBX folder is not an installed game asset.

## A feature card will not apply

Try a compatible section and confirm the drop target. Some categories require a median, sidewalk or parking section. Escape cancels an unfinished drag.

## Objects are missing or misplaced

Check loaded assets, adjacent sidewalks and the selected road's available width. Use the supported movement/setback controls and inspect the road after a junction rebuild. Record whether the problem appears on a straight segment, curve or junction.

## Parking markings are missing

Check the actual parking layout and marking selection. In the parking brush, choose a marking style other than **Unmarked**. Inspect conflict areas in the preview and confirm that you are painting the intended road side.

## Traffic lights changed appearance but not behavior

Appearance replacement does not establish signal timing, priority or routing. Use the appropriate game traffic controls. Imported signal meshes require a correctly configured functional prefab to participate in signals.

## Missing meshes or geometry-loading errors

Record the asset name shown in the error. Check for duplicate packages, incomplete imports and mismatched texture/mesh files. Avoid repeatedly importing the same broken asset into your working project. Preserve the original files and logs for diagnosis.

## Crash during a custom signal import

A previously supplied span-wire signal pack failed in emission-map processing. Its first baked ID maps contained interpolated values between valid light IDs. That is an asset-import issue; the corrected asset pack is separate from the Street Studio DLL.

Use the corrected import files supplied with that asset release. Do not assume an FBX passing a Blender check proves that CS2's emission processing will accept it.

## Report a problem

Use **More → Report a problem**, or include this information in a GitHub issue:

```text
Street Studio version:
Game version:
Other enabled mods and asset packs:
New or existing city:
Road layout / imported asset name:
Steps to reproduce:
Expected result:
Actual result:
Does it persist after restart or save/reload?:
Screenshots and relevant log files:
```

Useful files are under:

```text
%USERPROFILE%\AppData\LocalLow\Colossal Order\Cities Skylines II
```

Attach `Player.log` and relevant files from `Logs`, such as `StreetStudio.log` or `AssetPipeline.log`. Logs can contain local paths and account-related information; review them before posting publicly. Do not include Discord bot tokens, API secrets or private beta-key databases.

Keep the failing save as a separate copy when possible so a report can be reproduced without replacing your working city.
