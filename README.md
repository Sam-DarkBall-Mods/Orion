# Orion

[![CI](https://github.com/Sam-DarkBall-Mods/Orion/actions/workflows/ci.yml/badge.svg)](https://github.com/Sam-DarkBall-Mods/Orion/actions/workflows/ci.yml)

Orion adds the Orion-E UAV for BLUFOR, OPFOR and Independent. The available
loadouts include Kornet missiles and KAB-20 or KAB-50 bombs. Separate driver
and gunner displays provide the flight and weapon information.

## Requirements

- Arma 3 2.22 or newer

## Building

```bash
python3 -B -m unittest discover -s tests -p "test_*.py" -v
hemtt check
hemtt build --no-bin
```

The `orion` prefix, class names and `orion.pbo` filename remain unchanged
for mission compatibility.

## License

Code and configs use GPL-2.0-or-later. Original models, textures, materials and
audio use APL-SA. See [LICENSES.md](LICENSES.md).
