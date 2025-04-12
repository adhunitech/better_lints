# Better Lints

[![Better Lints Build](https://github.com/adhunitech/better_lints/workflows/Better%20Lints%20Build/badge.svg)](https://github.com/adhunitech/better_lints/actions?query=workflow%3A%22Better+Lints+Build%22)
[![Pub Dev](https://img.shields.io/pub/v/better_lints)](https://pub.dev/packages/better_lints)
[![Documentation](https://img.shields.io/badge/documentation-latest-brightgreen.svg)](https://pub.dev/documentation/better_lints/latest/)

A curated set of lint rules for Dart and Flutter projects to ensure consistency, maintainability, and best practices.

## ✨ Features
- Enforces a consistent coding style.
- Helps prevent common errors and anti-patterns.
- Based on Dart's official `lints` and `flutter_lints`, with additional enhancements.
- Easy integration into new and existing projects.

## 📦 Installation & Usage

Add `better_lints` as a dev dependency in your `pubspec.yaml`:

```sh
flutter pub add dev:better_lints
```

Then, add a ruleset to your `analysis_options.yaml`. This package contains a Dart ruleset & a Flutter ruleset.

To use the Flutter ruleset:
```yaml
include: package:better_lints/analysis_options.yaml
```
