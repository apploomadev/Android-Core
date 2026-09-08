# AppLooma RTC Core (Android)

Media transport core for the [AppLooma RTC](https://applooma.dev) Android SDK.

**You almost certainly want `com.applooma:rtc-android` instead.** This is the
low-level transport layer it is built on, published separately because Gradle
resolves dependencies as artifacts.

```kotlin
implementation("com.applooma:rtc-core-android:2.12.0")
```

- Documentation — https://docs.applooma.dev/sdk/android
- Support — support@applooma.dev

## Building

```bash
./gradlew :livekit-android-sdk:assembleRelease
```

Requires JDK 17 and the Android SDK. The protocol definitions are vendored in
`protocol/`, so no submodule initialisation is needed.

## Licence

Apache License 2.0. This is a modified redistribution of upstream open source
work; see [NOTICE](NOTICE) for the attribution and the list of changes.
