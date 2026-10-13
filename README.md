# enclosure-media

Photoreal Blender renders and animations of enclosure-forge targets,
rendered headless on GPU (ai-legion-small, RTX 3060 Ti, Cycles CUDA).

## Hero animations (4 s, 1080p, 30fps)

| Board | Video | Stills |
|---|---|---|
| Nucula V6 | [`nucula_hero.mkv`](nucula_hero.mkv) | below |
| RP2040 dev board | [`renders/rp2040-devboard_hero.mkv`](renders/rp2040-devboard_hero.mkv) | below |
| Easyduino ESP32 | [`renders/easyduino-esp32_hero.mkv`](renders/easyduino-esp32_hero.mkv) | below |
| Easyduino ESP32-S3 | [`renders/easyduino-esp32s3_hero.mkv`](renders/easyduino-esp32s3_hero.mkv) | below |
| Easyduino Pico | [`renders/easyduino-pico_hero.mkv`](renders/easyduino-pico_hero.mkv) | below |
| Specter-DIY | [`renders/specter-diy-case_hero.mkv`](renders/specter-diy-case_hero.mkv) | below |

Every animation: exploded assembly settles together, then a clean
360° orbit with the camera locked on the device center (track-to
constraint, 85mm lens, probe-verified zero drift).

Scene: [enclosure-forge/harness/blender/hero_generic.py](https://github.com/Amperstrand/enclosure-forge/blob/main/harness/blender/hero_generic.py)
— works with any enclosure repo's STL exports.

## Stills (1920×1080)

See `renders/` directory for stills at three moments per board:
exploded (frame ~24), assembled (frame ~46), turntable (frame ~96).
