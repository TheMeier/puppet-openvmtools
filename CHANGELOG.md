# Changelog

All notable changes to this project will be documented in this file.
Each new release typically also includes the latest modulesync defaults.
These should not affect the functionality of the module.

## [v2.1.0](https://github.com/voxpupuli/puppet-openvmtools/tree/v2.1.0) (2021-07-25)

[Full Changelog](https://github.com/voxpupuli/puppet-openvmtools/compare/v2.0.1...v2.1.0)

**Breaking changes:**

- Require puppet-epel over stahnma-epel [\#29](https://github.com/voxpupuli/puppet-openvmtools/pull/29) ([dhoppe](https://github.com/dhoppe))

**Implemented enhancements:**

- Add support for Ubuntu 20.04 [\#45](https://github.com/voxpupuli/puppet-openvmtools/pull/45) ([timdeluxe](https://github.com/timdeluxe))
- Autodetect supported instead of using Hiera [\#41](https://github.com/voxpupuli/puppet-openvmtools/pull/41) ([ekohl](https://github.com/ekohl))
- Support Debian 10 [\#34](https://github.com/voxpupuli/puppet-openvmtools/pull/34) ([ajurjevi](https://github.com/ajurjevi))

**Fixed bugs:**

- Repair service management in Ubuntu 14.04 [\#46](https://github.com/voxpupuli/puppet-openvmtools/pull/46) ([timdeluxe](https://github.com/timdeluxe))
- Create /var/run/vmware directory [\#27](https://github.com/voxpupuli/puppet-openvmtools/pull/27) ([raphink](https://github.com/raphink))

**Closed issues:**

- Support Debian 10 [\#33](https://github.com/voxpupuli/puppet-openvmtools/issues/33)
- Ubuntu family is "not supported" [\#30](https://github.com/voxpupuli/puppet-openvmtools/issues/30)

**Merged pull requests:**

- Convert class parameters to puppet-strings [\#43](https://github.com/voxpupuli/puppet-openvmtools/pull/43) ([ekohl](https://github.com/ekohl))
- Typo fixed \(line 71\) [\#39](https://github.com/voxpupuli/puppet-openvmtools/pull/39) ([kant](https://github.com/kant))
- Fix regex\_replace error on puppet 5 [\#36](https://github.com/voxpupuli/puppet-openvmtools/pull/36) ([jsosic](https://github.com/jsosic))
- Fix Ubuntu [\#35](https://github.com/voxpupuli/puppet-openvmtools/pull/35) ([ghoneycutt](https://github.com/ghoneycutt))
- modulesync 3.0.0 & puppet-lint updates [\#31](https://github.com/voxpupuli/puppet-openvmtools/pull/31) ([bastelfreak](https://github.com/bastelfreak))

## [v2.0.1](https://github.com/voxpupuli/puppet-openvmtools/tree/v2.0.1) (2020-01-25)

[Full Changelog](https://github.com/voxpupuli/puppet-openvmtools/compare/v2.0.0...v2.0.1)

**Closed issues:**

- Publishing on the forge? [\#23](https://github.com/voxpupuli/puppet-openvmtools/issues/23)

## [v2.0.0](https://github.com/voxpupuli/puppet-openvmtools/tree/v2.0.0) (2020-01-17)

[Full Changelog](https://github.com/voxpupuli/puppet-openvmtools/compare/1.1.0...v2.0.0)

**Breaking changes:**

- Modulesync 2.7.0 and drop Puppet 4 support [\#15](https://github.com/voxpupuli/puppet-openvmtools/pull/15) ([pillarsdotnet](https://github.com/pillarsdotnet))
- Require at least Puppet 6, support RedHat-7 and FreeBSD, support `vgauthd`, and various other small fixes [\#14](https://github.com/voxpupuli/puppet-openvmtools/pull/14) ([pillarsdotnet](https://github.com/pillarsdotnet))

**Implemented enhancements:**

- override $supported flag [\#5](https://github.com/voxpupuli/puppet-openvmtools/issues/5)
- Collision with existing vmware-tools [\#3](https://github.com/voxpupuli/puppet-openvmtools/issues/3)
- CentOS 6 support through epel [\#2](https://github.com/voxpupuli/puppet-openvmtools/issues/2)

**Closed issues:**

- Broken link in README.md [\#19](https://github.com/voxpupuli/puppet-openvmtools/issues/19)
- Possible move to voxpupuli [\#12](https://github.com/voxpupuli/puppet-openvmtools/issues/12)

**Merged pull requests:**

- Add missing changelog [\#24](https://github.com/voxpupuli/puppet-openvmtools/pull/24) ([dhoppe](https://github.com/dhoppe))
- Fix broken link. [\#20](https://github.com/voxpupuli/puppet-openvmtools/pull/20) ([pillarsdotnet](https://github.com/pillarsdotnet))
- Remove duplicate CONTRIBUTING.md file [\#18](https://github.com/voxpupuli/puppet-openvmtools/pull/18) ([dhoppe](https://github.com/dhoppe))
- Drop support for Ubuntu 12.04 LTS [\#17](https://github.com/voxpupuli/puppet-openvmtools/pull/17) ([ghoneycutt](https://github.com/ghoneycutt))

## [1.1.0](https://github.com/voxpupuli/puppet-openvmtools/tree/1.1.0) (2017-07-16)

[Full Changelog](https://github.com/voxpupuli/puppet-openvmtools/compare/1.0.0...1.1.0)

## [1.0.0](https://github.com/voxpupuli/puppet-openvmtools/tree/1.0.0) (2015-04-11)

[Full Changelog](https://github.com/voxpupuli/puppet-openvmtools/compare/0.2.0...1.0.0)

**Fixed bugs:**

- Service error on Ubuntu 14.04 [\#1](https://github.com/voxpupuli/puppet-openvmtools/issues/1)

## [0.2.0](https://github.com/voxpupuli/puppet-openvmtools/tree/0.2.0) (2015-04-01)

[Full Changelog](https://github.com/voxpupuli/puppet-openvmtools/compare/0.1.0...0.2.0)

## [0.1.0](https://github.com/voxpupuli/puppet-openvmtools/tree/0.1.0) (2015-03-31)

[Full Changelog](https://github.com/voxpupuli/puppet-openvmtools/compare/851285ce0d9a7009de5891866786d3e11a1d1de5...0.1.0)



\* *This Changelog was automatically generated by [github_changelog_generator](https://github.com/github-changelog-generator/github-changelog-generator)*
