MessagePack.swift
=================

[![CI Status](http://img.shields.io/travis/a2/MessagePack.swift.svg?style=flat)](https://travis-ci.org/a2/MessagePack.swift)
[![Version](https://img.shields.io/cocoapods/v/MessagePack.swift.svg?style=flat)](http://cocoapods.org/pods/MessagePack.swift)
[![License](https://img.shields.io/cocoapods/l/MessagePack.swift.svg?style=flat)](http://cocoapods.org/pods/MessagePack.swift)
[![Platform](https://img.shields.io/cocoapods/p/MessagePack.swift.svg?style=flat)](http://cocoapods.org/pods/Oberholz)

A fast, zero-dependency MessagePack implementation written in Swift 3. Supports Apple platforms and Linux.

## Installation

### CocoaPods

To use CocoaPods, add the following to your Podfile:

```ruby
pod 'MessagePack.swift', '~> 2.1.0'
```

### Carthage

To use Carthage, add the following to your Cartfile:

```ogdl
github "a2/MessagePack.swift" >= 2.1.0
```

### SPM (Swift Package Manager)

You can easily integrate MessagePack.swift in your app with SPM. Just add MessagePack.swift as a dependency:

```swift
import PackageDescription

let package = Package(
    name: "MyAwesomeApp",
    dependencies: [
        .Package(url: "https://github.com/a2/MessagePack.swift.git", majorVersion: 2, minor: 1),
    ]
)
```

## Version

2.x supports Swift 3. Support for Swift 2 was dropped after [1.2.0](https://github.com/a2/MessagePack.swift/releases/tag/1.2.0).

## Authors

Alexsander Akers, me@a2.io

## License

MessagePack.swift is available under the MIT license. See the LICENSE file for more info.
