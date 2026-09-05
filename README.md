[日本語](README.md#日本語) / [English](README.md#english)

# Travelers Split Public

## English

Public KiCad release bundle for the Travelers Split keyboard hardware.

### Projects

- `split_L_v2/ULP_Keyboard_split_L.kicad_pro`
- `split_R_v2/ULP_Keyboard_split_R.kicad_pro`
- `split_prog/ULP_Keyboard_split_prog.kicad_pro`

### Libraries

Project-local KiCad tables reference the bundled libraries under `libraries/` via `${KIPRJMOD}/../libraries/...`, so the projects can be opened without setting `KICAD_USER_LOCAL`.

### Repository Layout

- `split_L_v2/`: left half KiCad project
- `split_R_v2/`: right half KiCad project
- `split_prog/`: programmer KiCad project
- `libraries/`: symbols, footprints, and 3D models used by the projects

## 日本語

Travelers Split keyboard hardware の公開用 KiCad リリース一式です。

### プロジェクト

- `split_L_v2/ULP_Keyboard_split_L.kicad_pro`
- `split_R_v2/ULP_Keyboard_split_R.kicad_pro`
- `split_prog/ULP_Keyboard_split_prog.kicad_pro`

### ライブラリ

各プロジェクト内の KiCad ライブラリテーブルは、同梱の `libraries/` を `${KIPRJMOD}/../libraries/...` として参照します。そのため、`KICAD_USER_LOCAL` を設定しなくてもプロジェクトを開けます。

### リポジトリ構成

- `split_L_v2/`: 左手側の KiCad プロジェクト
- `split_R_v2/`: 右手側の KiCad プロジェクト
- `split_prog/`: 書き込み器用の KiCad プロジェクト
- `libraries/`: 各プロジェクトで使用するシンボル、フットプリント、3Dモデル
