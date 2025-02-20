
3.0.0-rc.46 / 2021-09-10
==================

**fixes**
  * [[`596bca9`](http://github.com/cnpm/cnpmjs.org/commit/596bca908ee87504dfeb3dbf463b4d9a551d9f27)] - fix: fs-cnpm on dockerize config (#1656) (wxhuang <<wxhuang1985@gmail.com>>)
  * [[`bbae9d3`](http://github.com/cnpm/cnpmjs.org/commit/bbae9d3bc3a565a59c397a63c4301272ac4509e9)] - fix: new publish with token should add user to maintainers (#1662) (killa <<killa123@126.com>>)

3.0.0-rc.45 / 2021-07-28
==================

**features**
  * [[`d28af7f`](http://github.com/cnpm/cnpmjs.org/commit/d28af7fd7e1bf530ad2e5a73fa5a54d2caf5cf9b)] - feat: support custom tokenService (#1658) (killa <<killa123@126.com>>)

**others**
  * [[`e258241`](http://github.com/cnpm/cnpmjs.org/commit/e2582417fa06a82c2fbb4d08eaf764465683a00b)] - remove maintainers logic (#1654) (Solais <<924615994@qq.com>>)
3.0.0-rc.44 / 2021-06-11
==================

**features**
  * [[`a1e8a82`](https://github.com/cnpm/cnpmjs.org/commit/a1e8a8289276275b995d15b3c254fbdbace6dbae)] - feat: impl npm owner hooks (#1645) (killa <<killa123@126.com>>)

3.0.0-rc.43 / 2021-05-36
==================

**features**
  * [[`a21aed0`](https://github.com/cnpm/cnpmjs.org/commit/a21aed08c5fe1ea09f4fda157ac3c12bd609781d)] - feat: impl sync to/from backup files (#1612) (killa <<killa123@126.com>>)

**fixes**
  * [[`2245dc2`](https://github.com/cnpm/cnpmjs.org/commit/2245dc2967ec070b8bcc618ebfad0cd4cd297fb8)] - feat: impl accelerate request (#1637) (killa <<killa123@126.com>>)

3.0.0-rc.42 / 2021-04-30
==================

**features**
  * [[`a21aed0`](https://github.com/cnpm/cnpmjs.org/commit/a21aed08c5fe1ea09f4fda157ac3c12bd609781d)] - feat: impl sync to/from backup files (#1612) (killa <<killa123@126.com>>)

3.0.0-rc.39 / 2021-01-14
==================

**features**
  * [[`33dd355`](http://github.com/cnpm/cnpmjs.org/commit/33dd3554f5daf13de33f04128be6853ce120636f)] - feat: impl dist-tag hooks (#1612) (killa <<killa123@126.com>>)

3.0.0-rc.38 / 2021-01-12
==================

**features**
  * [[`c6040b`](http://github.com/cnpm/cnpmjs.org/commit/1c6040bc95610e23b4756baa09e8119cda2fe01e)] - performance: optimise query pkg latestModified  (#1611) (killa <<killa123@126.com>>)


3.0.0-rc.37 / 2020-10-21
==================

**features**
  * [[`39c3223`](http://github.com/cnpm/cnpmjs.org/commit/39c322332ffafc512bf56c1679d2904fece2ae07)] - feat: new registry api (#1597) (killa <<killa123@126.com>>)
  * [[`45f2f8b`](http://github.com/cnpm/cnpmjs.org/commit/45f2f8b31f095eeadf0f47e234d6eb225e6b197f)] - feat: impl registry token api (#1590) (killa <<killa123@126.com>>)
  * [[`e97835f`](http://github.com/cnpm/cnpmjs.org/commit/e97835f7020e945e59fa7a84b14ab58c580add1e)] - feat: support custom web middlewares (#1563) (fengmk2 <<fengmk2@gmail.com>>)
  * [[`3cb3fe0`](http://github.com/cnpm/cnpmjs.org/commit/3cb3fe02f01dd669ad4bd3aebca51c44eb9e5938)] - feat: list all package versions by date (#1557) (fengmk2 <<fengmk2@gmail.com>>)
  * [[`a8ff647`](http://github.com/cnpm/cnpmjs.org/commit/a8ff647aa0f73076f4625e395e5da8ced9f61680)] - feat: retry sync fail on cnpm registry (#1547) (fengmk2 <<fengmk2@gmail.com>>)
  * [[`2c511f2`](http://github.com/cnpm/cnpmjs.org/commit/2c511f2209329e95b0cbe7603fa98a7f93c66474)] - feat: add unpublishRemoveTarball mode (#1536) (Khaidi Chu <<i@2333.moe>>)
  * [[`19563f5`](http://github.com/cnpm/cnpmjs.org/commit/19563f58517ffaebed8006630bd467f15b71d9ff)] - feat: allow to disable npm audits proxy (#1430) (fengmk2 <<fengmk2@gmail.com>>)
  * [[`8e2367e`](http://github.com/cnpm/cnpmjs.org/commit/8e2367ee1676bd36a4112cf0f6dce2c4f422806e)] - feat: dont check db data on tgz download request (#1477) (fengmk2 <<fengmk2@gmail.com>>)
  * [[`be05886`](http://github.com/cnpm/cnpmjs.org/commit/be05886452803d46f614bdde497ccdec8e9ed734)] - feat: add vary header on cdn (fengmk2 <<fengmk2@gmail.com>>)
  * [[`ea46399`](http://github.com/cnpm/cnpmjs.org/commit/ea46399265615c70ee33d9cab9ba5d5ce312fb67)] - feat: allow disable search page (fengmk2 <<fengmk2@gmail.com>>)
  * [[`581925d`](http://github.com/cnpm/cnpmjs.org/commit/581925db9733d295be02e75f0090db05fd6bae75)] - feat: support cache-control header on registry request (#1468) (fengmk2 <<fengmk2@gmail.com>>)
  * [[`7f0c141`](http://github.com/cnpm/cnpmjs.org/commit/7f0c141ac2f7679b5322aadd537c5ff1bef0b032)] - feat: allow config request protocol (fengmk2 <<fengmk2@gmail.com>>)
  * [[`807187e`](http://github.com/cnpm/cnpmjs.org/commit/807187ebeb0b266828a59724234e1a99c3238eb3)] - feat: add redis cache to import list all versions api perf (#1441) (fengmk2 <<fengmk2@gmail.com>>)
  * [[`99c4c3f`](http://github.com/cnpm/cnpmjs.org/commit/99c4c3fe35a9fde805751ef3d44413413f053f45)] - feat: support customized middlewares (#1436) (Khaidi Chu <<i@2333.moe>>)
  * [[`4b57c11`](http://github.com/cnpm/cnpmjs.org/commit/4b57c118a0b044f41b1c98eaf92449221c984c15)] - feat: can override tgz download options (fengmk2 <<fengmk2@gmail.com>>)
  * [[`b395c66`](http://github.com/cnpm/cnpmjs.org/commit/b395c666be3ae6b237803239fae8678647f3b70b)] - feat: proxy npm audit request (#1419) (alsotang <<alsotang@gmail.com>>)
  * [[`a4a25f9`](http://github.com/cnpm/cnpmjs.org/commit/a4a25f9e381aa20e1ef1e709f320aae41f3ae466)] - feat: use faster etag instead of koa-etag (#1409) (fengmk2 <<fengmk2@gmail.com>>)
  * [[`90580a7`](http://github.com/cnpm/cnpmjs.org/commit/90580a72e56c69f8f03bbdb64d79b4b1b139fbbf)] - feat: configurable view directory (#1400) (Khaidi Chu <<i@2333.moe>>)
  * [[`ad2d341`](http://github.com/cnpm/cnpmjs.org/commit/ad2d341d2c9317b062a25363f4805aedfef3913b)] - feat: sync downloads total <= 10000 unpublish package (fengmk2 <<fengmk2@gmail.com>>)
  * [[`25a9030`](http://github.com/cnpm/cnpmjs.org/commit/25a90300473e6ac437e393de139cebde1e354e8c)] - feat: allow to close mysql trace (fengmk2 <<fengmk2@gmail.com>>)
  * [[`017af69`](http://github.com/cnpm/cnpmjs.org/commit/017af69cce23c870694d124f4a865864e5c061cd)] - feat: add badgeService define on config (#1387) (fengmk2 <<fengmk2@gmail.com>>)
  * [[`842c031`](http://github.com/cnpm/cnpmjs.org/commit/842c0316ede2b19b76d9c1ca790902de467c82e9)] - feat: show versions list on package page (#1386) (fengmk2 <<fengmk2@gmail.com>>)
  * [[`bd87907`](http://github.com/cnpm/cnpmjs.org/commit/bd87907b69d3e65aa544930b5c7f04e75bdbc773)] - feat: auto retry if download tgz error (#1363) (fengmk2 <<fengmk2@gmail.com>>)
  * [[`533c27f`](http://github.com/cnpm/cnpmjs.org/commit/533c27fa78323ee50fcd549115034915ea3017ef)] - feat: support nfs.url return multi urls (#1344) (fengmk2 <<fengmk2@gmail.com>>)
  * [[`e61c7fa`](http://github.com/cnpm/cnpmjs.org/commit/e61c7fa32bdc54ef4474a071da686c70e512b009)] - feat: support pass through querystring to tgz url (#1334) (fengmk2 <<fengmk2@gmail.com>>)
  * [[`34d3a1e`](http://github.com/cnpm/cnpmjs.org/commit/34d3a1eabe927dc5c8c87436e2b644c70a7abc2a)] - feat: auto sync delete packages which deleted in 24 hours (#1315) (fengmk2 <<fengmk2@gmail.com>>)
  * [[`4210b7b`](http://github.com/cnpm/cnpmjs.org/commit/4210b7bdf8bfe8dfa2578802fd1d14e7411d4ea6)] - feat: can config to not sync deleted versions (#1282) (fengmk2 <<fengmk2@gmail.com>>)
  * [[`56c9457`](http://github.com/cnpm/cnpmjs.org/commit/56c945740f545abe9ba55759f6b1502a3abc453d)] - feat: let opensearch host can be config (#1258) (fengmk2 <<fengmk2@gmail.com>>)

**fixes**
  * [[`b7089d3`](http://github.com/cnpm/cnpmjs.org/commit/b7089d33d400f9fd4fc398479d4dac5aab26b633)] - fix: set maintainer to current user if maintainer is undefined (#1592) (killa <<killa123@126.com>>)
  * [[`2b74e00`](http://github.com/cnpm/cnpmjs.org/commit/2b74e00cb9ae20e9cf2f06c54ef8dbe6a36b4066)] - fix: release 3.0.0-rc.35 fix npm include functions dir (fengmk2 <<fengmk2@gmail.com>>)
  * [[`61549b4`](http://github.com/cnpm/cnpmjs.org/commit/61549b47a2f49c163bef6994f1e0f5f761317975)] - fix: avoid "ENAMETOOLONG: name too long" error (#1583) (fengmk2 <<fengmk2@gmail.com>>)
  * [[`e7bafb2`](http://github.com/cnpm/cnpmjs.org/commit/e7bafb2ee9d80ce3ef4087a6b69bc17517f85ec5)] - fix: audit proxy test cases (#1537) (Khaidi Chu <<i@2333.moe>>)
  * [[`92b7216`](http://github.com/cnpm/cnpmjs.org/commit/92b72169a89cec333177d1ba65205a31e60ebbb2)] - fix: maintainer permission greater than scope (#1494) (Khaidi Chu <<i@2333.moe>>)
  * [[`f084eba`](http://github.com/cnpm/cnpmjs.org/commit/f084ebae2106c8d4435dc0385e493fe18c6cec8a)] - fix: cpu usage 100% in node@6.x (#1470) (Yiman Liu <<413893093@qq.com>>)
  * [[`8d57216`](http://github.com/cnpm/cnpmjs.org/commit/8d572169b7293a33035257d3525c66b0abb5b679)] - fix: add cache on total (fengmk2 <<fengmk2@gmail.com>>)
  * [[`585f55b`](http://github.com/cnpm/cnpmjs.org/commit/585f55bbcc0ce257bfab2f0f545dd8a89c66ca49)] - fix: download url pathname (fengmk2 <<fengmk2@gmail.com>>)
  * [[`da2f964`](http://github.com/cnpm/cnpmjs.org/commit/da2f9640b87f1b110210b7b8caaf26b4b854ede8)] - fix: dont override exists weburl (fengmk2 <<fengmk2@gmail.com>>)
  * [[`b094f56`](http://github.com/cnpm/cnpmjs.org/commit/b094f5692f83700f152dd6ea9eb65f67385f6b5f)] - fix: changes stream syncer without deps (fengmk2 <<fengmk2@gmail.com>>)
  * [[`65bca46`](http://github.com/cnpm/cnpmjs.org/commit/65bca46f3c275bac5dc7497eb266d84605f6f8f8)] - fix: don't cache npm_service.cnpmjs.org request (fengmk2 <<fengmk2@gmail.com>>)
  * [[`f9d4858`](http://github.com/cnpm/cnpmjs.org/commit/f9d4858862a4b70cb989c3c60478c2424ca2c139)] - fix: avoid toString as downloads count key (#1438) (fengmk2 <<fengmk2@gmail.com>>)
  * [[`8a2f744`](http://github.com/cnpm/cnpmjs.org/commit/8a2f744749fc9f1297ff298fafe14deacf67efea)] - fix: don't update __all__ downloads every times (#1417) (fengmk2 <<fengmk2@gmail.com>>)
  * [[`9bdb695`](http://github.com/cnpm/cnpmjs.org/commit/9bdb695375a800464636d70981f433b7a11dd82d)] - fix: proxy to source registry when package is public scoped with encoded path (#1415) (Albert Zhang <<label4king@163.com>>)
  * [[`8bd0a2d`](http://github.com/cnpm/cnpmjs.org/commit/8bd0a2d49195734afa988cce69804d8540bbda19)] - fix: swap compress middleware and notFound position (#1413) (alsotang <<alsotang@gmail.com>>)
  * [[`93d5def`](http://github.com/cnpm/cnpmjs.org/commit/93d5def8ac8882edbd526e5a7341e07c99463b25)] - fix: show package when non-semver version of semver tag (#1411) (Khaidi Chu <<i@2333.moe>>)
  * [[`6a8434e`](http://github.com/cnpm/cnpmjs.org/commit/6a8434e0cae391981579af1a0b533aff0008904f)] - fix: Don't display sync info when the sync mode is none (#1410) (XingKai Zhang <<jack_zhxk@163.com>>)
  * [[`4a3a851`](http://github.com/cnpm/cnpmjs.org/commit/4a3a851256483d438753b154d80d28c12c1d625c)] - fix: use <%- instead of <%= in user profile page (#1404) (Khaidi Chu <<i@2333.moe>>)
  * [[`3497bae`](http://github.com/cnpm/cnpmjs.org/commit/3497bae2b94237664716911de965a4b27afc083a)] - fix: Obfuscate email address (#1391) (Ankur Kumar <<ankurk91@users.noreply.github.com>>)
  * [[`9b8491b`](http://github.com/cnpm/cnpmjs.org/commit/9b8491b736ebcb98df02d26c41334cf7fce306dc)] - fix: use https://cdn.staticfile.org (fengmk2 <<fengmk2@gmail.com>>)
  * [[`fc79930`](http://github.com/cnpm/cnpmjs.org/commit/fc799304d8c6710e71364bdf1d1ed0961b9e8695)] - fix: should return `[done] Sync {name}` string when task finished (#1382) (fengmk2 <<fengmk2@gmail.com>>)
  * [[`3c20267`](http://github.com/cnpm/cnpmjs.org/commit/3c20267b22491cd2ac2d751ccc459cf1f4fb0f1f)] - fix: don't retry to save log when db error (#1381) (fengmk2 <<fengmk2@gmail.com>>)
  * [[`5149aa5`](http://github.com/cnpm/cnpmjs.org/commit/5149aa5a1eb01dfc17f8de1cb6c6abfecca0ed96)] - fix: proxy public package from source registry (#1375) (fengmk2 <<fengmk2@gmail.com>>)
  * [[`fc07a38`](http://github.com/cnpm/cnpmjs.org/commit/fc07a38bde81bd93ef9067f3aacb06ae8e76e12b)] - fix: make sure replicate pkg is the latest pkg (#1347) (fengmk2 <<fengmk2@gmail.com>>)
  * [[`17f8b66`](http://github.com/cnpm/cnpmjs.org/commit/17f8b6648b2cf8cb4cf17daef2a2477f74a671e8)] - fix: retry from registry when no_db_file error on replicate (fengmk2 <<fengmk2@gmail.com>>)
  * [[`d1fe6ce`](http://github.com/cnpm/cnpmjs.org/commit/d1fe6cede7b5a082eabfe9eb94225c9af9399e62)] - fix: add other_urls on download dist tarball (#1345) (fengmk2 <<fengmk2@gmail.com>>)
  * [[`8fbad39`](http://github.com/cnpm/cnpmjs.org/commit/8fbad397f3ab7177c6e6c9b458b4b0bf3d24fbd7)] - fix: use rimraf instead of fs.unlink (#1338) (Yiyu He <<dead_horse@qq.com>>)
  * [[`0121de3`](http://github.com/cnpm/cnpmjs.org/commit/0121de31a3b7a8da38e31fca4e10d973c07d79e7)] - fix: no need to resync again (#1336) (fengmk2 <<fengmk2@gmail.com>>)
  * [[`84a3037`](http://github.com/cnpm/cnpmjs.org/commit/84a3037d90d4b3a316752eda7440ff5c73b0872f)] - fix: avoid query too frequently (#1329) (fengmk2 <<fengmk2@gmail.com>>)
  * [[`1f60a01`](http://github.com/cnpm/cnpmjs.org/commit/1f60a0136c5f2e4a33827d1f36b38c49e1e3dec6)] - fix: replicate request error, try to request from official registry (#1316) (fengmk2 <<fengmk2@gmail.com>>)
  * [[`6f656a0`](http://github.com/cnpm/cnpmjs.org/commit/6f656a0736c7d1d8b58288ff97590d7cb1317ecd)] - fix: save sync last time when successes > 1000 (fengmk2 <<fengmk2@gmail.com>>)
  * [[`1b30146`](http://github.com/cnpm/cnpmjs.org/commit/1b30146e94e7e72f9e762947b1ecdbd176d64532)] - fix: npm >= v5.5.0 login need not `email` (#1275) (#1304) (wmzy <<1256573276@qq.com>>)
  * [[`820ae23`](http://github.com/cnpm/cnpmjs.org/commit/820ae23454f0f9755456681f3ced03e634cb3109)] - fix: control sync frequency (fengmk2 <<fengmk2@gmail.com>>)
  * [[`bfb29f8`](http://github.com/cnpm/cnpmjs.org/commit/bfb29f82c967cb68f4de3a314200d95a8c59baff)] - fix: use _npmUser reset the maintainers (fengmk2 <<fengmk2@gmail.com>>)
  * [[`95aa035`](http://github.com/cnpm/cnpmjs.org/commit/95aa035a275089b50dfc2590497e3bc7319f4f6b)] - fix: make sure maintainers exists on sync worker (liang feng <<anhulife@gmail.com>>)
  * [[`6c69a38`](http://github.com/cnpm/cnpmjs.org/commit/6c69a38a508812f0320866d70b555de02e1fc204)] - fix: if replicate error, retry from official registry (#1230) (fengmk2 <<fengmk2@gmail.com>>)
  * [[`43ffa99`](http://github.com/cnpm/cnpmjs.org/commit/43ffa995cb8a724e8cd04224c2f137d407bfe014)] - fix: "start" should wait for "stop" to remove the pid file(using Promise) (#1220) (cloudstone <<baby31529@gmail.com>>)
  * [[`6c019de`](http://github.com/cnpm/cnpmjs.org/commit/6c019de514c9f4a62db1a1814ca2359408609074)] - fix: changes_stream_syncer log url should not contain sync_upstream=true (fengmk2 <<fengmk2@gmail.com>>)

**others**
  * [[`522ad11`](http://github.com/cnpm/cnpmjs.org/commit/522ad11124f168788b28dd925417ae37eb9d3991)] - update readme for now situation (#1506) (alsotang <<alsotang@gmail.com>>)
  * [[`0c59791`](http://github.com/cnpm/cnpmjs.org/commit/0c59791e50ef9d3080d5a2ab3e24b5899bd91446)] - Release Release 3.0.0-rc.19 (fengmk2 <<fengmk2@gmail.com>>)
  * [[`79fb163`](http://github.com/cnpm/cnpmjs.org/commit/79fb163a3b12f1b9c4c9eafad7f2041e7c4c4dbf)] - chore: README fix typo ( not to use plural for code ) (#1448) (Paul Verest <<enide.github@gmail.com>>)
  * [[`be00b65`](http://github.com/cnpm/cnpmjs.org/commit/be00b6557359d328c851e538827d6c681c2c3416)] - refactor: add detail message to error and keep reason (#1445) (alsotang <<alsotang@gmail.com>>)
  * [[`f7e9670`](http://github.com/cnpm/cnpmjs.org/commit/f7e9670025c6e7f09d8aa88c676938a2cf4849b5)] - Release Release 3.0.0-rc.14 (fengmk2 <<fengmk2@gmail.com>>)
  * [[`d0c3f1b`](http://github.com/cnpm/cnpmjs.org/commit/d0c3f1b19e46e73ce389e78413304a1542811b5f)] - test: shouldjs change from getter to function call (#1420) (alsotang <<alsotang@gmail.com>>)
  * [[`d889eba`](http://github.com/cnpm/cnpmjs.org/commit/d889ebafbd6ff1bc15fbf277fd8e143a57e6cac6)] - deps: use agentkeepalive@4 (fengmk2 <<fengmk2@gmail.com>>)
  * [[`938a14d`](http://github.com/cnpm/cnpmjs.org/commit/938a14d0a13b711c7b91d795151a7266b0a43c5a)] - chore: Hall of Fame integration on README (#1388) (Gwenael Pluchon <<gwenael.pluchon+github@gmail.com>>)
  * [[`26d7147`](http://github.com/cnpm/cnpmjs.org/commit/26d7147562a1ae21db8bfec26983daf311353d96)] - refactor: normalize database structure (#1376) (Khaidi Chu <<i@2333.moe>>)
  * [[`5334375`](http://github.com/cnpm/cnpmjs.org/commit/53343751f7c0a34ea0a346172bff0818d27864dd)] - chore: add latest-3 tag (fengmk2 <<fengmk2@gmail.com>>)

3.0.0-alpha.8 / 2017-06-15
==================

  * fix: should remove unpublished version on ModuleAbbreviated too (#1192)
  * docs: Dockerized cnpmjs.org configuration with installation guide (#1191)

3.0.0-alpha.7 / 2017-06-01
==================

  * fix: add missing publish_time property on package list api (#1185)

3.0.0-alpha.6 / 2017-05-18
==================

  * feat: add globalHook on config (#1177)
  * fix: TypeError caused by invalid engines property (#1151)
  * test: add new test for application/vnd.npm.install-v1+json request

3.0.0-alpha.5 / 2017-04-14
==================

  * fix: should auto sync missing deprecated property (#1167)

3.0.0-alpha.4 / 2017-04-12
==================

  * fix: add missing deprecated on abbreviated meta (#1165)

3.0.0-alpha.2 / 2017-03-27
==================

  * fix: only get from package_readme table

3.0.0-alpha.1 / 2017-03-27
==================

  * chore: start 3.x
  * fix: ignore sync npm registry status 502
  * feat: remove readme from package
  * feat: [BREAKING_CHANGE] support abbreviated meta

2.19.4 / 2017-03-26
==================

  * feat: need to sync sourceNpmRegistry also (#1153)
  * docs: change user.json to utf8mb4

2.19.3 / 2017-02-22
==================

  * fix: should get package from orginal registry when package is unpublished (#1130)

2.19.2 / 2017-01-05
==================

  * fix: should auto sync un-deprecate message (#1105)

2.19.1 / 2016-12-29
==================

  * fix: try to use the best repository url (#1102)

2.19.0 / 2016-12-21
==================

  * feat: keyword search with limit to support keywords > 100 (#1097)

2.18.0 / 2016-12-05
==================

  * fix: support downloads total on scope package (#1088)
  * fix: try to sync from official replicate (#1076)
  * feat: add change password script (#1070)
  * test: skip always fail tests
  * test: add node v7
  * feat: show more sync info

2.17.2 / 2016-11-13
==================

  * fix: ignore long package name on unpublished sync (#1067)

2.17.1 / 2016-11-08
==================

  * fix: add publish_time for private packages (#1061)

2.17.0 / 2016-11-03
==================

  * feat: make snyk.io url configable (#1058)

2.16.2 / 2016-09-27
==================

  * fix: try to use config.registryHost first on setDownloadURL (#1044)

2.16.1 / 2016-08-22
==================

  * refactor: refine publishable's code (#1022)

2.16.0 / 2016-08-22
==================

  * feat: admin can do everything (#1021)

2.15.0 / 2016-08-22
==================

  * feat: return dist-tag on package registry ([#1020](https://github.com/cnpm/cnpmjs.org/issues/1020))
  * chore(package): update supertest to version 2.0.0 ([#1004](https://github.com/cnpm/cnpmjs.org/issues/1004))

2.14.0 / 2016-08-04
==================

  * feat: password may contains ":" ([#999](https://github.com/cnpm/cnpmjs.org/issues/999))
  * fix: limit sync fails email notice ([#1006](https://github.com/cnpm/cnpmjs.org/issues/1006))

2.13.0 / 2016-07-26
==================

  * feat: enable maxrequests middleware ([#1003](https://github.com/cnpm/cnpmjs.org/issues/1003))

2.12.2 / 2016-07-11
==================

  * fix: getModuleByRange don't list all packages ([#990](https://github.com/cnpm/cnpmjs.org/issues/990))
  * fix: should show new version package count ([#984](https://github.com/cnpm/cnpmjs.org/issues/984))

2.12.1 / 2016-07-01
==================

  * fix: make sure chagnes stream destroy ([#982](https://github.com/cnpm/cnpmjs.org/issues/982))
  * chore(package): update semver to version 5.2.0 ([#978](https://github.com/cnpm/cnpmjs.org/issues/978))
  * deps: use ^ instead of ~ ([#976](https://github.com/cnpm/cnpmjs.org/issues/976))
  * chore(package): update mini-logger to version 1.1.1 ([#973](https://github.com/cnpm/cnpmjs.org/issues/973))

2.12.0 / 2016-06-26
==================

  * fix: logger seperator should be one EOL ([#972](https://github.com/cnpm/cnpmjs.org/issues/972))
  * feat: add security check badge for public package ([#971](https://github.com/cnpm/cnpmjs.org/issues/971))

2.11.0 / 2016-06-25
==================

  * feat: add changes stream syncer ([#970](https://github.com/cnpm/cnpmjs.org/issues/970))
  * chore(package): update pg to version 5.1.0 ([#953](https://github.com/cnpm/cnpmjs.org/issues/953))

2.10.1 / 2016-06-05
==================

  * fix: should sync missing public scoped package on install ([#946](https://github.com/cnpm/cnpmjs.org/issues/946))
  * chore(package): update bytes to version 2.4.0 ([#943](https://github.com/cnpm/cnpmjs.org/issues/943))
  * userService ([#926](https://github.com/cnpm/cnpmjs.org/issues/926))
  * chore(package): update should to version 8.4.0 ([#928](https://github.com/cnpm/cnpmjs.org/issues/928))
  * chore(package): update humanize-ms to version 1.2.0 ([#927](https://github.com/cnpm/cnpmjs.org/issues/927))
  * chore(package): update kcors to version 1.2.1 ([#918](https://github.com/cnpm/cnpmjs.org/issues/918))
  * chore(package): update urllib to version 2.9.0 ([#898](https://github.com/cnpm/cnpmjs.org/issues/898))

2.10.0 / 2016-04-15
==================

  * feat: show tarball url on package page ([#894](https://github.com/cnpm/cnpmjs.org/issues/894))
  * chore(package): update koa-mock to version 1.6.1 ([#891](https://github.com/cnpm/cnpmjs.org/issues/891))

2.9.5 / 2016-04-12
==================

  * fix: change logo url to a better https source
  * fix: http://cnpmjs.org/package/fms pre style ([#739](https://github.com/cnpm/cnpmjs.org/issues/739))

2.9.4 / 2016-04-09
==================

  * fix: don't sync constructor package on exists mode ([#883](https://github.com/cnpm/cnpmjs.org/issues/883))
  * Update utility to version 1.7.0 🚀
  * chore: update sponsor link

2.9.3 / 2016-04-05
==================

  * fix: use better diff time to check sync status
  * Update sequelize to version 3.21.0 🚀
  * chore(package): update agentkeepalive to version 2.1.0
  * chore(package): update pg to version 4.5.2

2.9.2 / 2016-03-29
==================

  * fix: override antd for ul & ol list number & icon.

2.9.1 / 2016-03-29
==================

  * refactor: add more ua info on syncer

2.9.0 / 2016-03-26
==================

  * feat: only admin can unpublish
  * chore(package): update gravatar to version 1.5.0
  * chore(package): update sequelize to version 3.20.0
  * fix: fix save download count unqiue constraint error
  * chore(package): update moment to version 2.12.0

2.8.1 / 2016-03-07
==================

  * fix: only send warning email if no any sync data after 24h
  * chore(package): update kcors to version 1.1.0
  * chore(package): update koa to version 1.2.0
  * chore(package): update urllib to version 2.8.0

2.8.0 / 2016-02-23
==================

  * fix: convert `*` to latest tag
  * deps: upgrade deps and remove node 2.0.0 support
  * doc: update sponsors on readme
  * fix: update copyright year
  * doc: fix disturl typo
  * deps: sequelize@3.19.0

2.7.1 / 2016-02-01
==================

  * fix(semver): when have invalid version([#817](https://github.com/cnpm/cnpmjs.org/issues/817))

2.7.0 / 2016-02-01
==================

  * test: fix all test cases
  * test: fix unpublish
  * test: add complex range test case
  * feat: support semver([#816](https://github.com/cnpm/cnpmjs.org/issues/816))

2.6.2 / 2016-01-19
==================

  * feat: list & show support jsonp
  * chore(package): update urllib to version 2.7.0
  * Delete install.md

2.6.1 / 2016-01-12
==================

  * fix: source registry is not cnpm, ignore check status

2.6.0 / 2016-01-12
==================

  * feat(sync): monitor sync status
  * chore(package): update agentkeepalive to version 2.0.3
  * fix SequelizeDatabaseError: ER_NO_SUCH_TABLE: Table 'qnpm.total' doesn't exist\nreproduce this bug:\nthe first startup of cnpmjs.org
  * chore(package): update moment to version 2.11.0
  * chore(package): update xss to version 0.2.10
  * chore(package): update pg-hstore to version 2.3.2
  * chore(package): update mini-logger to version 1.1.0
  * chore(package): update urllib to version 2.6.0
  * fix: row.package will json parse error
  * remove bluebird
  * chore(package): update utility to version 1.6.0

2.5.1 / 2015-12-02
==================

 * chore(package): update bluebird to version 3.0.6
 * fix: SequelizeDatabaseError
 * fix(dist_tag): disable delete latest tag
 * feat: count total private pkgs
 * fix: use isoweek. a week start from monday
 * chore(package): update xss to version 0.2.8
 * chore(package): update semver to version 5.1.0

2.5.0 / 2015-11-17
==================

 * test: add node v5
 * feat(sync): sync deleted user
 * Update show.js
 * chore(package): update bytes to version 2.2.0
 * do not sync inner username
 * gzip static file
 * chore(package): update bytes to version 2.1.0
 * chore(package): update is-type-of to version 1.0.0
 * Update static.js
 * chore(package): update cfork to version 1.4.0
 * chore(package): update bluebird to version 3.0.5

2.4.1 / 2015-10-27
==================

 * fix: improve registry index page performance with cache
 * Configable badge URL prefix.
 * chore(package): update koa-mock to version 1.5.0
 * chore(package): update urllib to version 2.5.0
 * chore(package): update co to version 4.6.0
 * chore(package): update semver to version 5.0.3

2.4.0 / 2015-10-21
==================

 * feat(registry): add package's dependents api
 * fix: show package's dependents
 * chore(package): update utility to version 1.5.0
 * chore(package): update bluebird to version 2.10.2

2.3.1 / 2015-10-15
==================

 * refactor: remove gnode
 * deps: upgrade giturl
 * Some fixes

2.3.0 / 2015-10-15
==================

 * Add dev dependencies.
 * Package page fix.
 * refactor: add more sync log
 * Add mock data.
 * refactor: add more sync log
 * Fix sidebar overflow.
 * Merge pull request [#680](https://github.com/cnpm/cnpmjs.org/issues/680) from ibigbug/ant-design
 * Clean code.
 * Indent.
 * chore(package): update debug to version 2.2.0
 * chore(package): update should to version 7.1.0
 * chore(package): update koa to version 1.1.0
 * Remove default adBanner.
 * Package pages.
 * Common styles.
 * search page.
 * Sync page.
 * Profile page antd style.
 * Unpublished pkg page style.
 * Add page title for unpubed pkg.
 * Index page style use antd.
 * chore(package): update pg to version 4.4.2
 * chore(package): update cfork to version 1.3.1
 * chore(package): update moment to version 2.10.6
 * feat(badge): Use qiniu cdn

2.2.1 / 2015-09-30
==================

 * test: use istanbul
 * pref: move out try/catch block
 * fix: support nfs.url is generator

2.2.0 / 2015-09-29
==================

 * feat: list packages by username
 * test: use codecov
 * feat(badge): support custom subject
 * fix(sync): add recover logic
 * feat(sync): add sync scripts

2.1.5 / 2015-09-05
==================

 * fix: only sync update packages

2.1.4 / 2015-09-05
==================

 * fix: support new array and old map format both
 * fix: /-/all/since had been redirect to /-/all/static/today.json
 * fix(list): let koa-etag to caculate the etag

2.1.3 / 2015-08-18
==================

 * fix: sync public scope package download url is wrong
 * fix: default registry change to taobao registry

2.1.2 / 2015-08-09
==================

 * fix(syncer): sync worker pkg null bug
 * feat(web): add downloads badge

2.1.1 / 2015-07-27
==================

 * fix: fix private scope package detect
 * fix: dont sync if upstream is npm registry
 * fix(sync): support sync public scope package
 * test: fix fails tests
 * fix: ignore 503 server error
 * fix: ignore sync 503 server error

2.1.0 / 2015-07-08
==================

 * feat(web): search support jsonp
 * fix function name

2.0.0 / 2015-05-11
==================

 * fix: real download as stream
 * add custom ad banner config
 * add sponsors: ucloud.cn
 * fix small typo
 * feat(urllib): support http_proxy
 * force using https links

2.0.0-rc.15 / 2015-02-15
==================

 * fix(markdown): filter xss after markdown render
 * feat(database): support PostgreSQL

2.0.0-rc.14 / 2015-02-14
==================

 * feat: support always-auth
 * fix mysql select args = [] bug
 * fix [#597](https://github.com/cnpm/cnpmjs.org/issues/597) sequelize raw query.
 * fix(markdown): hotfix markdown-it cpu problem
 * feat: upgrade to co4
 * use kcors fixes [#594](https://github.com/cnpm/cnpmjs.org/issues/594)

2.0.0-rc.13 / 2015-02-04
==================

 * docs: Deploy a private npm registry in 5 minutes
 * refactor(config): move application data to ~/.cnpmjs.org/
 * fix(sync): make get popular pakcage faster
 * feat(sync): web page also redirect to npm www
 * refactor(config): make syncModel to none by default
 * test: fix admin can not publish non-scoped package test cases
 * docs: add chinese mirror link
 * fix: admin can not publish non scoped package on "none" sync model
 * feat(sync): enable none syncModel proxy all public packages
 * fix: ignore username start with " or '
 * fix(bin): fix stop not work on iojs

2.0.0-rc.12 / 2015-02-01
==================

 * feat(syncer): add hostname ua
 * fix(web): remove pkg.contributors logic

2.0.0-rc.11 / 2015-02-01
==================

 * fix xss tests
 * fix(markdown): revert marky-markdown

2.0.0-rc.10 / 2015-01-31
==================

 * feat(middleware): CORS headers for GET and HEAD requests
 * fix(readme): fix index page markdown
 * feat(markdown): use npm same markdown parser
 * feat(download): support download redirect to nfs
 * feat(syncer): request npm registry with gzip
 * change(sync): remove dist syncer
 * feat(registry): add dist tag api
 * refactor(common): remove redis store

2.0.0-rc.9 / 2015-01-22 
==================

  * hotfix reame render error, pin xss
  * fix registry user auth api

2.0.0-rc.8 / 2015-01-10
==================

 * fix(markdown): readme.md allow scripts
 * fix(style) flexbox compatibility for both chrome and firefox (@afc163)
 * feat(sync): default sync exist packages

2.0.0-rc.7 / 2015-01-07
==================

 * install sync dont check `enablePrivate`
 * fix(markdown): filter xss readme before markdown render

2.0.0-rc.6 / 2015-01-05
==================

 * fix(markdown): use markdown-it
 * add userService options on config
 * add upload to nfs sync info log

2.0.0-rc.5 / 2015-01-03
==================

 * fix(markdown): use marked instead of remarkable
 * fix(package): pkg.readme is not a string, dont remarkable it
 * feat(sync): sync user profile

2.0.0-rc.4 / 2014-12-25
==================

 * refactor(download): try to use nsf.url() first
 * use __all__ for full downloads
 * refactor(download_total): optimize download total
 * fix sqlite raw sql return datetime is string format
 * fix(download_total): change column date to DateTime
 * fix(services/download_total): fix download_total slow sql on `date >= $start and date <= $end`
 * fix(markdown): replace marked use remarkable

2.0.0-rc.3 / 2014-12-14
==================

 * fix(services): need to detect instance isDirty or not before save()

2.0.0-rc.2 / 2014-12-11
==================

 * add download API, closes [#529](https://github.com/cnpm/cnpmjs.org/issues/529)
 * fix missing home page title (@rockdai)
 * Fix typo in view/web/package.html (@LoicMahieu)

2.0.0-rc.1 / 2014-12-09
==================

 * fix xss on title
 * feat(badge): support badge image url with tag

2.0.0-beta5 / 2014-12-05
==================

 * hotfix package.html typo. Closes [#521](https://github.com/cnpm/cnpmjs.org/issues/521)
 * Add editorconfig
 * fix(web/package): package name to long cause style problem fix
 * fix(css): use github-markdown-css for markdown body
 * feat(mock): use koa-mock for front end dev

2.0.0-beta4 / 2014-11-21
==================

 * fix(registry): add missing /-/short api
 * zoom sync link
 * new design for package page
 * image max width, fixed [#505](https://github.com/cnpm/cnpmjs.org/issues/505)
 * feat(middleware): block Ruby user-agent

2.0.0-beta3 / 2014-11-12
==================

 * fix(sync): should not sync package when maintainers sort change
 * fix(package): detect package is private or not
 * fix(maintainer): fix missing maintainers

2.0.0-beta2 / 2014-11-09
==================

 * fix(sync): add missing syncUpstreamFirst argument

2.0.0-beta1 / 2014-11-07
==================

 * refactor(sync_worker): only sync request need to sync upstream first
 * fix(sync_worker): make sure end event will emit
 * fix: mv readme.md script to public/js/readme.js
 * fix(sync): hotfix co uncaughtException
 * feat(sync): sync python dist
 * pin autod@1
 * remove useless comment
 * refactor models/_module_maintainer_class_methods.js

2.0.0-beta0 / 2014-11-02
==================

 * ungrade koa-markdown to use remarkable, close [#482](https://github.com/cnpm/cnpmjs.org/issues/482)
 * fix(module_log): limit module sync log size to 1MB
 * refactor(config): remove adaptScope config key
 * chore(Makefile): $ make install-production
 * fix(sequelize): show warnning message when using old config.js
 * docs(readme): Migrating from 1.x to 2.x
 * feat(sync): add min sync interval time detect
 * refactor(dispatch): remove unused codes
 * use sequelize to connect database

1.7.1 / 2014-10-15
==================

  * fix typo in sync popular, fix [#477](https://github.com/cnpm/cnpmjs.org/issues/477)

1.7.0 / 2014-10-15
==================

  * Merge pull request [#475](https://github.com/cnpm/cnpmjs.org/issues/475) from KidkArolis/configurable-short-registry-url
  * If sourceNpmRegistry is cnpm - use it in getShort
  * Merge pull request [#472](https://github.com/cnpm/cnpmjs.org/issues/472) from cnpm/issue468-upon
  * fix test label
  * add sync popular modules, close [#468](https://github.com/cnpm/cnpmjs.org/issues/468)
  * add sendmail test script

1.6.1 / 2014-10-09
==================

 * make test on travis faster
 * ensure not sync user also has his own package names
 * add [v1.6.x-upgrade.sql](https://github.com/cnpm/cnpmjs.org/blob/master/docs/update_sqls/v1.6.x-upgrade.sql)
 * save npm original package maintainers to npm_module_maintainer table. fixed [#464](https://github.com/cnpm/cnpmjs.org/issues/464)
 * use simple 404

1.6.0 / 2014-10-08
==================

 * list user all packages api. fixed [#462](https://github.com/cnpm/cnpmjs.org/issues/462)
 * add node-dev: $ make dev
 * always start sync worker
 * update node mailer
 * update autod

1.5.5 / 2014-09-25
==================

 * fix sync in web
 * sync upstream only the first package. make sync devDependencies optionsal, default is false
 * add some comment, default sourceNpmRegistryIsCNpm to true

1.5.4 / 2014-09-24
==================

 * format sync log

1.5.3 / 2014-09-24
==================

 * support sync upstream first. fixed [#451](https://github.com/cnpm/cnpmjs.org/issues/451)

1.5.2 / 2014-09-24
==================

 * support im url on user profile page; update bootstrap to 3.2.0

1.5.1 / 2014-09-23
==================

  * search support case insensitive, close [#450](https://github.com/cnpm/cnpmjs.org/issues/450)
  * add config._syncInWeb, close [#448](https://github.com/cnpm/cnpmjs.org/issues/448)
  * show maintainers when publish 403. fixed [#430](https://github.com/cnpm/cnpmjs.org/issues/430)
  * no attachment for html

1.5.0 / 2014-09-15
==================

  * dist sync document too. fixed [#420](https://github.com/cnpm/cnpmjs.org/issues/420)

1.4.4 / 2014-09-12
==================

  * badge version support 1.0.0-beta1. fixed [#440](https://github.com/cnpm/cnpmjs.org/issues/440)

1.4.3 / 2014-09-09
==================

  * alias /:name/-/:file to /:name/download/:file. fixed [#439](https://github.com/cnpm/cnpmjs.org/issues/439)

1.4.2 / 2014-09-03
==================

  * change default source registry to taobao's registry
  * Merge pull request [#435](https://github.com/cnpm/cnpmjs.org/issues/435) from cnpm/bluebird
  * add bluebird
  * bump fs-cnpm
  * Merge pull request [#434](https://github.com/cnpm/cnpmjs.org/issues/434) from cnpm/agent-stat
  * show agent sockets stat. fixed [#433](https://github.com/cnpm/cnpmjs.org/issues/433)
  * update readme
  * remove pic in readme

1.4.1 / 2014-08-20
==================

  * fix login error status

1.4.0 / 2014-08-20
==================

 * different version, different color badge, add version badge. fixed [#427](https://github.com/cnpm/cnpmjs.org/issues/427)
 * add download and node version badge

1.3.2 / 2014-08-18
==================

  * remove unused eventproxy
  * add custom config in tools/sync_not_exist.js

1.3.1 / 2014-08-18
==================

  * add sync not exist tools, close [#424](https://github.com/cnpm/cnpmjs.org/issues/424)
  * use gittip instand of alipay. close [#425](https://github.com/cnpm/cnpmjs.org/issues/425)
  * update registry api doc

1.3.0 / 2014-08-11
==================

  * ignore config/config.js
  * Merge pull request [#421](https://github.com/cnpm/cnpmjs.org/issues/421) from cnpm/qn-cnpm
  * fix test case
  * use fs-cnpm
  * fix test
  * use qn-cnpm
  * bump cfork

1.2.2 / 2014-08-08
==================

  * bump koa

1.2.1 / 2014-08-07
==================

 * deprecated bug fix and support undeprecate

1.2.0 / 2014-08-07
==================

 * show deprecated message
 * Sync deprecated field if it missing
 * Support $ cnpm deprecate [pkgname]@[version] "message". fixed [#415](https://github.com/cnpm/cnpmjs.org/issues/415)

1.1.0 / 2014-08-07
==================

 * Add user to maintainers when publish. fixed [#395](https://github.com/cnpm/cnpmjs.org/issues/395)
 * List all npm registry api. close [#413](https://github.com/cnpm/cnpmjs.org/issues/413)
 * limit list since
 * change deps by "~"
 * use cfork to make sure worker fork and restart
 * handle master uncaughtException. fixed [#403](https://github.com/cnpm/cnpmjs.org/issues/403)

1.0.6 / 2014-08-02
==================

 * WTF moment@2.8.0 missing

1.0.5 / 2014-08-02
==================

 * unpublish pkg@version bug hotfix. fixed [#400](https://github.com/cnpm/cnpmjs.org/issues/400)

1.0.4 / 2014-08-01
==================

 * hotfix [#399](https://github.com/cnpm/cnpmjs.org/issues/399) use not exists

1.0.3 / 2014-08-01
==================

 * add maintaining packages in user page

1.0.2 / 2014-08-01
==================

  * ~_~ fix auth error response message

1.0.1 / 2014-08-01
==================

  * Merge pull request [#398](https://github.com/cnpm/cnpmjs.org/issues/398) from cnpm/fix-auth
  * hot fix auth error

1.0.0 / 2014-08-01
==================

 * add private package list

0.9.2 / 2014-07-30
==================

 * hotfix save custom user bug

0.9.1 / 2014-07-30
==================

 * Handle user service auth throw custom error message
 * add test for config private packages
 * add config.privatePackages
 * add more comments in config/index.js

0.9.0 / 2014-07-29
==================

 * scopes init mv to services/user.js
 * show user more profile
 * registry show user support custom user service
 * support custom user service for user auth
 * remove session middleware
 * add DefaultUserService
 * check scopes in module.getAdapt
 * test public mode, fix some logic, close [#382](https://github.com/cnpm/cnpmjs.org/issues/382)
 * move scope.js into publishable.js, add forcePublishWithScope
 * config.scopes not exist, means do not support scope
 * add assert scope middleware

0.8.7 / 2014-07-24
==================

 * fix unpublished info missing maintainers cause TypeError

0.8.6 / 2014-07-23
==================

 * show unpublished info on web package page. fixes [#381](https://github.com/cnpm/cnpmjs.org/issues/381)

0.8.5 / 2014-07-22
==================

 * Only private package support default scoped. fixed [#378](https://github.com/cnpm/cnpmjs.org/issues/378)

0.8.4 / 2014-07-22
==================

 * adapt default scpoe in /@:scope/:name/:version

0.8.3 / 2014-07-22
==================

 * hot fix download

0.8.2 / 2014-07-22
==================

 * fix default scope detect

0.8.1 / 2014-07-21
==================

 * add more test cases
 * support default @org. close [#376](https://github.com/cnpm/cnpmjs.org/issues/376)
 * hotfix redis init error

0.8.0 / 2014-07-21
==================

 * support "scoped" packages. close [#352](https://github.com/cnpm/cnpmjs.org/issues/352)
 * use safe jsonp
 * Stop support old publish flow. fix [#368](https://github.com/cnpm/cnpmjs.org/issues/368)
 * update SQLs
 * use sync_info and sync_error categories
 * add categories to loggers. fix [#370](https://github.com/cnpm/cnpmjs.org/issues/370)
 * fix get latest tag always not exists bug
 * support `npm publish --tag beta`. fix [#366](https://github.com/cnpm/cnpmjs.org/issues/366)
 * use mini-logger and error-formater

0.7.0 / 2014-07-07
==================

 * use module_maintainers on GET /pakcage/:name page
 * use new module_maintainers on GET /:name
 * admin user should never publish to other user's packages. fix [#363](https://github.com/cnpm/cnpmjs.org/issues/363)
 * Add a new table for module-maintainers.
 * gravatar use https
 * support https

0.6.1 / 2014-06-18
==================

 * hot fix removeTagsByNames()
 * fix _rev not exists
 * sync unpublished on GET /sync/:name

0.6.0 / 2014-06-16
==================

 * sync unpublished info. close [#353](https://github.com/cnpm/cnpmjs.org/issues/353)
 * Delete not exists versions on sync worker. [#353](https://github.com/cnpm/cnpmjs.org/issues/353)

0.5.3 / 2014-06-13
==================

  * fix sync response 204
  * add links in History.md
  * bump koa
  * fix test-cov
  * bump koa and should

0.5.2 / 2014-06-04
==================

 * sync hotfix
 * sync phantomjs downloads pkg. close [#348](https://github.com/cnpm/cnpmjs.org/issues/348)
 * add restart, fixed [#346](https://github.com/cnpm/cnpmjs.org/issues/346)

0.5.1 / 2014-05-28
==================

 * fix attack on /-/all/since?stale=update_after&startkey=2 close [#336](https://github.com/cnpm/cnpmjs.org/issues/336)
 * bump thunkify-wrap
 * bump koa-middlewares
 * remove outputError
 * bump dependencies
 * use svg badge
 * add package/notfound page
 * add dist mirror link to home page
 * fix sync listdiff and add more test cases

0.5.0 / 2014-05-13
==================

 * filter /nightlies/*
 * use koa setter instead of set()
 * add more info on error email
 * add sync dist to sync/index.js
 * show dist page
 * sync dist file and save it to database
 * disable gzip before [#335](https://github.com/cnpm/cnpmjs.org/issues/335) has fix

0.4.3 / 2014-04-18
==================

  * Merge pull request [#334](https://github.com/cnpm/cnpmjs.org/issues/334) from cnpm/fix-permission
  * add permission check to /:name/:tag
  * Merge pull request [#333](https://github.com/cnpm/cnpmjs.org/issues/333) from cnpm/issue332-tag
  * fix space
  * add put /:name/:tag, close [#332](https://github.com/cnpm/cnpmjs.org/issues/332)

0.4.2 / 2014-04-17
==================

 * sync interval config
 * fix fav ico and show pkg size on pkg info page. fix [#318](https://github.com/cnpm/cnpmjs.org/issues/318)
 * sync work sync one done must wait for a defer.setImmediate. fix [#328](https://github.com/cnpm/cnpmjs.org/issues/328)
 * bump dep versions
 * if download tarball 404, throw err better than ignore it. fixed [#325](https://github.com/cnpm/cnpmjs.org/issues/325)
 * refator sync
 * hotfix, close [#321](https://github.com/cnpm/cnpmjs.org/issues/321)
 * hotfix, close [#319](https://github.com/cnpm/cnpmjs.org/issues/319)
 * support custom web home page
 * npm get short only can read from cnpm now
 * if using reverted proxy like nginx, only binding on local host
 * fix redis detect logic

0.4.1 / 2014-04-10
==================

 * fix sync status code error

0.4.0 / 2014-04-09
==================

 * fix test cases to run on local machine
 * add contribute guidelines
 * use local mysql for dev env. fix [#308](https://github.com/cnpm/cnpmjs.org/issues/308)
 * use copy to
 * use koa-compress and koa-conditional-get
 * maintainers is string, fix [#301](https://github.com/cnpm/cnpmjs.org/issues/301)

0.3.13 / 2014-03-27
==================

 * fix npm adduser update 409 bug
 * fix multiline coverage
 * show package engines. fixed [#280](https://github.com/cnpm/cnpmjs.org/issues/280)
 * dont sync local package field. fix [#295](https://github.com/cnpm/cnpmjs.org/issues/295)

0.3.12 / 2014-03-26
==================

 * fix result.successes not exist error
 * fix search list
 * add simple request for listall
 * only return package name in /-/all and /-/all/since, fixed [#291](https://github.com/cnpm/cnpmjs.org/issues/291)
 * refine docs foloder
 * use module gmt_modified as etag. fix [#288](https://github.com/cnpm/cnpmjs.org/issues/288)
 * fix typo, remove unused config in package.json
 * web page only list cnpm registry related info
 * use generator in qnfs

0.3.11 / 2014-03-20
==================

  * use common.isMaintainer, fixed [#283](https://github.com/cnpm/cnpmjs.org/issues/283)
  * update dependencies
  * use co-mocha for test, fixed [#279](https://github.com/cnpm/cnpmjs.org/issues/279)
  * update thunkify-wrap, breaking change in thunkify-wrap
  * refactor SQLs by using multiline
  * use multiline to refactor sqls
  * ignore contributors

0.3.10 / 2014-03-16
==================

  * Only /_session request send the authSession. fixed [#223](https://github.com/cnpm/cnpmjs.org/issues/223)
  * sync npm user info when maintainers and contributors not exists. fixed [#82](https://github.com/cnpm/cnpmjs.org/issues/82)
  * save npm user to mysql
  * password salt always be randoms
  * remove session access in /name and /name/version, fixed [#274](https://github.com/cnpm/cnpmjs.org/issues/274)
  * fix update maintainer session error
  * update koa-middlewares
  * fix test, fix sync_by_install
  * use defer session
  * Support npm owner|author add [name] [pkg]. fixed [#271](https://github.com/cnpm/cnpmjs.org/issues/271)

0.3.9 / 2014-03-14
==================

  * custom user-agent
  * use co-urllib instead of thunkify urllib; fix mock http.request test cases
  * request limit custom message
  * add config.redis check
  * add koa-limit, fixed [#267](https://github.com/cnpm/cnpmjs.org/issues/267)

0.3.8 / 2014-03-11
==================

  * update middlewares, fixed missing charset bug [#264](https://github.com/cnpm/cnpmjs.org/issues/264)

0.3.7 / 2014-03-11
==================

  * show worker die date time
  * update to koa@0.5.1
  * hotfix for star user
  * fix yield gather, sync missing deps even no missing versions
  * fix return versions
  * fix makefile, remove eventproxy
  * refactor sync_module_worker
  * add make test-dev, fixed [#259](https://github.com/cnpm/cnpmjs.org/issues/259)
  * change npm.js to generator
  * update urllib, proxy/npm.js use generator
  * sync_all and sync_exist to generator
  * change function to generator
  * need node >= v0.11.9

0.3.6 / 2014-03-06
==================

  * install missing package should sync it from source npm. fixed [#252](https://github.com/cnpm/cnpmjs.org/issues/252)
  * npm publish dont contains .jshint*
  * npm test run jshint
  * Add jshint check: $ make jshint
  * use `yield next` instead of `yield next`
  * replace dist.u.qiniudn.com with cnpmjs.org/dist

0.3.5 / 2014-03-05
==================

  * redirect /dist/xxx.tgz => http://dist.u.qiniudn.com/xxx.tgz fixed [#249](https://github.com/cnpm/cnpmjs.org/issues/249)
  * redirect /name to /package/name when /name is 404. fixed [#245](https://github.com/cnpm/cnpmjs.org/issues/245)
  * Add missing properies and sync missing star users. fixed [#235](https://github.com/cnpm/cnpmjs.org/issues/235)

0.3.4 / 2014-03-04
==================

  * add cov
  * use istanbul run test coverage
  * gzip support. fix [#241](https://github.com/cnpm/cnpmjs.org/issues/241)
  * readme spelling patch (@stanzheng)
  * default readme to null, fixed [#233](https://github.com/cnpm/cnpmjs.org/issues/233)
  * remove readme in versions

0.3.3 / 2014-02-28
==================

  * Merge pull request [#232](https://github.com/cnpm/cnpmjs.org/issues/232) from cnpm/host-hotfix
  * get request host from request.headers
  * Merge pull request [#231](https://github.com/cnpm/cnpmjs.org/issues/231) from cnpm/bug-fix
  * fix deps display bug[#230](https://github.com/cnpm/cnpmjs.org/issues/230) and nsf.url TypeError[#229](https://github.com/cnpm/cnpmjs.org/issues/229)

0.3.2 / 2014-02-28
==================

  * update koa-sess and koa-redis
  * fix sync all test
  * remove nfs.downloadStream first, fix tmppath error
  * fix fengmk2/giturl[#1](https://github.com/cnpm/cnpmjs.org/issues/1) bug

0.3.1 / 2014-02-27
==================

  * add etag fixed [#224](https://github.com/cnpm/cnpmjs.org/issues/224)
  * travis ci install on source npm

0.3.0 / 2014-02-27
==================

  * fix typo and dont sync not exists pkgs
  * use koa-middlewares
  * fix signed cookie not work on npm@1.3.25; node --harmony-generators
  * fix opensearch test case
  * update koa bodyparser
  * logger.error(err) should send err stack email notice
  * json body parse limit and bug fix.
  * fix sync 404 reason not clear
  * all controllers to koa
  * controller/web/user.js to koa
  * change web connect to koa
  * use outputError
  * use yield exports.addPackageAndDist.call(this, next);
  * add end() when ws write end
  * fix yield coWrite
  * fix all the test of registry module.test.js
  * convert registry/module.js to koa type
  * fix auth middleware
  * finish registry user controller koa and update mm to support thunkify. fixed [#196](https://github.com/cnpm/cnpmjs.org/issues/196)
  * change controllers/user.js to koa
  * thunkify all proxy
  * convert all middlewares to koa type
  * change regsitry sync to koa
  * addd koa-jsonp, koa-bodyparser, fix / controller
  * first koa run registry home page /
  * Merge pull request [#212](https://github.com/cnpm/cnpmjs.org/issues/212) from cnpm/fix-sync-404
  * return friendly 404 reason
  * Merge pull request [#211](https://github.com/cnpm/cnpmjs.org/issues/211) from cnpm/bug-fix
  * override json limit to default 10mb. fixed [#209](https://github.com/cnpm/cnpmjs.org/issues/209)
  * fix [#210](https://github.com/cnpm/cnpmjs.org/issues/210) addPackageAndDist package version detect bug

0.2.27 / 2014-02-19
==================

  * support json result in search, fixed [#189](https://github.com/cnpm/cnpmjs.org/issues/189)

0.2.26 / 2014-02-19
==================

  * npm publish also need to add deps

0.2.25 / 2014-02-19
==================

  * max handle number of package.json `dependencies` property
  * Dependents support. fixed [#190](https://github.com/cnpm/cnpmjs.org/issues/190)

0.2.24 / 2014-02-13
==================

  * fix if delete all the versions
  * refactor remove module, fixed [#186](https://github.com/cnpm/cnpmjs.org/issues/186)

0.2.23 / 2014-01-26
==================

  * system admin can add, publish, remove the packages. fixed [#176](https://github.com/cnpm/cnpmjs.org/issues/176)

0.2.22 / 2014-01-26
==================

  * add keyword and search support keyword. [#181](https://github.com/cnpm/cnpmjs.org/issues/181)

0.2.21 / 2014-01-24
==================

  * refactor code styles on package.html
  * nav-tabs e.preventDefault
  * Show registry server error response. fixed [#178](https://github.com/cnpm/cnpmjs.org/issues/178)
  * nav-tabs for package.html (@4simple)

0.2.20 / 2014-01-23
==================

  * hotfix sync missing dependencies and readmes
  * fix sync readme error, fixed [#174](https://github.com/cnpm/cnpmjs.org/issues/174)
  * add updateReadme in module

0.2.19 / 2014-01-22
==================

  * npm install no need to check authorization header. fixed [#171](https://github.com/cnpm/cnpmjs.org/issues/171)

0.2.18 / 2014-01-20
==================

  * Support gitlab git url to display and click. fixed [#160](https://github.com/cnpm/cnpmjs.org/issues/160)
  * fix redis crash

0.2.17 / 2014-01-17
==================

  * custom logo url
  * hotfix layout bug

0.2.16 / 2014-01-16
==================

  * fix publish-time bug

0.2.15 / 2014-01-16
==================

  * add publish_time to debug

0.2.14 / 2014-01-16
==================

  * add make autod
  * update publish_time, fixed [#163](https://github.com/cnpm/cnpmjs.org/issues/163)

0.2.13 / 2014-01-15
==================

  * markdown tmpl not support footer, need to wrap on app start

0.2.12 / 2014-01-15
==================

  * add footer and npm client name customable

0.2.11 / 2014-01-15
==================

  * package page contributor link to search, default is true

0.2.10 / 2014-01-14
==================

  * fix [#155](https://github.com/cnpm/cnpmjs.org/issues/155) Content-Disposition wrong.

0.2.9 / 2014-01-14
==================

  * support startkey=c and startkey="c"
  * support couch db search api. fixed [#153](https://github.com/cnpm/cnpmjs.org/issues/153)
  * fix fork me image link
  * support sync by query.name

0.2.8 / 2014-01-14
==================

  * dont show err stack on test env
  * add download link for package page

0.2.7 / 2014-01-13
==================

  * add shasum when nfs.upload and hfs.uploadBuffer, fixed [#148](https://github.com/cnpm/cnpmjs.org/issues/148)

0.2.6 / 2014-01-13
==================

  * support custom session store, fixed [#146](https://github.com/cnpm/cnpmjs.org/issues/146)

0.2.5 / 2014-01-13
==================

  * add download timeout and unit test
  * use downloadStream() first
  * nfs download to a writeable stream.

0.2.4 / 2014-01-10
==================

  * set main script to  index.js, fixed [#142](https://github.com/cnpm/cnpmjs.org/issues/142)

0.2.3 / 2014-01-10
==================

  * Dont show sync button on private package
  * Sync package as publish with no deps. fixed [#138](https://github.com/cnpm/cnpmjs.org/issues/138)

0.2.2 / 2014-01-10
==================

  * keep compatibility
  * qnfs upload only callback a url
  * compat remove package
  * set tarball url
  * new npm publish in one request, add _publish_in_cnpm
  * support unsure name ufs
  * contributors maybe a object
  * Object #<Object> has no method 'forEach' fixed [#134](https://github.com/cnpm/cnpmjs.org/issues/134)
  * support custom config as a module, fixed issue [#132](https://github.com/cnpm/cnpmjs.org/issues/132)
  * support npm new publish flow. fixed [#129](https://github.com/cnpm/cnpmjs.org/issues/129)
  * add toString and constructor to test admin
  * fix [#119](https://github.com/cnpm/cnpmjs.org/issues/119) hasOwnProperty check admin bug.

0.2.0 / 2013-12-27
==================

  * remove to lower case
  * fix [#127](https://github.com/cnpm/cnpmjs.org/issues/127) execSync and execsync.
  * add contributors list on package page
  * mv blanket to config
  * sync typeerror fix #statusCode
  * add disturl
  * fix [#122](https://github.com/cnpm/cnpmjs.org/issues/122) admin security bug
  * fixed [#121](https://github.com/cnpm/cnpmjs.org/issues/121), let pkg 404 as success
  * fix sql insert error
  * fix typos

0.1.3 / 2013-12-20
==================

  * add favicon
  * Fix auth middleware bug (@alsotang)
  * make sure all packages name are lower case
  * select ids from tag
  * fix nodejsctl
  * fix [#112](https://github.com/cnpm/cnpmjs.org/issues/112) missing versions and time no sync
  * remove restart command
  * fix sync missing packages error
  * fix web/readme.md, add install
  * fix [#109](https://github.com/cnpm/cnpmjs.org/issues/109) pkg no times and no versions bug.

0.1.2 / 2013-12-19
==================

  * fix times not exists canot sync bug. fixed [#101](https://github.com/cnpm/cnpmjs.org/issues/101)
  * support npm run command
  * remove before_install and install in travis, fixed [#102](https://github.com/cnpm/cnpmjs.org/issues/102)
  * split all sub queries, fixed [#104](https://github.com/cnpm/cnpmjs.org/issues/104)
  * fix doc, fixed [#103](https://github.com/cnpm/cnpmjs.org/issues/103)
  * fix search too slow.
  * dont email sync log level info
  * only sync missing packages at first time
  * update dependencies
  * sync all will sync all the missing packages, fixed [#97](https://github.com/cnpm/cnpmjs.org/issues/97)

0.1.0 / 2013-12-12
==================

  * add sync title
  * add favicon. fixed [#69](https://github.com/cnpm/cnpmjs.org/issues/69)
  * refine sync page, fiexd [#70](https://github.com/cnpm/cnpmjs.org/issues/70)
  * add app version
  * add test for sync
  * refine sync page
  * registry and web all use controllers/sync.js
  * sync from web, fixed [#58](https://github.com/cnpm/cnpmjs.org/issues/58)
  * saving missing descriptions
  * add package download info. fixed [#63](https://github.com/cnpm/cnpmjs.org/issues/63)
  * add avatar
  * use dependecies, fixed #issue62
  * support open search, fixed [#60](https://github.com/cnpm/cnpmjs.org/issues/60)
  * make sure publish_time and author is same to source npm registry. fixed [#56](https://github.com/cnpm/cnpmjs.org/issues/56)
  * add test for search
  * add a simple search by mysql like
  * fix This version of MySQL doesn't yet support 'LIMIT & IN/ALL/ANY/SOME subquery. fixed [#54](https://github.com/cnpm/cnpmjs.org/issues/54)
  * update install doc, use nodejsctl to start
  * must add limit on list by author sql
  * fix sql, change test to fit my local database, fixed [#46](https://github.com/cnpm/cnpmjs.org/issues/46)
  * use registry.cnpmjs.org
  * add install document and total package info on home page. fix [#42](https://github.com/cnpm/cnpmjs.org/issues/42)
  * add module_id to tag table. [#46](https://github.com/cnpm/cnpmjs.org/issues/46)
  * skip error version. fixed [#43](https://github.com/cnpm/cnpmjs.org/issues/43)
  * sync may make a user do not exist in database, but have modules in registry
  * add user page
  * fix set license
  * ignore 404 on sync. fixed [#39](https://github.com/cnpm/cnpmjs.org/issues/39)
  * fix module page, add test
  * update urllib to 0.5.5
  * version and tag
  * add module page
  * fix download url
  * first get tag, then try version
  * support sync triggle by install, finish [#31](https://github.com/cnpm/cnpmjs.org/issues/31)
  * addTag error return 500
  * just one download field
  * add download total info on home page
  * add download count
  * versions empty and also check missing tags
  * remove tags on unpublish
  * add module tag. fix [#6](https://github.com/cnpm/cnpmjs.org/issues/6)
  * add [done] flag to check sync done on client
  * get sync log [#29](https://github.com/cnpm/cnpmjs.org/issues/29)
  * fix test in module
  * rm tmp file on down request error
  * add time for debug str
  * fix pkg not exists null bug
  * use sync module woker to handle sync process. fixed [#19](https://github.com/cnpm/cnpmjs.org/issues/19)
  * if private mode enable, only admin can publish module
  * add alias in readme
  * fix sql, add sort by name
  * fix sql
  * add api to support npm search and auto completion
  * add npm and cnpm image
  * add registry total info on home page
  * fix mods bug in module.removeAll, change module.update => module.removeWithVersions
  * add test, fix bug. fixed [#18](https://github.com/cnpm/cnpmjs.org/issues/18)
  * spoort unpublish
  * add web page index readme
  * switchable nfs [#21](https://github.com/cnpm/cnpmjs.org/issues/21)
  * change file path to match npm file path
  * use qn cdn to store tarball file fixed [#16](https://github.com/cnpm/cnpmjs.org/issues/16)
  * add GET /:name/:version, fixed [#3](https://github.com/cnpm/cnpmjs.org/issues/3)
  * add module controller test cases; fix next module not exists logic bug.
  * publish module flow finish [#11](https://github.com/cnpm/cnpmjs.org/issues/11)
  * add test for controllers/registry/user.js
  * add test for middleware/auth
  * add test for proxy/user
  * remove index.js
  * fix typo
  * add redis as session store
  * fix nodejsctl mod
  * add start time
  * add home page
  * remove session controller
  * adduser() finish fixed [#5](https://github.com/cnpm/cnpmjs.org/issues/5)
  * rm app.js and routes.js
  * Mock npm adduser server response, fixing [#5](https://github.com/cnpm/cnpmjs.org/issues/5)
  * adjust project dir, separate registry and web server
  * Init rest frame for cnpmjs.org
  * init
