# Linting Standards

This project uses [very_good_analysis](https://pub.dev/packages/very_good_analysis) for linting and code quality.

## Why very_good_analysis?

We chose `very_good_analysis` because it provides a stricter, more opinionated set of rules than the default `flutter_lints`. This helps maintain a high standard of code quality and consistency across the codebase.

### Key Features:
- **Strict Type Safety**: Ensures that types are explicitly defined and correctly used.
- **Consistent Ordering**: Enforces a consistent order for class members (constructors, fields, methods).
- **Reduced Technical Debt**: Catches potential issues early through detailed static analysis.

## Customizations

Currently, we are using the default rules provided by `very_good_analysis`. Any future overrides should be documented here and added to `analysis_options.yaml`.

## Automatic Fixes

To automatically fix many common lint issues, run:
```bash
dart fix --apply
```

## Manual Checks

You can run the analyzer manually at any time:
```bash
flutter analyze
```
