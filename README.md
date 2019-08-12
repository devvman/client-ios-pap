[![iOS 11]][iOS] [![Swift 5.0]][Swift] [![Carthage compatible]][Carthage] [![SPM compatible]][SPM] [![Accio supported]][Accio] [![Docs Percentage]][Docs]

# client-ios-pap
> test for docs


## Linting

Project uses [SwiftLint] - Version: `0.33.0`

1. see .swiftlint.yml file by  `open .swiftlint.yml -a Xcode` 
in terminal > project root directory.
2. Access Run Script in `Build Phases > SwiftLint Run Script`

#### Disabled Rules

	- block_based_kvo
	- multiple_closures_with_trailing_closure
	- type_name
	- trailing_whitespace
	- force_cast
	- line_length
	- nesting
	- opening_brace
	- identifier_name
	- cyclomatic_complexity
	- function_parameter_count
	- function_body_length
	- file_length

#### Opt In Rules

	- empty_count
	- missing_docs

## Documentation
Project uses [Jazzy] - Version: `0.10.0`

1. To view docs, open `docs/index.html` at root directory of project.
2. To generate docs use `jazzy --min-acl internal`
3. hold down following keys above property, function, class - `alt>command>forward slash` `⌥ + ⌘ + /`


(c) 2019 Devvman

<!--- External -->

[Docs]: https://client-ios-pap.herokuapp.com/
[Docs Percentage]: https://raw.github.com/devvman/client-ios-pap/heroku-pages/badge.svg?sanitize=true

[iOS 11]: https://img.shields.io/badge/iOS-11.0-orange.svg
[iOS]: https://developer.apple.com

[Swift 5.0]: https://img.shields.io/badge/Swift-5.0-orange.svg
[Swift]: https://swift.org

[Accio supported]: https://img.shields.io/badge/Accio-supported-0A7CF5.svg?style=flat
[Accio]: https://github.com/JamitLabs/Accio

[Carthage compatible]: https://img.shields.io/badge/Carthage-compatible-4BC51D.svg?style=flat
[Carthage]: https://github.com/Carthage/Carthage

[SPM compatible]: https://img.shields.io/badge/Swift%20Package%20Manager-compatible-brightgreen.svg
[SPM]: https://github.com/apple/swift-package-manager

[Jazzy]: https://github.com/realm/jazzy
[SwiftLint]: https://github.com/realm/SwiftLint
