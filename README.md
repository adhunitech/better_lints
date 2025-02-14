# better_lints - Because `package:lints` wasn't strict enough

[![Better Lints Build](https://github.com/adhunitech/better_lints/workflows/Better%20Lints%20Build/badge.svg)](https://github.com/adhunitech/better_lints/actions?query=workflow%3A%22Better+Lints+Build%22)
[![Pub Dev](https://img.shields.io/pub/v/better_lints)](https://pub.dev/packages/better_lints)
[![Documentation](https://img.shields.io/badge/documentation-latest-brightgreen.svg)](https://pub.dev/documentation/better_lints/latest/)

Lint rules used by Adhunitech and other major companies.

## Usage

To use a ruleset, add `better_lints` as a dev dependency in your `pubspec.yaml`.
```bash
flutter pub add better_lints
```

Then, add a ruleset to your `analysis_options.yaml`. This package contains a Dart ruleset & a Flutter ruleset.

To use the Dart ruleset:
```yaml
include: package:better_lints/analysis_options.dart.yaml
```

To use the Flutter ruleset:
```yaml
include: package:better_lints/analysis_options.flutter.yaml
```
