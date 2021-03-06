[android-components](../../index.md) / [mozilla.components.concept.engine](../index.md) / [Settings](./index.md)

# Settings

`abstract class Settings` [(source)](https://github.com/mozilla-mobile/android-components/blob/master/components/concept/engine/src/main/java/mozilla/components/concept/engine/Settings.kt#L18)

Holds settings of an engine or session. Concrete engine
implementations define how these settings are applied i.e.
whether a setting is applied on an engine or session instance.

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `Settings()`<br>Holds settings of an engine or session. Concrete engine implementations define how these settings are applied i.e. whether a setting is applied on an engine or session instance. |

### Properties

| Name | Summary |
|---|---|
| [allowContentAccess](allow-content-access.md) | `open var allowContentAccess: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Setting to control whether or not the engine is allowed to load content from a content provider installed in the system. |
| [allowFileAccess](allow-file-access.md) | `open var allowFileAccess: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Setting to control whether or not file access is allowed. |
| [allowFileAccessFromFileURLs](allow-file-access-from-file-u-r-ls.md) | `open var allowFileAccessFromFileURLs: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Setting to control whether or not JavaScript running in the context of a file scheme URL should be allowed to access content from other file scheme URLs. |
| [allowUniversalAccessFromFileURLs](allow-universal-access-from-file-u-r-ls.md) | `open var allowUniversalAccessFromFileURLs: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Setting to control whether or not JavaScript running in the context of a file scheme URL should be allowed to access content from any origin. |
| [displayZoomControls](display-zoom-controls.md) | `open var displayZoomControls: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Setting to control whether or not zoom controls should be displayed. |
| [domStorageEnabled](dom-storage-enabled.md) | `open var domStorageEnabled: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Setting to control whether or not DOM Storage is enabled. |
| [historyTrackingDelegate](history-tracking-delegate.md) | `open var historyTrackingDelegate: `[`HistoryTrackingDelegate`](../../mozilla.components.concept.engine.history/-history-tracking-delegate/index.md)`?`<br>Setting to provide a history delegate to the engine. |
| [horizontalScrollBarEnabled](horizontal-scroll-bar-enabled.md) | `open var horizontalScrollBarEnabled: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Setting to control whether or not horizontal scrolling is enabled. |
| [javaScriptCanOpenWindowsAutomatically](java-script-can-open-windows-automatically.md) | `open var javaScriptCanOpenWindowsAutomatically: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Setting to control whether or not window.open can be called from JavaScript. |
| [javascriptEnabled](javascript-enabled.md) | `open var javascriptEnabled: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Setting to control whether or not JavaScript is enabled. |
| [loadWithOverviewMode](load-with-overview-mode.md) | `open var loadWithOverviewMode: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Setting to control whether or not the engine zooms out the content to fit on screen by width. |
| [mediaPlaybackRequiresUserGesture](media-playback-requires-user-gesture.md) | `open var mediaPlaybackRequiresUserGesture: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Setting to control whether or not a user gesture is required to play media. |
| [remoteDebuggingEnabled](remote-debugging-enabled.md) | `open var remoteDebuggingEnabled: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Setting to control whether or not remote debugging is enabled. |
| [requestInterceptor](request-interceptor.md) | `open var requestInterceptor: `[`RequestInterceptor`](../../mozilla.components.concept.engine.request/-request-interceptor/index.md)`?`<br>Setting to intercept and override requests. |
| [supportMultipleWindows](support-multiple-windows.md) | `open var supportMultipleWindows: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Setting to control whether or not multiple windows are supported. |
| [testingModeEnabled](testing-mode-enabled.md) | `open var testingModeEnabled: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Setting to control whether or not testing mode is enabled. |
| [trackingProtectionPolicy](tracking-protection-policy.md) | `open var trackingProtectionPolicy: `[`TrackingProtectionPolicy`](../-engine-session/-tracking-protection-policy/index.md)`?`<br>Setting to control tracking protection. |
| [userAgentString](user-agent-string.md) | `open var userAgentString: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?`<br>Setting to control the user agent string. |
| [verticalScrollBarEnabled](vertical-scroll-bar-enabled.md) | `open var verticalScrollBarEnabled: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Setting to control whether or not vertical scrolling is enabled. |
| [webFontsEnabled](web-fonts-enabled.md) | `open var webFontsEnabled: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Setting to control whether or not Web fonts are enabled. |

### Inheritors

| Name | Summary |
|---|---|
| [DefaultSettings](../-default-settings/index.md) | `data class DefaultSettings : `[`Settings`](./index.md)<br>[Settings](./index.md) implementation used to set defaults for [Engine](../-engine/index.md) and [EngineSession](../-engine-session/index.md). |
