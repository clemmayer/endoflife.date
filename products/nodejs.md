---
permalink: /nodejs
alternate_urls:
-   /node
-   /node.js
category: lang
title: Node.js
iconSlug: nodedotjs
releasePolicyLink: https://nodejs.org/about/releases/
releaseImage: https://raw.githubusercontent.com/nodejs/Release/master/schedule.svg?sanitize=true
changelogTemplate: https://github.com/nodejs/node/blob/master/doc/changelogs/CHANGELOG_V__RELEASE_CYCLE__.md#__LATEST__
activeSupportColumn: true
auto:
-   git: https://github.com/nodejs/node.git
versionCommand: node --version
releaseDateColumn: true
releases:
-   releaseCycle: "19"
    support: 2023-04-01
    eol: 2023-06-01
    latest: "19.0.0"
    latestReleaseDate: 2022-10-18
    releaseDate: 2022-10-18
-   releaseCycle: "18"
    lts: 2022-10-25
    support: 2023-10-18
    eol: 2025-04-30
    latest: "18.12.0"
    latestReleaseDate: 2022-10-25
    releaseDate: 2022-04-19
-   releaseCycle: "17"
    support: 2022-04-01
    eol: 2022-06-01
    latest: "17.9.1"
    latestReleaseDate: 2022-06-01
    releaseDate: 2021-10-19
-   releaseCycle: "16"
    lts: 2021-10-26
    support: 2022-10-18
    eol: 2023-09-11
    latest: "16.18.0"
    latestReleaseDate: 2022-10-12
    releaseDate: 2021-04-20
-   releaseCycle: "15"
    support: 2021-04-01
    eol: 2021-06-01
    latest: "15.14.0"
    latestReleaseDate: 2021-04-06
    releaseDate: 2020-10-20
-   releaseCycle: "14"
    lts: 2020-10-27
    support: 2021-10-19
    eol: 2023-04-30
    latest: "14.21.0"
    latestReleaseDate: 2022-11-01
    releaseDate: 2020-04-21
-   releaseCycle: "13"
    support: 2020-04-01
    eol: 2020-06-01
    latest: "13.14.0"
    releaseDate: 2019-10-22
    latestReleaseDate: 2020-04-29
-   releaseCycle: "12"
    lts: 2019-10-21
    support: 2020-10-20
    eol: 2022-04-30
    latest: "12.22.12"
    latestReleaseDate: 2022-04-05
    releaseDate: 2019-04-23
-   releaseCycle: "11"
    support: 2019-04-01
    eol: 2019-06-30
    latest: "11.15.0"
    releaseDate: 2018-10-23
    latestReleaseDate: 2019-04-30
-   releaseCycle: "10"
    lts: 2018-10-30
    support: 2020-05-19
    eol: 2021-04-30
    latest: "10.24.1"
    latestReleaseDate: 2021-04-06
    releaseDate: 2018-04-24
-   releaseCycle: "9"
    support: 2018-06-30
    eol: 2018-06-30
    latest: "9.11.2"
    releaseDate: 2017-10-31
    latestReleaseDate: 2018-06-12
-   releaseCycle: "8"
    lts: 2017-10-31
    support: 2019-01-01
    eol: 2019-12-31
    latest: "8.17.0"
    releaseDate: 2017-05-30
    latestReleaseDate: 2019-12-17
-   releaseCycle: "7"
    support: 2017-06-30
    eol: 2017-06-30
    latest: "7.10.1"
    releaseDate: 2016-10-25
    latestReleaseDate: 2017-07-11
-   releaseCycle: "6"
    support: 2018-04-30
    lts: 2016-10-18
    eol: 2019-04-30
    latest: "6.17.1"
    releaseDate: 2016-04-26
    latestReleaseDate: 2019-04-03
-   releaseCycle: "5"
    support: 2016-06-30
    eol: 2016-06-30
    latest: "5.12.0"
    releaseDate: 2015-10-30
    latestReleaseDate: 2016-06-23
-   releaseCycle: "4"
    support: 2017-04-01
    eol: 2018-04-30
    latest: "4.9.1"
    releaseDate: 2015-09-09
    lts: 2015-10-01
    latestReleaseDate: 2018-03-29
-   releaseCycle: "3"
    support: false
    eol: true
    latest: "3.3.1"
    releaseDate: 2015-08-04
    latestReleaseDate: 2015-09-15
-   releaseCycle: "2"
    support: false
    eol: true
    latest: "2.5.0"
    releaseDate: 2015-05-04
    latestReleaseDate: 2015-07-28
-   releaseCycle: "1"
    support: false
    eol: true
    latest: "1.8.4"
    releaseDate: 2015-01-20
    latestReleaseDate: 2015-07-09

---

> [Node.js](https://nodejs.org/) is an open-source, cross-platform JavaScript run-time environment built on Chrome's V8 JavaScript engine that executes JavaScript code outside of a browser.

Major Node.js versions enter Current release status for six months, which gives library authors time to add support for them. After six months, odd-numbered releases (9, 11, etc.) become unsupported, and even-numbered releases (10, 12, etc.) move to Active LTS status and are ready for general use. LTS release status is "long-term support", which typically guarantees that critical bugs will be fixed for a total of 30 months. Production applications should only use Active LTS or Maintenance LTS releases.

If a even-numbered release above is _not marked as LTS_, then it has not entered "Active LTS" and is not recommended for Production use.

The End-of-Life date for Node.js 16 was [moved forward by seven months][eol-16] to coincide with the end of support of OpenSSL 1.1.1 on September 11th, 2023.

[eol-16]: https://nodejs.org/en/blog/announcements/nodejs16-eol/ "Bringing forward the End-of-Life Date for Node.js 16"
