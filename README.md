# FiveM Vector Tool

A simple web tool for FiveM devs: paste `vector2/3/4` (or raw numbers) and instantly get clean coords + copy-ready snippets.

## Features
- Paste: `vector2(...)`, `vector3(...)`, `vector4(...)`, `vec2/3/4`, or plain `x, y, z, w`
- Extracts X / Y / Z / W
- One-click copy:
  - `vector2`, `vector3`, `vector4`
  - `/tp x y z`
  - `SetEntityHeading(PlayerPedId(), w)`

## Usage
1. Download / clone the repo
2. Open `index.html` in your browser

## Example Inputs
- `vector4(468.52, -928.83, 28.45, 87.8)`
- `120.87, -736.17, 242.15`
- `vec2(100.0, 200.0)`

## License
MIT
