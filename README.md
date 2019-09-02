# Protobuf Lint Support for JetBrains IDEs
[![Build Status](https://travis-ci.org/yoheimuta/intellij-protolint.svg?branch=master)](https://travis-ci.org/yoheimuta/intellij-protolint)

[Protocol Buffer Linter Plugin](https://plugins.jetbrains.com/plugin/12641-protocol-buffer-linter) for IntelliJ IDEA & other JetBrains products.

The latest plugin release is compatible with IntelliJ IDEA 2018.3.
Other JetBrains IDEs of the same or higher version should be supported as well.

Compatibility Matrix:

| Plugin Version  | IDE Version Range  |
|-----------------|--------------------|
| 0.2.2           | IDEA 2018.3        |

### Installation

// WHat?>??!?

#### Dependencies

- [apilint](https://github.com/thought-machine/protolint) will be installed by default
- [protobuf-jetbrains-plugin](https://github.com/protostuff/protobuf-jetbrains-plugin) must be installed.

### Configuration

The plugin will lint all protobuf file based on the API guidelines by default


### Development

#### Build

```
./gradlew build
```

#### Run IntelliJ IDEA with enabled plugin

```
./gradlew runide
```
