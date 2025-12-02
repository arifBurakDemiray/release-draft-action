## 25.4.5
* Added a new config flag `setUseSerialExecutor(boolean useSerial)` for selecting immediate request executor type.
* Added a new config option `setWebviewDisplayOption(WebViewDisplayOption)` to control how Content and Feedback Widgets are displayed. 
  * `IMMERSIVE` mode (default): Full-screen display (except cutouts).
  * `SAFE_AREA` mode: Omits status bar, navigation bar and cutouts when displaying webviews.
* Added a new config option `disableGradualRequestCleaner()` to change request queue overflow behavior. When enabled, all overflowing requests are removed at once instead of in batches.
* Added a new method `requestQueue().addCustomNetworkRequestHeaders(Map<String,String>)` for providing or overriding custom headers after init .

* Mitigated a potential issue where Remote Config calls could have blocked the main UI thread processes.

* Immediate requests now will be run by parallel executor instead of serial by default.

## 25.4.2
* Some change
* Some other change
* New content

* Some fix

* Some deprecation

## NEW_VERSION_5
* Some change
* Some other change
* New content

* Some fix

* Some deprecation

## OLD_VERSION
* Some old change
* Some old other change

* Some old fix

## VERY_OLD_VERSION
* Some very old change
* Some very old other change

* Some very old deprecation

## VERY_VERY_OLD_VERSION
* Some very old change
