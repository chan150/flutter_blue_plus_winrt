## 0.0.3
* Fix: ensure physical disconnection by explicitly closing all GATT services.
* Fix: potential race condition where a device might stay connected if disconnected during the connection process.
* Fix: properly clear characteristic and descriptor caches upon disconnection.

## 0.0.2
* Fix: a version issue with `flutter_blue_plus_platform_interface` #1

## 0.0.1
* Initial release.
