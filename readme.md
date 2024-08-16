<p align="center">
  <a href="https://fingerprint.com">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="resources/logo_light.svg" />
      <source media="(prefers-color-scheme: light)" srcset="resources/logo_dark.svg" />
      <img src="resources/logo_dark.svg" alt="Fingerprint logo" width="312px" />
    </picture>
  </a>
</p>
<p align="center">
  <a href="https://discord.gg/39EpE2neBg">
    <img src="https://img.shields.io/discord/852099967190433792?style=logo&label=Discord&logo=Discord&logoColor=white" alt="Discord server">
  </a>
</p>
  
# FingerprintJS

Welcome to the world of FingerprintJS open-source software. This is the home repository where you can get up to speed in minutes. In the [wiki section](https://github.com/FingerprintJS/Home/wiki) of this repository, you can find the best practices and guidelines for open-source projects. 

[FingerprintJS](https://github.com/fingerprintjs/fingerprintjs) is a browser fingerprinting library that queries browser attributes and computes a hashed visitor identifier from them. Unlike cookies and local storage, a fingerprint stays the same in incognito/private mode and even when browser data is purged.

---

## Related products 

### Fingerprint Pro

[Fingerprint Pro](https://fingerprint.com/github/) offers highly accurate browser fingerprinting technology (99.5%) and is used by over 8,000 websites. It can verify legitimate users and block fraudsters even if they use VPNs, browse in incognito mode, clear their cookies, or use other methods to hide their identity. Fingerprint Pro helps companies prevent fraud, improve user experiences, and better understand their traffic.

Fingerprint Pro builds on the FingerprintJS browser fingerprint library to provide up to 99.5% accurate device identification. Key capabilities include:

- Cookie and local storage management - Leverages cryptographically signed cookies and local storage to reliably associate visitor identifier values with fingerprintable attributes.
- Server-side analysis and machine learning - Provides a holistic view of all attributes and layers to generate the most stable and accurate visitor ID.
- Storage and deduplication - Collects multiple attributes to do fuzzy matching and handle browser and OS upgrades.
- Native [iOS](https://github.com/fingerprintjs/fingerprintjs-pro-ios) and [Android](https://github.com/fingerprintjs/fingerprintjs-pro-android-demo) libraries - Enables accurate iOS and Android application user identification with the native platform-specific library, or with the webview integration. These integrations work together with Fingerprint Pro API.

### Fingerprint Pro Plus
Fingerprint Pro Plus expands on Fingerprint Pro’s identification via the visitor ID and adds Smart Signals for enhanced fraud detection and prevention. Fingerprint Pro Plus is geared toward businesses that need additional tools to understand their anonymous users, identify malicious users, and prevent fraud. Fingerprint Pro Plus provides the visitor ID, a unique identifier, and combines that with Smart Signals to tackle your anti-fraud use cases. 

#### Smart Signals 

[Smart Signals](https://dev.fingerprint.com/docs/smart-signals-overview) are an extensive set of signals, not used in traditional identification processes, that are used to identify anonymous visitors attempting to perform fraudulent activities enabling you to identify them with confidence while providing a frictionless, positive experience for trusted visitors. 

- Browser bot detection
- Incognito mode detection
- IP geolocation
- VPN detection
- Browser tamper detection
- Virtual machine detection
- Privacy-focused settings detection
- Developer tools detection
- Remote control tools detection
- IP blocklist matching
- High-activity device detection
- Raw device attributes
- Android emulator detection
- Android tamper detection
- Android cloned app detection
- Factory reset detection
- Frida detection
- Geolocation spoofing detection
- Jailbroken iOS device detection
- Suspect score

With Fingerprint Pro Plus you get access to most Smart Signals. High-activity device, IP blocklist matching, and Raw device attributes are only available in Fingerprint Enterprise.

## Related open-source projects

### Native mobile fingerprinting libraries

- [fingerprintjs-android](https://github.com/fingerprintjs/fingerprintjs-android) - open-source library for Android device identification.
- [fingerprintjs-ios](https://github.com/fingerprintjs/fingerprintjs-ios) - open-source library for iOS device identification.

---

### BotD - open-source bot detection for the web

[Botd](https://github.com/fingerprintjs/botd) is a browser JavaScript library for bot detection that enables you to detect bots and browser automation tools in your web applications. The [BotD integrations](https://github.com/fingerprintjs/botd-integrations) repository contains examples of integrations with cloud platforms.

---

### GradeJS

[GradeJS](https://github.com/gradejs/gradejs) allows you to analyze JavaScript bundles without having access to the source code of the website. GradeJS analyzes the content of the bundles and returns the list of the used packages with detailed information about the package. The tool can detect packages even in minified and tree-shaken bundles.

---

### Fingerprint Pro Use cases

- [demo.fingerprint.com](https://github.com/fingerprintjs/fingerprintjs-pro-use-cases) - Open-source demos of various Fingerprint Pro use cases including payment fraud prevention, promotion abuse prevention, credential stuffing protection, paywall metering, personalization, bot detection and more. 

---

### Fingerprint Pro client SDKs

Open-source libraries that make it easy to integrate Fingerprint Pro into your application. Each library contains an example application:

* [React](https://github.com/fingerprintjs/fingerprintjs-pro-react) (including Preact and Next support)
* [Vue](https://github.com/fingerprintjs/fingerprintjs-pro-vue)
* [Angular](https://github.com/fingerprintjs/fingerprintjs-pro-angular)
* [Svelte](https://github.com/fingerprintjs/fingerprintjs-pro-svelte)
* [React Native](https://github.com/fingerprintjs/fingerprintjs-pro-react-native)
* [Flutter](https://github.com/fingerprintjs/fingerprintjs-pro-flutter)

---

### Fingerprint Pro server SDKs

Open-source libraries that make it easy to use Fingerprint Pro Server API: 

* [Node.js](https://github.com/fingerprintjs/fingerprintjs-pro-server-api-node-sdk)
* [Python](https://github.com/fingerprintjs/fingerprint-pro-server-api-python-sdk)
* [PHP](https://github.com/fingerprintjs/fingerprint-pro-server-api-php-sdk)
* [C#/.NET](https://github.com/fingerprintjs/fingerprint-pro-server-api-dotnet-sdk/)
* [Java](https://github.com/fingerprintjs/fingerprint-pro-server-api-java-sdk)
* [Go](https://github.com/fingerprintjs/fingerprint-pro-server-api-go-sdk)

---

### Selected demos, examples, and research

- [blog-nojs-fingerprint-demo](https://github.com/fingerprintjs/blog-nojs-fingerprint-demo) - A fingerprint that works without JavaScript and cookies.
- [external-protocol-flooding](https://github.com/fingerprintjs/external-protocol-flooding) - The source code of the demo for external protocol flooding vulnerability. Allows arbitrary websites to gather information about installed applications on a victim's computer to perform reliable tracking across different desktop browsers.
- [blog-adblocker-fingerprinting-demo](https://github.com/fingerprintjs/blog-adblocker-fingerprinting-demo) - Interactive demos for an ad blocker fingerprint article.
- [blog-audio-fingerprinting-demo](https://github.com/fingerprintjs/blog-audio-fingerprinting-demo) - Interactive audio signal charts for an audio fingerprint article.
- [blog-apple-id-region-detection](https://github.com/fingerprintjs/blog-apple-id-region-detection) - Interactive demo showing detection of apple ID region using smart app banners.

---

## Contribution guidelines

- [Integrations and repositories best practices](https://github.com/fingerprintjs/home/wiki/Integrations-and-repositories-best-practices)
- [Naming conventions](https://github.com/fingerprintjs/home/wiki/FingerprintJS-Naming-Conventions)
- [Checklist for publishing integration](https://github.com/fingerprintjs/home/wiki/Checklist-for-publishing-new-integration)

## Community 

- [Discord server](https://discord.gg/39EpE2neBg) - Join the Fingerprint community on Discord.
