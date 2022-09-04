[![pub package](https://img.shields.io/pub/v/carapacik_lints.svg)](https://pub.dev/packages/carapacik_lints)

This package contains a recommended set of lints for Flutter apps, packages, and plugins to encourage good coding practices.

## Install

Add `carapacik_lints` as dev dependency to your `pubspec.yaml`.
```yaml
dev_dependencies:
  carapacik_lints: ^1.1.5
```
or
```yaml
dev_dependencies:
  carapacik_lints:
    git:
      url: https://github.com/Carapacik/carapacik_lints.git
```

For Flutter 2 and Dart 2.16 use version 1.0.x:
```yaml
  carapacik_lints: 1.0.6
```

Create an `analysis_options.yaml` file at the root of the project with the following content:

```yaml
include: package:carapacik_lints/core.yaml
```