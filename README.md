# DXMT

A Metal-based translation layer for Direct3D 11 and 10 which allows running 3D applications on macOS using Wine.

For the current status of the project, please refer to the [project wiki](https://github.com/3Shain/dxmt/wiki).

The most recent development builds can be found [here](https://github.com/3Shain/dxmt/actions).


## Build

See [DEVELOPMENT.md](docs/DEVELOPMENT.md)

## FSR4 DXMT overrides

The optional FSR4 integration accepts `FSR4_DXMT_HOOK` for the hook library and `FSR4_DXMT_RENDER_WIDTH` / `FSR4_DXMT_RENDER_HEIGHT` for a render-size override. When `FSR4_ROOT` is set, values in `dist/crossover/panel.conf` take precedence over the render-size environment defaults.
