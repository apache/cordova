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
- [apache/cordova-windows](https://github.com/apache/cordova-windows)
- [apache/cordova-wp7](https://github.com/apache/cordova-wp7)
- [apache/cordova-bada](https://github.com/apache/cordova-bada)
- [apache/cordova-bada-wac](https://github.com/apache/cordova-bada-wac)
- [apache/cordova-bada-osx](https://github.com/apache/cordova-osx)

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

### [cordova-plugin-globalization](https://github.com/apache/cordova-plugin-globalization)

- Date: 2017-11
- Reason: Replacement [ECMA Internationalization API](https://www.ecma-international.org/ecma-402/1.0/) available in all relevant platforms
- Deprecation announcement and Migration guide: https://cordova.apache.org/news/2017/11/20/migrate-from-cordova-globalization-plugin.html

### [cordova-plugin-wkwebview-engine](https://github.com/apache/cordova-plugin-wkwebview-engine)

- Date: 2021-02
- Reason: WKWebView implementation is now provided by [cordova-ios@6](https://cordova.apache.org/announcements/2020/06/01/cordova-ios-release-6.0.0.html) making this plugin obsolete.
- Deprecation announcement and Migration guide: https://cordova.apache.org/2021/02/07/deprecate-wkwebview-engine.html

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
