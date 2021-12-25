# Pure

Pure is a Social Network Messenger app developed using Flutter.

[![build Actions Status](https://github.com/Aanu1995/Pure/workflows/build/badge.svg)](https://github.com/Aanu1995/Pure/actions)
[![License: MIT][license_badge]][license_link]
[![Codemagic build status](https://api.codemagic.io/apps/61c16a2d5d15f530c8172797/61c16b3168cc9cfd2f86b064/status_badge.svg)](https://codemagic.io/apps/61c16a2d5d15f530c8172797/61c16b3168cc9cfd2f86b064/latest_build)

Generated by the [Very Good CLI][very_good_cli_link] 🤖

**Tech Stack**

- Flutter
- Firebase
- Cloud Functions (https://github.com/Aanu1995/Pure_Dev_Cloud_Function)
- algolia (For Search)

**Dependencies**

- State Management (flutter_bloc)
- image_Picker
- flex_color_scheme
- Firebase
- stream_transform

<img width="200" alt="Screenshot 2021-12-05 at 8 15 15 AM" src="https://user-images.githubusercontent.com/24871915/144737628-286cb714-e774-409f-92cc-1a8d1563224a.png"> <img width="200" alt="Screenshot 2021-12-05 at 8 29 29 AM" src="https://user-images.githubusercontent.com/24871915/144738009-51ca0ead-f6d5-4fb8-a8f9-1f47762adf72.png"> <img width="200" alt="Screenshot 2021-12-05 at 8 29 50 AM" src="https://user-images.githubusercontent.com/24871915/144738010-73e4fa82-75f7-4b4b-9485-a830a051eb00.png"> <img width="200" alt="Screenshot 2021-12-05 at 8 30 51 AM" src="https://user-images.githubusercontent.com/24871915/144738011-c0d0849b-5014-4df2-977a-e5c2a0278541.png"> <img width="200" alt="Screenshot 2021-12-05 at 8 18 58 AM" src="https://user-images.githubusercontent.com/24871915/144737631-d61814d1-f863-49ea-8c44-2ea70b8280e5.png"> <img width="200" alt="Screenshot 2021-12-05 at 8 20 11 AM" src="https://user-images.githubusercontent.com/24871915/144737632-c5bdd025-b2b4-4897-b81e-a13c3c380b1d.png"> <img width="200" alt="Screenshot 2021-12-05 at 8 15 55 AM" src="https://user-images.githubusercontent.com/24871915/144737630-cba4be63-d975-4ac1-a260-7b8b03ed56b1.png">

<img width="200" alt="Screenshot 2021-12-05 at 8 31 19 AM" src="https://user-images.githubusercontent.com/24871915/144738067-76bb7d7a-0743-4f52-9b0e-d1b76f13d112.png"> <img width="200" alt="Screenshot 2021-12-05 at 8 31 29 AM" src="https://user-images.githubusercontent.com/24871915/144738069-785089c3-54ac-4838-b967-9ab2b91aa4bf.png"> <img width="200" alt="Screenshot 2021-12-05 at 8 31 44 AM" src="https://user-images.githubusercontent.com/24871915/144738070-7a3e938a-2df4-4276-a640-cc9307aa761c.png"> <img width="200" alt="Screenshot 2021-12-05 at 8 32 32 AM" src="https://user-images.githubusercontent.com/24871915/144738071-c27456e4-a84f-4a50-9da3-593aaea5e3b0.png">

---

## Getting Started 🚀

This project contains 3 flavors:

- development
- staging
- production

To run the desired flavor either use the launch configuration in VSCode/Android Studio or use the following commands:

```sh
# Development
$ flutter run --flavor development --target lib/main_development.dart

# Staging
$ flutter run --flavor staging --target lib/main_staging.dart

# Production
$ flutter run --flavor production --target lib/main_production.dart
```

_\*Pure works on iOS, Android, and Web._

---

## Running Tests 🧪

To run all unit and widget tests use the following command:

```sh
$ flutter test --coverage --test-randomize-ordering-seed random
```

To view the generated coverage report you can use [lcov](https://github.com/linux-test-project/lcov).

```sh
# Generate Coverage Report
$ genhtml coverage/lcov.info -o coverage/

# Open Coverage Report
$ open coverage/index.html
```

[coverage_badge]: coverage_badge.svg
[flutter_localizations_link]: https://api.flutter.dev/flutter/flutter_localizations/flutter_localizations-library.html
[internationalization_link]: https://flutter.dev/docs/development/accessibility-and-localization/internationalization
[license_badge]: https://img.shields.io/badge/license-MIT-blue.svg
[license_link]: https://opensource.org/licenses/MIT
[very_good_analysis_badge]: https://img.shields.io/badge/style-very_good_analysis-B22C89.svg
[very_good_analysis_link]: https://pub.dev/packages/very_good_analysis
[very_good_cli_link]: https://github.com/VeryGoodOpenSource/very_good_cli
