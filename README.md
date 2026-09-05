# Travelers Split Public

Public KiCad release bundle for the Travelers Split keyboard hardware.

Travelers Split keyboard hardwareの公開用KiCadリリース一式です。

## Projects

- `split_L_v2/ULP_Keyboard_split_L.kicad_pro`
- `split_R_v2/ULP_Keyboard_split_R.kicad_pro`
- `split_prog/ULP_Keyboard_split_prog.kicad_pro`

## プロジェクト

- `split_L_v2/ULP_Keyboard_split_L.kicad_pro`
- `split_R_v2/ULP_Keyboard_split_R.kicad_pro`
- `split_prog/ULP_Keyboard_split_prog.kicad_pro`

## Libraries

Project-local KiCad tables reference the bundled libraries under `libraries/` via `${KIPRJMOD}/../libraries/...`, so the projects can be opened without setting `KICAD_USER_LOCAL`.

## ライブラリ

各プロジェクト内のKiCadライブラリテーブルは、同梱の `libraries/` を `${KIPRJMOD}/../libraries/...` として参照します。そのため、`KICAD_USER_LOCAL` を設定しなくてもプロジェクトを開けます。

## Repository Layout

- `split_L_v2/`: left half KiCad project
- `split_R_v2/`: right half KiCad project
- `split_prog/`: programmer KiCad project
- `libraries/`: symbols, footprints, and 3D models used by the projects

## リポジトリ構成

- `split_L_v2/`: 左手側のKiCadプロジェクト
- `split_R_v2/`: 右手側のKiCadプロジェクト
- `split_prog/`: 書き込み器用のKiCadプロジェクト
- `libraries/`: 各プロジェクトで使用するシンボル、フットプリント、3Dモデル
