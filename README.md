
# BlurEffect

[![Travis CI](https://img.shields.io/travis/0xxd0/BlurEffect.svg)](https://www.travis-ci.org/0xxd0/BlurEffect)
![CocoaPods](https://img.shields.io/cocoapods/v/BlurEffect.svg)
[![Carthage compatible](https://img.shields.io/badge/Carthage-compatible-4BC51D.svg?style=flat)](https://github.com/0xxd0/BlurEffect)
[![SPM compatible](https://img.shields.io/badge/SPM-compatible-4BC51D.svg?style=flat)](https://github.com/0xxd0/BlurEffect)
![](https://img.shields.io/github/repo-size/0xxd0/BlurEffect.svg)
[![Join the chat at https://gitter.im/0xxd0/BlurEffect](https://badges.gitter.im/0xxd0/BlurEffect.svg)](https://gitter.im/0xxd0/BlurEffect?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

A high performance blur effect on image in pure Swift.

- [Features](#features)
- [Requirement](#requirement)
- [Installation](#installation)
- [Usage](#usage)
- [License](#license)

## Features
 1. vImage based box blur
 2. stack blur
 3. OpenGL texture blur

## Requirement

![platform](https://img.shields.io/badge/platform-iOS%20%7C%20macOS%20%7C%20tvOS%20%7C%20watchOS-ed523f.svg) ![language](https://img.shields.io/github/languages/top/0xxd0/BlurEffect.svg?colorB=ed523f) ![Swift Version](https://img.shields.io/badge/Swift-3.2%20%7C%204.0-ed523f.svg) ![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/0xxd0/BlurEffect.svg?colorB=ed523f)

#### Required
- Xcode 9.0+
- iOS 8.0+ | macOS 10.10+ | tvOS 9.0+ | watchOS 2.0+
- Swift 3.2+

## Installation

### CocoaPods 

> ⚠️ Comming soon, you can use the master branch of the repository for now.

```ruby
target '<#Your Target#>' do
    pod 'BlurEffect', :git => 'https://github.com/0xxd0/BlurEffect.git'
end
```

***

[CocoaPods](http://cocoapods.org) CocoaPods is a dependency manager for Swift and Objective-C Cocoa projects. It has over 41 thousand libraries and is used in over 3 million apps. CocoaPods can help you scale your projects elegantly. 

#### Install Cocoapods

```bash
$ gem install cocoapods
```

#### Integrate BlurEffect

With CocoaPods, specify BlurEffect in your `Podfile`:

```ruby
source 'https://github.com/CocoaPods/Specs.git'
platform :ios, '8.0'
use_frameworks!

target '<#Your Target#>' do
    pod 'BlurEffect', '~> 0.0.1'
end
```

run pod install:

```bash
$ pod install
```

### Carthage

[Carthage](https://github.com/Carthage/Carthage) builds your dependencies and provides you with binary frameworks, but you retain full control over your project structure and setup. Carthage does not automatically modify your project files or your build settings.

#### Install Carthage 

```shell
$ brew update
$ brew install carthage
```

#### Integrate BlurEffect

Add following to Cartfile:

```
github "0xxd0/BlurEffect" ~> 0.0.1
```

### Swift Package Manager

The [Swift Package Manager](https://swift.org/package-manager/) is a tool for managing the distribution of Swift code. It’s integrated with the Swift build system to automate the process of downloading, compiling, and linking dependencies.

⚠️ SPM only support macOS or Linux. 

#### Integrate BlurEffect

```swift
// Package.swift
// swift-tools-version:3.0

let package = Package(
    name: "<#Your Target#>",
    dependencies: [
        // ···
        .Package(url: "https://github.com/0xxd0/BlurEffect.git", majorVersion: 0)
        // ···
    ]
)
```

### Manually

Download zip or clone repo and integrate into your project manually.

## Usage

Clone the project and see the **`BlurEffect.playground`** for detail usage.

## License
[![license](https://img.shields.io/github/license/0xxd0/BlurEffect.svg?colorA=24292e&colorB=24292e&style=flat)](https://github.com/0xxd0/BlurEffect/blob/master/LICENSE)

This project is released under the **MIT License**.
