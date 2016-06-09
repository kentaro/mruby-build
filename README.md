# mruby-build

A simple script just to `git clone` and build mruby.

## Usage

```sh
$ ./mruby-build
```

You'll see the artifact in `./mruby`.

## `build_config.rb`

If you want to customize the mruby installation, set the environment variable named `MRUBY_CONFIG'`.

```sh
$ MRUBY_CONFIG=/path/to/your/build_config.rb ./mruby-build
```

## Author

Kentaro Kuribayashi

## License

MIT
