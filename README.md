![Flutter Community](https://raw.githubusercontent.com/fluttercommunity/community/master/welcome_banner.png)

# Flutter Community
**A central place for all community made Flutter packages.**

---

The Flutter Community is a GitHub organisation used to manage community made Flutter packages.

Our goal is to ensure packages made by the Flutter community are kept alive and maintained in one place.

## Medium Articles
To go along with the packages, we have started a Medium publication as a central location for community content to be published - especially if it relates to the packages here.

https://medium.com/flutter-community

# Submitting your packages
If you want your packages to be included in the Flutter Community organization, make sure you have read and completed the following steps.

<!--
## Guidelines
 - Android and iOS compatible
 - Package is published and approved on Dart pub.
 - ...
-->

## Preperation
In order for the Flutter Community organization to keep track of all the submitted packages and their maintainer, all repositories are required to contain a `COMMUNITY_INFO.yaml` file **in the root of the repository**. This file contains information about the package, pub page and maintainer.

**Note, without this file your package will not be listed in the [packages table](#Packages).**

### COMMUNITY_INFO.yaml
This is no longer a requirement and alternative solutions are being worked on. TBA.

#### Example

Your `COMMUNITY_INFO.yaml` file should look something like this (example taken from [after_layout](https://github.com/fluttercommunity/flutter_after_layout)):
```yaml
is_package: true
package_name: after_layout
maintainer_name: Simon Lightfoot
maintainer_username: slightfoot
package_description: Brings functionality to execute code after the first layout of a widget has been performed.
pub_package_name: after_layout
```

## Getting in contact
If you've [prepared your packages](#preperation), you can either:
- **RECOMMENDED**: [Open an issue on the `community` repository.](https://github.com/fluttercommunity/community/issues/new)
- Contact us in the Study Group.

### Note to packages owners
This is only a branding change. The idea is to promote the integrity of packages. Not all packaged will be accepted.

# Packages

| Name | Release | Description | Maintainer
| --- | --- | --- | --- |
| [**after_layout**](https://github.com/fluttercommunity/flutter_after_layout) | [![Pub](https://img.shields.io/pub/v/after_layout.svg)](https://pub.dartlang.org/packages/after_layout) | Brings functionality to execute code after the first layout of a widget has been performed. | [Simon&nbsp;Lightfoot](https://github.com/slightfoot)
| [**sticky_headers**](https://github.com/fluttercommunity/flutter_sticky_headers) | [![Pub](https://img.shields.io/pub/v/sticky_headers.svg)](https://pub.dartlang.org/packages/sticky_headers) | Lets you place headers on scrollable content that will stick to the top of the container whilst the content is scrolled. | [Simon&nbsp;Lightfoot](https://github.com/slightfoot)
| [**get_it**](https://github.com/fluttercommunity/get_it) | [![Pub](https://img.shields.io/pub/v/get_it.svg)](https://pub.dartlang.org/packages/get_it) | Simple direct Service Locator that allows to decouple the interface from a concrete implementation and to access the concrete implementation from everywhere in your App. | [Thomas&nbsp;Burkhart](https://github.com/escamoteur)
| [**rx_command**](https://github.com/fluttercommunity/rx_command) | [![Pub](https://img.shields.io/pub/v/rx_command.svg)](https://pub.dartlang.org/packages/rx_command) | Reactive event handler wrapper class inspired by ReactiveUI. | [Thomas&nbsp;Burkhart](https://github.com/escamoteur)
| [**draggable_scrollbar**](https://github.com/fluttercommunity/flutter-draggable-scrollbar) | [![Pub](https://img.shields.io/pub/v/draggable_scrollbar.svg)](https://pub.dartlang.org/packages/draggable_scrollbar) | A scrollbar that can be dragged for quickly navigation through a vertical list with optional label next to scrollthumb with information about current item. | [Marina&nbsp;Kuznetsova](https://github.com/marica27)
