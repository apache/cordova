# Deprecated Apache Cordova components

Apache Cordova is a relatively old project. As such, we deprecated serveral of our components and ceased supporting and developing them over the years. (Read more about the process behind this in [cordova-contribute / Deprecation and Archiving](https://github.com/apache/cordova-contribute/blob/master/deprecation.md).)

## Deprecated Platforms

- [apache/cordova-blackberry](https://github.com/apache/cordova-blackberry)
- [apache/cordova-firefoxos](https://github.com/apache/cordova-firefoxos)
- [apache/cordova-ubuntu](https://github.com/apache/cordova-ubuntu)
- [apache/cordova-wp8](https://github.com/apache/cordova-wp8)
- [apache/cordova-tizen](https://github.com/apache/cordova-tizen)
- [apache/cordova-qt](https://github.com/apache/cordova-qt)
- [apache/cordova-webos](https://github.com/apache/cordova-webos)
- [apache/cordova-amazon-fireos](https://github.com/apache/cordova-amazon-fireos)
- [apache/cordova-wp7](https://github.com/apache/cordova-wp7)
- [apache/cordova-bada](https://github.com/apache/cordova-bada)
- [apache/cordova-bada-wac](https://github.com/apache/cordova-bada-wac)

## Deprecated Core Plugins

### [cordova-plugin-compat](https://github.com/apache/cordova-plugin-compat)

- Date: 2017-09
- Deprecation announcement: https://cordova.apache.org/news/2017/09/22/plugins-release.html
- Reason: `cordova-plugin-compat` has been integrated into the `cordova-android` 6.3.0 release. The plugin should be removed from projects using this or newer versions of `cordova-android`

### [cordova-plugin-console](https://github.com/apache/cordova-plugin-console)

- Date: 2017-09
- Deprecation announcement: https://cordova.apache.org/news/2017/09/22/plugins-release.html
- Reason: The plugin functionality was integrated into `cordova-ios` 4.5.0+. The plugin was not needed any more.

### [cordova-plugin-contacts](https://github.com/apache/cordova-plugin-contacts)

- Date: 2017-11
- Deprecation announcement: https://cordova.apache.org/news/2017/11/27/Deprecation-of-cordova-contacts-plugin.html
- Reason: various privacy and security issues

### [cordova-plugin-device-motion](https://github.com/apache/cordova-plugin-device-motion)

- Date: 2017-09
- Deprecation announcement: https://cordova.apache.org/news/2017/09/22/plugins-release.html
- Reason: The [W3C Device Motion and Orientation API](https://www.w3.org/TR/2016/CR-orientation-event-20160818/#devicemotion) now defines a way to access the accelerometer of the device
- Migration Guide: https://blog.phonegap.com/migrating-from-the-cordova-device-motion-plugin-ddd8176632ed

### [cordova-plugin-device-orientation](https://github.com/apache/cordova-plugin-device-orientation)

- Date: 2017-09
- Deprecation announcement: https://cordova.apache.org/news/2017/09/22/plugins-release.html
- Reason: The [W3C Device Motion and Orientation API](https://www.w3.org/TR/2016/CR-orientation-event-20160818/#devicemotion) now defines a way to access the compass of the device
- Migration Guide: https://blog.phonegap.com/migrating-from-the-cordova-device-orientation-plugin-8442b869e6cc

### [cordova-plugin-file-transfer](https://github.com/apache/cordova-plugin-file-transfer)

- Date: 2017-10
- Reason: `XMLHttpRequest` supports [download of binary data](https://developer.mozilla.org/en-US/docs/Web/API/XMLHttpRequest/Sending_and_Receiving_Binary_Data) on all relevant platforms and browsers
- Deprecation announcement and transition guide: https://cordova.apache.org/blog/2017/10/18/from-filetransfer-to-xhr2.html

### [cordova-plugin-globalization](https://github.com/apache/cordova-plugin-globalization)

- Date: 2017-11
- Reason: Replacement [ECMA Internationalization API](https://www.ecma-international.org/ecma-402/1.0/) available in all relevant platforms
- Deprecation announcement and Migration guide: https://cordova.apache.org/news/2017/11/20/migrate-from-cordova-globalization-plugin.html

### [cordova-plugin-legacy-whitelist](https://github.com/apache/cordova-plugin-legacy-whitelist)

## Deprecated Tooling

- [apache/cordova-medic](https://github.com/apache/cordova-medic)

## Deprecated Other

- [apache/cordova-weinre](https://github.com/apache/cordova-weinre)
- [apache/cordova-app-harness](https://github.com/apache/cordova-app-harness)
- [apache/cordova-plugin-compat](https://github.com/apache/cordova-plugin-compat)
- [apache/cordova-registry-web](https://github.com/apache/cordova-registry-web)
- [apache/cordova-registry](https://github.com/apache/cordova-registry)
- [apache/cordova-fauxton-server](https://github.com/apache/cordova-fauxton-server)
- [apache/cordova-template-reference](https://github.com/apache/cordova-template-reference)
