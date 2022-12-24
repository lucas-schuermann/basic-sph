`basic-sph` is a basic 2D implementation of a stable smoothed particle hydrodynamics (SPH) solver. See [here](https://github.com/cerrno/pcisph-wasm) for a more recent implementation in Rust including a parallelized solver.

For further information, please see SPH tutorials on [my website](https://lucasschuermann.com/writing), including an introduction to [SPH math](https://lucasschuermann.com/writing/particle-based-fluid-simulation) and a [simple SPH solver](https://lucasschuermann.com/writing/implementing-sph-in-2d).

## Running
```bash
# install dependencies (debian/ubuntu)
apt install libopengl-dev freeglut3-dev libeigen3-dev

# uncomment header in `Makefile` depending on platform
make

# launch demo
./sph
```

## License
This project is distributed under the [MIT license](LICENSE.md).