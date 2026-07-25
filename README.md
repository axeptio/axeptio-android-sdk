<img src="https://github.com/user-attachments/assets/c4c2d3a6-52a1-4515-b27f-4041af19fcf6" width="600" height="300"/>

# Package axeptio-android-sdk


[![License](https://img.shields.io/badge/license-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0) [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://github.com/axeptio/sample-app-android/pulls)  [![Axeptio SDK Version](https://img.shields.io/github/v/release/axeptio/axeptio-android-sdk)](https://github.com/axeptio/axeptio-android-sdk/releases) [![Kotlin Integration](https://img.shields.io/badge/Integration-Kotlin%20%26%20Compose-blue)](https://github.com/axeptio/sample-app-android/tree/main/samplekotlin) [![Android SDK Compatibility](https://img.shields.io/badge/Android%20SDK-%3E%3D%2026-blue)](https://developer.android.com/studio)

This repository contains the Axeptio Android SDK, a powerful library for managing user consent in compliance with privacy regulations. It allows Android developers to seamlessly ask for and collect user consent for data processing, ensuring compliance with frameworks like GDPR and CCPA.

## 📑 Table of Contents
1. [Supported Standards](#supported-standards)
2. [Java Support (EOL)](#java-support-eol)
3. [Implementation](#implementation)
4. [Releases](#releases)
5. [License](#license)

This repository contains the Axeptio Android SDK Github-Package.
<br><br><br>
## Supported Standards
The **Axeptio Android SDK** supports the following consent management frameworks and standards:
- **IAB TCF v1** (Transparency and Consent Framework)

- **IAB TCF v2** (Transparency and Consent Framework)

- **Google Consent Mode v2**
<br><br><br>

## ⚠Java Support (EOL)
Java language support was **dropped in 2.2.0**. The **Axeptio Android SDK** is Kotlin-only.

- `@JvmStatic` annotations removed from `AxeptioSDK.instance()` and `AxeptioAPIRepository.instance()`
- The `samplejava` sample module has been removed

**Migration:** replace `AxeptioSDK.instance()` with `AxeptioSDK.INSTANCE.instance()`, or migrate your consumer to Kotlin. Consumers compiled against pre-2.2.0 releases may hit `NoSuchMethodError` at runtime — recompile against 2.2.0 or later.

See [release notes 2.2.0](releases/2.2.0.md) for the full breaking-change details.
<br><br><br>

## 🚀Implementation
For detailed implementation instructions and configuration steps, please refer to the official [sample apps repository](https://github.com/axeptio/sample-app-android) The repository provides example applications and step-by-step guides to help you integrate the **Axeptio Android SDK** into your project.
<br><br><br>

## Releases
Latest release: **2.4.0**

| Version | Release notes |
|---|---|
| 2.4.0 | [notes](releases/2.4.0.md) |
| 2.3.0 | [notes](releases/2.3.0.md) |
| 2.2.0 | [notes](releases/2.2.0.md) — ⚠️ Java EOL |
| 2.1.2 | [notes](releases/2.1.2.md) |
| 2.1.1 | [notes](releases/2.1.1.md) |
| 2.1.0 | [notes](releases/2.1.0.md) |

<br><br><br>

## License

The Axeptio Android SDK is available under the MIT License. For more information, please refer to the [LICENSE](LICENSE) file in this repository.



