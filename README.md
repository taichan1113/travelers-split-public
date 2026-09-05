# Travelers Split Public

Public KiCad release bundle for the Travelers Split keyboard hardware.

## Projects

- `split_L_v2/ULP_Keyboard_split_L.kicad_pro`
- `split_R_v2/ULP_Keyboard_split_R.kicad_pro`
- `split_prog/ULP_Keyboard_split_prog.kicad_pro`

## Libraries

Project-local KiCad tables reference the bundled libraries under `libraries/` via `${KIPRJMOD}/../libraries/...`, so the projects can be opened without setting `KICAD_USER_LOCAL`.

## Repository Layout

- `split_L_v2/`: left half KiCad project
- `split_R_v2/`: right half KiCad project
- `split_prog/`: programmer KiCad project
- `libraries/`: symbols, footprints, and 3D models used by the projects
