An example project that showcases how to enable the lint set from `package:carapacik_lints`, which contains recommended lints for Flutter apps, packages, and plugins to encourage good coding practices

Add `carapacik_lints` as dependency to your `pubspec.yaml`.
```yaml
dev_dependencies:
  carapacik_lints: ^1.0.3
```

Create an `analysis_options.yaml` file at the root of the project with the following content:

```yaml
include: package:carapacik_lints/analysis_options.yaml
```