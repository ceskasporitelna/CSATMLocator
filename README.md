#CSAS ATM Locator for iOS and WatchOS
This repository contains iOS application demonstrating the usage of API of Ceska Sporitelna a.s. to display ATMs near user location. WatchOS extension displays route to currently nearest ATM.

#Requirements
- iOS 9.0+
- Xcode 7.1+
- RxSwift 2.1.0+
- Alamofire 3.1.5+

#Installation

1) Install latest version of [Carthage](https://github.com/Carthage/Carthage) and make sure you have recent version of `git`.

2) Clone this repository using command `git clone git@github.com:ceskasporitelna/CSATMLocator.git`

3) Enter into cloned directory using command `cd CSATMLocator`.

6) Run command `carthage update` to download and set up dependencies and build schemes. This may take up to 30 minutes as dependencies have to be built for more platforms. Patience is the key to get everything working.

#Usage

##Running CSAS ATM Locator

To call API, you need first obtain WEB_API_KEY at [WebApi developer portal](https://developers.csas.cz/html/devs/) and set in `WebApi.swift` to atribute: `KEY`.

To see how the demo application works, just open the project `CSATMLocator.xcodeproj` in Xcode.

Implementation of the application is in group `CSATMLocator`. Pay special attention to `ApiManager.swift` to and `ApiClient.swift` to observe how to communicate with the API.

To run the app in Simulator or on your hardware, simply run the scheme `CSATMLocator`.


#Contributing
Contributions are more than welcome!

Please read our [contribution guide](CONTRIBUTING.md) to learn how to contribute to this project.

#Terms and License
This software is licensed under [MIT license](LICENSE.md).
