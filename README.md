<img src="https://github.com/user-attachments/assets/c4c2d3a6-52a1-4515-b27f-4041af19fcf6" width="600" height="300"/>

# Package axeptio-android-sdk


[![License](https://img.shields.io/badge/license-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0) [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://github.com/axeptio/sample-app-android/pulls)  [![Axeptio SDK Version](https://img.shields.io/github/v/release/axeptio/axeptio-android-sdk)](https://github.com/axeptio/axeptio-android-sdk/releases) [![Kotlin Integration](https://img.shields.io/badge/Integration-Kotlin%20%26%20Compose-blue)](https://github.com/axeptio/sample-app-android/tree/main/samplekotlin) [![Android SDK Compatibility](https://img.shields.io/badge/Android%20SDK-%3E%3D%2026-blue)](https://developer.android.com/studio)

> **2.2.0 is now available** (previously beta as 2.2.0-beta.1)
>
> This release includes a **breaking change**:
>
> **Java language support has been dropped.** The SDK is now Kotlin-only.
> - `@JvmStatic` annotations removed from `AxeptioSDK.instance()` and `AxeptioAPIRepository.instance()`
> - The `samplejava` module has been removed
> - **Migration:** Replace `AxeptioSDK.instance()` with `AxeptioSDK.INSTANCE.instance()`, or migrate to Kotlin
> - Consumers compiled against earlier versions may encounter `NoSuchMethodError` at runtime — recompile against this release
>
> New features include `onError()` callback, `getRemainingDaysForConsent()`, `AxeptioStore` for Compose, and foreground popup controls.
>
> See the full [release notes](releases/2.2.0.md) for details.

This repository contains the Axeptio Android SDK, a powerful library for managing user consent in compliance with privacy regulations. It allows Android developers to seamlessly ask for and collect user consent for data processing, ensuring compliance with frameworks like GDPR and CCPA.

## 📑 Table of Contents
1. [Supported Standards](#supported-standards)
2. [Implementation](#implementation)
3. [License](#license)

This repository contains the Axeptio Android SDK Github-Package.
<br><br><br>
## Supported Standards
The **Axeptio Android SDK** supports the following consent management frameworks and standards:
- **IAB TCF v1** (Transparency and Consent Framework)

- **IAB TCF v2** (Transparency and Consent Framework)

- **Google Consent Mode v2**
<br><br><br>

## 🚀Implementation
For detailed implementation instructions and configuration steps, please refer to the official [sample apps repository](https://github.com/axeptio/sample-app-android) The repository provides example applications and step-by-step guides to help you integrate the **Axeptio Android SDK** into your project.
<br><br><br>

## License

The Axeptio Android SDK is available under the MIT License. For more information, please refer to the [LICENSE](LICENSE) file in this repository.



