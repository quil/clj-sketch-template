# quil/clj-sketch-template

## Usage

This is a template project for use with
[deps-new](https://github.com/seancorfield/deps-new). Assuming you have installed `deps-new` as your `new` "tool" via:

```bash
clojure -Ttools install-latest :lib io.github.seancorfield/deps-new :as new
```

You can create a new sketch with:

``` bash
$ clojure -Sdeps '{:deps {io.github.quil/clj-sketch-template {:local/root "."}}}' -Tnew create :template quil/clj-sketch-template :name myusername/mycoollib
```

See the README in the new sketch for more info!

## License

Distributed under the Eclipse Public License version 1.0.
