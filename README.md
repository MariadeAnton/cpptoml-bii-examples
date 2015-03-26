# cpptoml examples in biicode

cpptoml is header-only library for parsing [TOML][toml] configuration files.

Targets: [TOML v0.4.0][currver]

It is reasonably conforming, with the exception of unicode escape
characters in strings. This includes support for the new DateTime format,
inline tables, multi-line basic and raw strings, and digit separators.

# Use it in biicode

Fill your ``biicode.conf`` file just like this:

```
[requirements]
    skystrife/cpptoml: 0

[includes]
     cpptoml.h :skystrife/cpptoml/include
```

# Compile the examples

```
git clone ..
cd cpptoml-bii-examples
bii init -L
bii build
```

[currver]: https://github.com/toml-lang/toml/blob/master/versions/en/toml-v0.4.0.md
[toml]: https://github.com/toml-lang/toml
[biicode]: https://www.biicode.com

