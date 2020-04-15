
# Hyperledger Fabric [![join the chat][rocketchat-image]][rocketchat-url]

[rocketchat-url]: https://chat.hyperledger.org/channel/fabric
[rocketchat-image]: https://open.rocket.chat/images/join-chat.svg

[![Build Status](https://dev.azure.com/Hyperledger/Fabric/_apis/build/status/Merge?branchName=release-1.4)](https://dev.azure.com/Hyperledger/Fabric/_build/latest?definitionId=51&branchName=release-1.4)
[![CII Best Practices](https://bestpractices.coreinfrastructure.org/projects/955/badge)](https://bestpractices.coreinfrastructure.org/projects/955)
[![Go Report Card](https://goreportcard.com/badge/github.com/hyperledger/fabric)](https://goreportcard.com/report/github.com/hyperledger/fabric)
[![GoDoc](https://godoc.org/github.com/hyperledger/fabric?status.svg)](https://godoc.org/github.com/hyperledger/fabric)
[![Documentation Status](https://readthedocs.org/projects/hyperledger-fabric/badge/?version=release-1.4)](http://hyperledger-fabric.readthedocs.io/en/release-1.4/?badge=release-1.4)

## self-made version
> use go mod to download the dependency;
> shut down the go mod to make;
> make sure if you got the same proxy I did in the Makefile;

**Note:** This is a **read-only mirror** of the formal [Gerrit](https://gerrit.hyperledger.org/r/#/admin/projects/fabric) repository,
where active development is ongoing. Issue tracking is handled in [Jira](https://jira.hyperledger.org/secure/Dashboard.jspa?selectPageId=10104).

This project is an _Active_ Hyperledger project. For more information on the history of this project see the [Fabric wiki page](https://wiki.hyperledger.org/display/fabric). Information on what _Active_ entails can be found in
the [Hyperledger Project Lifecycle document](https://wiki.hyperledger.org/display/HYP/Project+Lifecycle).
Hyperledger Fabric is a platform for distributed ledger solutions, underpinned
by a modular architecture delivering high degrees of confidentiality,
resiliency, flexibility and scalability. It is designed to support pluggable
implementations of different components, and accommodate the complexity and
intricacies that exist across the economic ecosystem.

Hyperledger Fabric delivers a uniquely elastic and extensible architecture,
distinguishing it from alternative blockchain solutions. Planning for the
future of enterprise blockchain requires building on top of a fully-vetted,
open source architecture; Hyperledger Fabric is your starting point.

## Releases

- [v1.4.6 - February 25, 2020](https://github.com/hyperledger/fabric/releases/tag/v1.4.6)
- [v1.4.5 - February 19, 2020](https://github.com/hyperledger/fabric/releases/tag/v1.4.5)
- [v1.4.4 - November 14, 2019](https://github.com/hyperledger/fabric/releases/tag/v1.4.4)
- [v1.4.3 - August 26, 2019](https://github.com/hyperledger/fabric/releases/tag/v1.4.3)
- [v1.4.2 - July 17, 2019](https://github.com/hyperledger/fabric/releases/tag/v1.4.2)
- [v1.4.1 - April 11, 2019](https://github.com/hyperledger/fabric/releases/tag/v1.4.1)
- [v1.4.1-rc1 - March 29, 2019](https://github.com/hyperledger/fabric/releases/tag/v1.4.1-rc1)
- [v1.4.0 - January 9, 2019](https://github.com/hyperledger/fabric/releases/tag/v1.4.0)
- [v1.4.0-rc2 - December 20, 2018](https://github.com/hyperledger/fabric/releases/tag/v1.4.0-rc2)
- [v1.4.0-rc1 - December 10, 2018](https://github.com/hyperledger/fabric/releases/tag/v1.4.0-rc1)
- [v1.3.0 - October 10, 2018](https://github.com/hyperledger/fabric/releases/tag/v1.3.0)
- [v1.3.0-rc1 - September 24, 2018](https://github.com/hyperledger/fabric/releases/tag/v1.3.0-rc1)
- [v1.2.0 - July 3, 2018](https://github.com/hyperledger/fabric/releases/tag/v1.2.0)
- [v1.2.0-rc1 - June 22, 2018](https://github.com/hyperledger/fabric/releases/tag/v1.2.0-rc1)
- [v1.1.0 - March 15, 2018](https://github.com/hyperledger/fabric/releases/tag/v1.1.0)
- [v1.1.0-rc1 - March 1, 2018](https://github.com/hyperledger/fabric/releases/tag/v1.1.0-rc1)
- [v1.1.0-alpha - January 25, 2018](https://github.com/hyperledger/fabric/releases/tag/v1.1.0-alpha)
- [v1.0.5 - December 6, 2017](https://github.com/hyperledger/fabric/releases/tag/v1.0.5)
- [v1.1.0-preview - November 1, 2017](https://github.com/hyperledger/fabric/releases/tag/v1.1.0-preview)
- [v1.0.4 - October 31, 2017](https://github.com/hyperledger/fabric/releases/tag/v1.0.4)
- [v1.0.3 - October 3, 2017](https://github.com/hyperledger/fabric/releases/tag/v1.0.3)
- [v1.0.2 - September 10, 2017](https://github.com/hyperledger/fabric/releases/tag/v1.0.2)
- [v1.0.1 - August 10, 2017](https://github.com/hyperledger/fabric/releases/tag/v1.0.1)
- [v1.0.0 - July 11, 2017](https://github.com/hyperledger/fabric/releases/tag/v1.0.0)
- [v1.0.0-rc1 - June 23, 2017](https://github.com/hyperledger/fabric/releases/tag/v1.0.0-rc1)
- [v1.0.0-beta - June 8, 2017](https://github.com/hyperledger/fabric/releases/tag/v1.0.0-beta)
- [v1.0.0-alpha2 - May 14, 2017](https://github.com/hyperledger/fabric/releases/tag/v1.0.0-alpha2)
- [v1.0.0-alpha - March 16, 2017](https://github.com/hyperledger/fabric/releases/tag/v1.0.0-alpha)
- [v0.6.1-preview - October 15, 2016](https://github.com/hyperledger/fabric/releases/tag/v0.6.0-preview)
- [v0.6.0-preview - September 16, 2016](https://github.com/hyperledger/fabric/releases/tag/v0.6.0-preview)

## Release Roadmap

Please visit the [Hyperledger Fabric wiki](https://wiki.hyperledger.org/display/fabric/Hyperledger+Fabric+Roadmap) for our release roadmap. We plan on a quarterly release cadence following the v1.1.0 release, delivering on a scoped set of themes and select features. Unless specified otherwise, all releases will be upgradable from the prior minor release.

## Documentation, Getting Started and Developer Guides

Please visit our
online documentation for
information on getting started using and developing with the fabric, SDK and chaincode:
- [v1.4](http://hyperledger-fabric.readthedocs.io/en/release-1.4/)
- [v1.3](http://hyperledger-fabric.readthedocs.io/en/release-1.3/)
- [v1.2](http://hyperledger-fabric.readthedocs.io/en/release-1.2/)
- [v1.1](http://hyperledger-fabric.readthedocs.io/en/release-1.1/)
- [v1.0](http://hyperledger-fabric.readthedocs.io/en/release-1.0/)
- [master branch (development)](http://hyperledger-fabric.readthedocs.io/en/master/)

It's recommended for first-time users to begin by going through the Getting Started section of the documentation in order to gain familiarity with the Hyperledger Fabric components and the basic transaction flow.

## Contributing

We welcome contributions to the Hyperledger Fabric project in many forms.
There’s always plenty to do! Check [the documentation on how to contribute to this project](http://hyperledger-fabric.readthedocs.io/en/latest/CONTRIBUTING.html)
for the full details.

## Testing
Check [the documentation](testingInfo.rst) for information on the testing structure that the project follows.

## Community

[Hyperledger Community](https://www.hyperledger.org/community)

[Hyperledger mailing lists and archives](http://lists.hyperledger.org/)

[Hyperledger Chat](http://chat.hyperledger.org/channel/fabric)

[Hyperledger Fabric Issue Tracking (JIRA)](https://jira.hyperledger.org/secure/Dashboard.jspa?selectPageId=10104)

[Hyperledger Fabric Wiki](https://wiki.hyperledger.org/display/Fabric)

[Hyperledger Wiki](https://wiki.hyperledger.org/)

[Hyperledger Code of Conduct](https://wiki.hyperledger.org/display/HYP/Hyperledger+Code+of+Conduct)

[Community Calendar](https://wiki.hyperledger.org/display/HYP/Calendar+of+Public+Meetings)

## License <a name="license"></a>

Hyperledger Project source code files are made available under the Apache License, Version 2.0 (Apache-2.0), located in the [LICENSE](LICENSE) file. Hyperledger Project documentation files are made available under the Creative Commons Attribution 4.0 International License (CC-BY-4.0), available at http://creativecommons.org/licenses/by/4.0/.
