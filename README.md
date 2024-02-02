### MLX C

MLX C is a C API for [MLX](https://github.com/ml-explore/mlx). MLX C can be
used standalone or as a bridge to bind other languages to MLX. For example,
the [MLX Swift](https://github.com/ml-explore/mlx-swift/) package uses MLX C
for Swift bindings to MLX.

For more information see the [docs](https://ml-explore.github.io/mlx-c)

#### Install

CMake is required to build MLX C. You can install it with [Homebrew](https://brew.sh/):

```shell
brew install cmake
```

To build, run the following commands:

```shell
mkdir build && cd build
cmake ..
make -j
```

From the `build/` directory, you can run an [examples/example.c](example)
that uses MLX C  with `./example`.

## Contributing 

Check out the [contribution guidelines](CONTRIBUTING.md) for more information
on contributing to MLX. See the
[docs](https://ml-explore.github.io/mlx/build/html/install.html) for more
information on building from source, and running tests.

We are grateful for all of [our
contributors](ACKNOWLEDGMENTS.md#Individual-Contributors). If you contribute
to MLX and wish to be acknowledged, please add your name to the list in your
pull request.
