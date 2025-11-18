# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [3.1.0](https://github.com/lotusnoir/ansible-system_local_users/compare/3.0.0...3.1.0) - 2025-11-18

### Commits

- fix molecule test image for rhel8 [`b6495cf`](https://github.com/lotusnoir/ansible-system_local_users/commit/b6495cf50cfaa952d8c7cd6cd1c92010e2b8382e)
- update core and molecule [`6235511`](https://github.com/lotusnoir/ansible-system_local_users/commit/6235511f3d392ccd55247516a625437e91ca1b11)
- add oraclelinux10 support + lint and core fixes [`af9be2f`](https://github.com/lotusnoir/ansible-system_local_users/commit/af9be2f26ccbddaaf93b31845c80d952cf0cd762)

## [3.0.0](https://github.com/lotusnoir/ansible-system_local_users/compare/2.0.0...3.0.0) - 2025-10-29

### Commits

- add trixie (debian13) support [`97adadd`](https://github.com/lotusnoir/ansible-system_local_users/commit/97adadd5542058c7502fc618290e82d961d3453d)
- update core, molecule + gitlab-ci [`543da9c`](https://github.com/lotusnoir/ansible-system_local_users/commit/543da9c0440c0053dca44b5e1bebe2ad702804e6)
- fix lint [`7766f23`](https://github.com/lotusnoir/ansible-system_local_users/commit/7766f235766d7025227ed9650514125392cbc3ce)
- fix molecule paralelism and little updates [`2a30564`](https://github.com/lotusnoir/ansible-system_local_users/commit/2a30564a44e4c4efd41175ebc20e39743a5179f0)
- add support for ubuntu24 [`439420d`](https://github.com/lotusnoir/ansible-system_local_users/commit/439420d10fb387ced95cc8a1e80715cbcf4675b7)
- add version on molecule play image to maintain support on old release [`d2f8474`](https://github.com/lotusnoir/ansible-system_local_users/commit/d2f8474f4d94c31f48279df6680b30bbb8ccca02)
- update molecule [`9e89070`](https://github.com/lotusnoir/ansible-system_local_users/commit/9e8907026aeb5893c6583d75033df9d401d15592)
- add redhat 9 to default supported distrib [`acb18a6`](https://github.com/lotusnoir/ansible-system_local_users/commit/acb18a6a73351d417e3ed4910bd4a1d1cd5d07cc)
- add redhat 8 to default supported distrib [`9c77795`](https://github.com/lotusnoir/ansible-system_local_users/commit/9c77795703eee4e1998f20a4c9093de0b19f4965)
- sort testing distrib to avoid random changes [`086cd9c`](https://github.com/lotusnoir/ansible-system_local_users/commit/086cd9c7d68c30f13438d3f77d81119671435158)

## [2.0.0](https://github.com/lotusnoir/ansible-system_local_users/compare/1.1.0...2.0.0) - 2023-09-25

### Commits

- update vars [`d40bc06`](https://github.com/lotusnoir/ansible-system_local_users/commit/d40bc06959d976fea30c77e68284a1deafe1b164)
- update readme + precommit + include vars [`544523c`](https://github.com/lotusnoir/ansible-system_local_users/commit/544523caad224b101f8533f05fb0ee10342bdb77)
- update molecule playbook order and main include vars [`74ee579`](https://github.com/lotusnoir/ansible-system_local_users/commit/74ee57935a196685731c4b733053fc515fab6acb)
- fix wrong default for missing password [`dad8465`](https://github.com/lotusnoir/ansible-system_local_users/commit/dad8465caf862d13f50388207830ccf4bd89b6a8)
- add options + fix [`bb5da48`](https://github.com/lotusnoir/ansible-system_local_users/commit/bb5da48204beaf1a3e411875537701b90d4a5f88)

## [1.1.0](https://github.com/lotusnoir/ansible-system_local_users/compare/1.0.0...1.1.0) - 2023-06-14

### Commits

- add debian12 support [`e4bed41`](https://github.com/lotusnoir/ansible-system_local_users/commit/e4bed41c4d57fb69f041a3771b8dc063f8106a29)
- remove sudo install as if shouldnt be support by this role [`736e442`](https://github.com/lotusnoir/ansible-system_local_users/commit/736e442f47d688aa10d8df63191062ada518982f)

## [1.0.0](https://github.com/lotusnoir/ansible-system_local_users/compare/0.2.0...1.0.0) - 2023-03-23

### Commits

- add code of conduc and small changes [`02aaf3b`](https://github.com/lotusnoir/ansible-system_local_users/commit/02aaf3b72c60f0ac8cf0a70c6c98f1bdcb788234)
- add precommit for lint [`4a8c9a6`](https://github.com/lotusnoir/ansible-system_local_users/commit/4a8c9a6859ec40e8d5e076c25247281a28be0839)
- fix checks [`208792e`](https://github.com/lotusnoir/ansible-system_local_users/commit/208792ebb9fc1a878f5c6634ae538f6f5d294a4a)
- add new molecule all scenario [`383eeac`](https://github.com/lotusnoir/ansible-system_local_users/commit/383eeac2c02f7f5f09b8e64f86de3d8f92878d11)
- split distro for molecule tests on ci [`89a74bc`](https://github.com/lotusnoir/ansible-system_local_users/commit/89a74bcb6779a3f8477d7681911d8ea4a1c758ed)
- update checks and Readme [`678d40d`](https://github.com/lotusnoir/ansible-system_local_users/commit/678d40d990197a78023c3cd941875fbd2a702331)
- add molecule fix for ora9 [`a91dc4d`](https://github.com/lotusnoir/ansible-system_local_users/commit/a91dc4dbb55bcc2ed215503c12d199b1e62a8d44)
- add ora9 support [`7358827`](https://github.com/lotusnoir/ansible-system_local_users/commit/7358827b7eda16a3be949e4fa30e7e25422512fb)
- update checks [`0e73d93`](https://github.com/lotusnoir/ansible-system_local_users/commit/0e73d931d3b6ce698be3505784b94d917bc2ade8)
- fix test and pipeline [`34fd632`](https://github.com/lotusnoir/ansible-system_local_users/commit/34fd632512bf1df2d6d31582f44166e8cbf335be)

## [0.2.0](https://github.com/lotusnoir/ansible-system_local_users/compare/0.1.0...0.2.0) - 2022-07-01

### Commits

- minor: add oracleLinux7 support [`a751ab2`](https://github.com/lotusnoir/ansible-system_local_users/commit/a751ab254c205c73feb13f444e80b484649aa73f)
- minor: add oracleLinux support + little fixes [`36f44a0`](https://github.com/lotusnoir/ansible-system_local_users/commit/36f44a025121ddf54209ab143aa85870161c1f45)
- minor: add ubuntu 22 molecule test + fix lint [`982d6ed`](https://github.com/lotusnoir/ansible-system_local_users/commit/982d6ed910fcf045afaa479a9b25fc6d8449e51b)

## 0.1.0 - 2022-06-02

### Commits

- fix: module error [`58b3165`](https://github.com/lotusnoir/ansible-system_local_users/commit/58b3165dc2a063fc3545cf61a5643f3630253774)
