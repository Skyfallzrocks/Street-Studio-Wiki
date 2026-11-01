# Parking

Street Studio includes parking sections in the road designer and a separate **Parking brush**.

## Parking sections

Add a Parking piece, select it and choose its available layout and marking options. Parallel parking can use bay dividers/T markings. Check the actual road surface after placement; a library thumbnail is not proof that the markings are active.

A valid parking section needs an appropriate lane configuration and access. Painting a rectangle alone does not establish functional parking.

## Parking brush

Open **Parking brush** in the Street Studio workspace.

### Bay layouts

- Parallel.
- Angled 30°.
- Angled 45°.
- Angled 60°.
- Perpendicular.

### Markings

- T-marks.
- Full T.
- Dividers.
- Boxed.
- Unmarked.

### Placement and hatching

Choose **Curb** for bays against the curb, or **Off road** for placement beside the road's edge. End hatching can be switched off or set to 2, 3, 4 or 6 metres.

1. Choose the bay layout, markings and placement mode.
2. Press on a road, drag along it and release.
3. The chosen side follows the cursor.
4. Inspect the preview before release. The tool describes bays stopping before crosswalks and skipping already painted areas; red preview areas indicate a conflict.
5. Switch to **Erase** and drag to remove brush bays.
6. Choose **Done** to leave the brush.

These controls describe the implemented workflow. Traffic access and parking use still need checking on the road configuration you build.

## Parking meters

Select a compatible parking section and enable **Parking meters** when available.

- **Parking meter spacing** controls distance between meters.
- **Meter curb setback** controls placement relative to the curb.

The generation code looks for the **SolarPayStation** asset and an adjacent sidewalk. If either is missing, it skips meter placement rather than putting a meter in the carriageway. A meter model does not by itself establish a new parking-fee simulation.
