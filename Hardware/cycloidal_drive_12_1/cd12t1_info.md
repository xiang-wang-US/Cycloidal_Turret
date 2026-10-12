# 12:1 cycloidal drive (elevation)

`cd12t1` is the 12:1 single stage cycloidal reducer that drives the elevation (pitch) axis on a NEMA 17 stepper.
An AS5600 magnetic encoder reads the output angle. Pitch range is about -30 to +80 degrees.

## Files

- `12-1 Cycloidal Drive Assembly.STEP`: full reducer assembly with motor envelope
- `12-1 cycloidal drive Var1.mp4`: assembly animation

## Build notes

- Disc profile generated parametrically in Desmos, imported into SolidWorks as the disc sketch
- All structural parts FDM printed; the printed drive was turned by hand to check engagement before mounting
