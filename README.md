[![pub version](https://img.shields.io/pub/v/carapacik_lints?logo=dart)](https://pub.dev/packages/carapacik_lints)

This package contains a recommended set of lints for Flutter apps, packages, and plugins to encourage good coding practices.

## Install

Add `carapacik_lints` as dev dependency to your `pubspec.yaml`.
```yaml
dev_dependencies:
  carapacik_lints: ^1.5.0
```
or
```yaml
dev_dependencies:
  carapacik_lints:
    git:
      url: https://github.com/Carapacik/carapacik_lints.git
```

Create an `analysis_options.yaml` file at the root of the project with the following content:

```yaml
include: package:carapacik_lints/core.yaml
```

## Versions table
| Flutter | Dart   | Package |
|:--------|:-------|:--------|
| 2.10.x  | 2.16.x | 1.0.8   |
| 3.0.x   | 2.17.x | 1.1.7   |
| 3.3.x   | 2.18.x | 1.2.3   |
| 3.7.x   | 2.19.x | 1.3.2   |
| 3.10.x  | 3.0.x  | 1.4.2   |
| 3.13.x  | 3.1.x  | 1.5.0   |
