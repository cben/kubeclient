# Change Log

## [Unreleased](https://github.com/abonas/kubeclient/tree/HEAD)

[Full Changelog](https://github.com/abonas/kubeclient/compare/v2.5.1...HEAD)

**Fixed bugs:**

- Fix header markdown in README [\#296](https://github.com/abonas/kubeclient/pull/296) ([cben](https://github.com/cben))
- Fix README comment on Kubeclient::HttpError [\#288](https://github.com/abonas/kubeclient/pull/288) ([moolitayer](https://github.com/moolitayer))

**Closed issues:**

- support as: :raw for watch [\#282](https://github.com/abonas/kubeclient/issues/282)
- no get\_hpa support? [\#278](https://github.com/abonas/kubeclient/issues/278)
- http gem 2.x doesn't officially support ruby 2.4 [\#274](https://github.com/abonas/kubeclient/issues/274)
- Passing extra query params when deleting an entity? \(i.e. a deployment\) [\#266](https://github.com/abonas/kubeclient/issues/266)
- Only one resource class should exists: Kubeclient::Resource [\#198](https://github.com/abonas/kubeclient/issues/198)

**Merged pull requests:**

- Add ruby 2.5.0 to Travis test matrix [\#295](https://github.com/abonas/kubeclient/pull/295) ([cben](https://github.com/cben))
- Drop entity classes [\#292](https://github.com/abonas/kubeclient/pull/292) ([moolitayer](https://github.com/moolitayer))
- Update required ruby [\#291](https://github.com/abonas/kubeclient/pull/291) ([moolitayer](https://github.com/moolitayer))
- allow running tests with ruby test\_foo.rb [\#286](https://github.com/abonas/kubeclient/pull/286) ([grosser](https://github.com/grosser))
- implement as: :raw for watch [\#285](https://github.com/abonas/kubeclient/pull/285) ([grosser](https://github.com/grosser))
- Catch EBADF when watch\_stream fails [\#280](https://github.com/abonas/kubeclient/pull/280) ([zeari](https://github.com/zeari))
- Recurse over arrays for watch notices [\#279](https://github.com/abonas/kubeclient/pull/279) ([jhernand](https://github.com/jhernand))
- cascade delete entities with a delete\_option parameter. [\#267](https://github.com/abonas/kubeclient/pull/267) ([kamerblauwlicht](https://github.com/kamerblauwlicht))

## [v2.5.1](https://github.com/abonas/kubeclient/tree/v2.5.1) (2017-10-12)
[Full Changelog](https://github.com/abonas/kubeclient/compare/v2.5.0...v2.5.1)

## [v2.5.0](https://github.com/abonas/kubeclient/tree/v2.5.0) (2017-10-12)
[Full Changelog](https://github.com/abonas/kubeclient/compare/v2.4.0...v2.5.0)

**Closed issues:**

- Can't create a config map with nested properties. [\#265](https://github.com/abonas/kubeclient/issues/265)
- Specify rest-client version [\#264](https://github.com/abonas/kubeclient/issues/264)
- Cant pass authentication data to Client.new. [\#259](https://github.com/abonas/kubeclient/issues/259)
- Exception handling doesn't catch SSL errors [\#201](https://github.com/abonas/kubeclient/issues/201)

**Merged pull requests:**

- Bump version to 2.5.0 [\#272](https://github.com/abonas/kubeclient/pull/272) ([simon3z](https://github.com/simon3z))
- \[v2.x\] Adds raw option for client get requests [\#271](https://github.com/abonas/kubeclient/pull/271) ([simon3z](https://github.com/simon3z))
- Tell Rubocop to target Ruby 2.2 \(oldest we support\) [\#270](https://github.com/abonas/kubeclient/pull/270) ([cben](https://github.com/cben))
- Require rest-client 2.x, drop 1.x support code [\#269](https://github.com/abonas/kubeclient/pull/269) ([cben](https://github.com/cben))
- Adds raw option for client get requests [\#262](https://github.com/abonas/kubeclient/pull/262) ([NickLaMuro](https://github.com/NickLaMuro))
- Fixes warnings in test output \(and a potential bug\) [\#261](https://github.com/abonas/kubeclient/pull/261) ([NickLaMuro](https://github.com/NickLaMuro))
- Updated outdated dependencies [\#253](https://github.com/abonas/kubeclient/pull/253) ([Abdulwahaab710](https://github.com/Abdulwahaab710))

## [v2.4.0](https://github.com/abonas/kubeclient/tree/v2.4.0) (2017-05-10)
[Full Changelog](https://github.com/abonas/kubeclient/compare/v2.3.0...v2.4.0)

**Closed issues:**

- Upgrade webmock for ruby 2.4+ support [\#242](https://github.com/abonas/kubeclient/issues/242)
- pretty-printed json wastes bandwidth [\#239](https://github.com/abonas/kubeclient/issues/239)
- Automatically detect kind and apiVersion in Resources [\#235](https://github.com/abonas/kubeclient/issues/235)
- relax requirement on recursive-open-struct [\#230](https://github.com/abonas/kubeclient/issues/230)
- Include docker image in metadata [\#222](https://github.com/abonas/kubeclient/issues/222)
- HTTP library is out of date and causuing error when used with Ruby \>= 2.3.0 due to missing dependency  [\#220](https://github.com/abonas/kubeclient/issues/220)
- delete with label\_selector ? [\#217](https://github.com/abonas/kubeclient/issues/217)

**Merged pull requests:**

- \[v2.x\] Bump version to 2.4.0 [\#248](https://github.com/abonas/kubeclient/pull/248) ([simon3z](https://github.com/simon3z))
- Support ruby 2.4 [\#247](https://github.com/abonas/kubeclient/pull/247) ([cben](https://github.com/cben))
- \[v2.x\] Add requests timeouts option [\#246](https://github.com/abonas/kubeclient/pull/246) ([simon3z](https://github.com/simon3z))
- Add requests timeouts option [\#244](https://github.com/abonas/kubeclient/pull/244) ([cben](https://github.com/cben))
- adjust readme to rubocop [\#243](https://github.com/abonas/kubeclient/pull/243) ([grosser](https://github.com/grosser))
- bump rubocop to enforce what our style dictates [\#236](https://github.com/abonas/kubeclient/pull/236) ([grosser](https://github.com/grosser))
- Introduce Kubeclient::ResourceNotFoundError [\#233](https://github.com/abonas/kubeclient/pull/233) ([kirs](https://github.com/kirs))
- Fix Minitest deprecation [\#232](https://github.com/abonas/kubeclient/pull/232) ([kirs](https://github.com/kirs))
- relax requirement on recursive-open-struct [\#231](https://github.com/abonas/kubeclient/pull/231) ([jordimassaguerpla](https://github.com/jordimassaguerpla))
- Clarifying docs around process\_template [\#229](https://github.com/abonas/kubeclient/pull/229) ([salilgupta1](https://github.com/salilgupta1))
- raise KeyError as .fetch would do to behave more intuitive [\#228](https://github.com/abonas/kubeclient/pull/228) ([grosser](https://github.com/grosser))
- Remove limited entity list from Readme [\#225](https://github.com/abonas/kubeclient/pull/225) ([moolitayer](https://github.com/moolitayer))
- bump rubocop, fix offenses, use 2-space indent [\#223](https://github.com/abonas/kubeclient/pull/223) ([grosser](https://github.com/grosser))
- Include request info in exceptions to make it easy to see what reques… [\#221](https://github.com/abonas/kubeclient/pull/221) ([grosser](https://github.com/grosser))
- Code style: add parentheses around methods for test file [\#215](https://github.com/abonas/kubeclient/pull/215) ([jeremywadsack](https://github.com/jeremywadsack))
- make test output more readable by adding color [\#205](https://github.com/abonas/kubeclient/pull/205) ([grosser](https://github.com/grosser))
- bump http lib to remove circular dependencies [\#204](https://github.com/abonas/kubeclient/pull/204) ([grosser](https://github.com/grosser))
- move exception into Kubeclient namespace [\#195](https://github.com/abonas/kubeclient/pull/195) ([grosser](https://github.com/grosser))

## [v2.3.0](https://github.com/abonas/kubeclient/tree/v2.3.0) (2016-12-05)
[Full Changelog](https://github.com/abonas/kubeclient/compare/v2.2.0...v2.3.0)

**Merged pull requests:**

- Bump version to 2.3.0 [\#216](https://github.com/abonas/kubeclient/pull/216) ([zakiva](https://github.com/zakiva))
- Add backward compatibility for missing kind [\#214](https://github.com/abonas/kubeclient/pull/214) ([zakiva](https://github.com/zakiva))
- split up discovery for readability and stubbability [\#200](https://github.com/abonas/kubeclient/pull/200) ([grosser](https://github.com/grosser))

## [v2.2.0](https://github.com/abonas/kubeclient/tree/v2.2.0) (2016-11-15)
[Full Changelog](https://github.com/abonas/kubeclient/compare/v2.1.0...v2.2.0)

**Closed issues:**

- Post NetworkPolicy Annotations on Namespace [\#202](https://github.com/abonas/kubeclient/issues/202)
- Ingress support [\#176](https://github.com/abonas/kubeclient/issues/176)

**Merged pull requests:**

- Bump version to 2.2.0 [\#212](https://github.com/abonas/kubeclient/pull/212) ([zakiva](https://github.com/zakiva))
- Fix undefined method `rindex' [\#209](https://github.com/abonas/kubeclient/pull/209) ([zakiva](https://github.com/zakiva))
- Regenerate expired certificates for tests [\#207](https://github.com/abonas/kubeclient/pull/207) ([simon3z](https://github.com/simon3z))

## [v2.1.0](https://github.com/abonas/kubeclient/tree/v2.1.0) (2016-09-29)
[Full Changelog](https://github.com/abonas/kubeclient/compare/v2.0.0...v2.1.0)

**Merged pull requests:**

- Bump version to 2.1.0 [\#194](https://github.com/abonas/kubeclient/pull/194) ([simon3z](https://github.com/simon3z))
- Fix class extraction [\#193](https://github.com/abonas/kubeclient/pull/193) ([moolitayer](https://github.com/moolitayer))

## [v2.0.0](https://github.com/abonas/kubeclient/tree/v2.0.0) (2016-09-26)
[Full Changelog](https://github.com/abonas/kubeclient/compare/v1.2.0...v2.0.0)

**Fixed bugs:**

- activesupport requires Ruby version \>= 2.2.2 [\#182](https://github.com/abonas/kubeclient/issues/182)

**Closed issues:**

- jobs support [\#189](https://github.com/abonas/kubeclient/issues/189)
- Support new group API [\#144](https://github.com/abonas/kubeclient/issues/144)

**Merged pull requests:**

- Bump version to 2.0.0 [\#192](https://github.com/abonas/kubeclient/pull/192) ([simon3z](https://github.com/simon3z))
- Absolute paths for certs [\#191](https://github.com/abonas/kubeclient/pull/191) ([albertrdixon](https://github.com/albertrdixon))
- Do not update @headers on requests [\#190](https://github.com/abonas/kubeclient/pull/190) ([moolitayer](https://github.com/moolitayer))
- Added information about token [\#188](https://github.com/abonas/kubeclient/pull/188) ([Zhomart](https://github.com/Zhomart))
- Inline oneline block [\#186](https://github.com/abonas/kubeclient/pull/186) ([moolitayer](https://github.com/moolitayer))
- Support k8s api discovery and group api [\#185](https://github.com/abonas/kubeclient/pull/185) ([moolitayer](https://github.com/moolitayer))
- Drop the dependency on activesupport [\#184](https://github.com/abonas/kubeclient/pull/184) ([moolitayer](https://github.com/moolitayer))
- Add support for processing templates [\#183](https://github.com/abonas/kubeclient/pull/183) ([zakiva](https://github.com/zakiva))
- rudimentary Kubeclient::Config documentation [\#179](https://github.com/abonas/kubeclient/pull/179) ([quavmo](https://github.com/quavmo))

## [v1.2.0](https://github.com/abonas/kubeclient/tree/v1.2.0) (2016-06-23)
[Full Changelog](https://github.com/abonas/kubeclient/compare/v1.1.4...v1.2.0)

**Closed issues:**

- Config file reader doesn't read user auth options [\#173](https://github.com/abonas/kubeclient/issues/173)
- ueihkntjfbf [\#172](https://github.com/abonas/kubeclient/issues/172)

**Merged pull requests:**

- Bump version to 1.2.0 [\#178](https://github.com/abonas/kubeclient/pull/178) ([simon3z](https://github.com/simon3z))
- Fix rubocop failure on line too long [\#177](https://github.com/abonas/kubeclient/pull/177) ([abonas](https://github.com/abonas))
- Comma separates cert\_store example ssl\_options [\#175](https://github.com/abonas/kubeclient/pull/175) ([quavmo](https://github.com/quavmo))
- add support for reading tokens and user/pass from kubeconfig \[\#173\] [\#174](https://github.com/abonas/kubeclient/pull/174) ([jonmoter](https://github.com/jonmoter))
- adding proxy support [\#169](https://github.com/abonas/kubeclient/pull/169) ([enoodle](https://github.com/enoodle))

## [v1.1.4](https://github.com/abonas/kubeclient/tree/v1.1.4) (2016-05-28)
[Full Changelog](https://github.com/abonas/kubeclient/compare/v1.1.3...v1.1.4)

**Closed issues:**

- set selector not supported ? [\#168](https://github.com/abonas/kubeclient/issues/168)

**Merged pull requests:**

- Bump version to 1.1.4 [\#171](https://github.com/abonas/kubeclient/pull/171) ([simon3z](https://github.com/simon3z))
- parallelize rubocop and normal tests for speed and clarity on what broke [\#166](https://github.com/abonas/kubeclient/pull/166) ([grosser](https://github.com/grosser))
- lock down webmock to pass tests [\#165](https://github.com/abonas/kubeclient/pull/165) ([grosser](https://github.com/grosser))
- some cleanup [\#164](https://github.com/abonas/kubeclient/pull/164) ([grosser](https://github.com/grosser))
- config: add support to read kube config files [\#127](https://github.com/abonas/kubeclient/pull/127) ([simon3z](https://github.com/simon3z))

## [v1.1.3](https://github.com/abonas/kubeclient/tree/v1.1.3) (2016-04-04)
[Full Changelog](https://github.com/abonas/kubeclient/compare/v1.1.2...v1.1.3)

**Merged pull requests:**

- Bump version to 1.1.3 [\#162](https://github.com/abonas/kubeclient/pull/162) ([simon3z](https://github.com/simon3z))
- Add support for Patch method [\#161](https://github.com/abonas/kubeclient/pull/161) ([zakiva](https://github.com/zakiva))

## [v1.1.2](https://github.com/abonas/kubeclient/tree/v1.1.2) (2016-03-22)
[Full Changelog](https://github.com/abonas/kubeclient/compare/v0.8.1...v1.1.2)

**Closed issues:**

- kubeclient-1.1.1 doesn't support Kubernetes 1.2.0 [\#158](https://github.com/abonas/kubeclient/issues/158)

**Merged pull requests:**

- Bump version to 1.1.2 [\#159](https://github.com/abonas/kubeclient/pull/159) ([simon3z](https://github.com/simon3z))
- Remove json is part of the ruby stdlib now [\#154](https://github.com/abonas/kubeclient/pull/154) ([cored](https://github.com/cored))

## [v0.8.1](https://github.com/abonas/kubeclient/tree/v0.8.1) (2016-03-08)
[Full Changelog](https://github.com/abonas/kubeclient/compare/v1.1.1...v0.8.1)

**Merged pull requests:**

- Bump version to 0.8.1 [\#157](https://github.com/abonas/kubeclient/pull/157) ([simon3z](https://github.com/simon3z))
- Add content-type header = application/json for create and update actions [\#156](https://github.com/abonas/kubeclient/pull/156) ([simon3z](https://github.com/simon3z))
- Add content-type header = application/json for create and update actions [\#152](https://github.com/abonas/kubeclient/pull/152) ([abonas](https://github.com/abonas))

## [v1.1.1](https://github.com/abonas/kubeclient/tree/v1.1.1) (2016-02-24)
[Full Changelog](https://github.com/abonas/kubeclient/compare/v1.1.0...v1.1.1)

**Closed issues:**

- Use a non-blocking HTTP library [\#140](https://github.com/abonas/kubeclient/issues/140)
- Endpoints entity\_type is not plural [\#81](https://github.com/abonas/kubeclient/issues/81)

**Merged pull requests:**

- Fix \#81 kind of an endpoint in creation should be Endpoints [\#153](https://github.com/abonas/kubeclient/pull/153) ([abonas](https://github.com/abonas))
- fix usage of update service in tests [\#151](https://github.com/abonas/kubeclient/pull/151) ([abonas](https://github.com/abonas))
- Fix for nil ns\_prefix caused by upgrade to recursive-open-struct 1.0 [\#150](https://github.com/abonas/kubeclient/pull/150) ([bkoski](https://github.com/bkoski))

## [v1.1.0](https://github.com/abonas/kubeclient/tree/v1.1.0) (2016-01-17)
[Full Changelog](https://github.com/abonas/kubeclient/compare/v1.0.0...v1.1.0)

**Closed issues:**

- Current release \(0.9.0\) doesn't work on ruby 2.3.x [\#149](https://github.com/abonas/kubeclient/issues/149)

**Merged pull requests:**

- Use the non-blocking IO enabled http.rb instead of net/http in watchers [\#142](https://github.com/abonas/kubeclient/pull/142) ([msufa](https://github.com/msufa))

## [v1.0.0](https://github.com/abonas/kubeclient/tree/v1.0.0) (2016-01-05)
[Full Changelog](https://github.com/abonas/kubeclient/compare/v0.9.0...v1.0.0)

**Closed issues:**

- Add Ruby 2.3 to travis.yml matrix as soon as it's released [\#146](https://github.com/abonas/kubeclient/issues/146)
- FYI: Update recursive-open-struct once it supports ruby 2.3.0 [\#145](https://github.com/abonas/kubeclient/issues/145)
- Watcher crashes when WatchStream\#finish called during event processing [\#139](https://github.com/abonas/kubeclient/issues/139)

**Merged pull requests:**

- Add Ruby 2.3 to .travis.yml [\#148](https://github.com/abonas/kubeclient/pull/148) ([abonas](https://github.com/abonas))
- Fix \#145 bump ROS version to 1.0.0 [\#147](https://github.com/abonas/kubeclient/pull/147) ([abonas](https://github.com/abonas))
- Updated nits in readme [\#141](https://github.com/abonas/kubeclient/pull/141) ([abonas](https://github.com/abonas))

## [v0.9.0](https://github.com/abonas/kubeclient/tree/v0.9.0) (2015-10-27)
[Full Changelog](https://github.com/abonas/kubeclient/compare/v0.8.0...v0.9.0)

**Closed issues:**

- Allow watching events with a labelSelector [\#123](https://github.com/abonas/kubeclient/issues/123)
- Allow reading the log of a pod [\#119](https://github.com/abonas/kubeclient/issues/119)

**Merged pull requests:**

- add functionality for getting and watching logs of pods [\#136](https://github.com/abonas/kubeclient/pull/136) ([jonmoter](https://github.com/jonmoter))
- get or watch entities using fieldSelector or labelSelector [\#126](https://github.com/abonas/kubeclient/pull/126) ([jonmoter](https://github.com/jonmoter))
- common: add support for the ca cert\_store [\#125](https://github.com/abonas/kubeclient/pull/125) ([simon3z](https://github.com/simon3z))
- Add service account entity [\#124](https://github.com/abonas/kubeclient/pull/124) ([simon3z](https://github.com/simon3z))

## [v0.8.0](https://github.com/abonas/kubeclient/tree/v0.8.0) (2015-10-18)
[Full Changelog](https://github.com/abonas/kubeclient/compare/v0.7.0...v0.8.0)

**Merged pull requests:**

- fix revert add component statuses [\#138](https://github.com/abonas/kubeclient/pull/138) ([dkorn](https://github.com/dkorn))

## [v0.7.0](https://github.com/abonas/kubeclient/tree/v0.7.0) (2015-10-15)
[Full Changelog](https://github.com/abonas/kubeclient/compare/v0.6.0...v0.7.0)

**Closed issues:**

- Problem using create\_\* [\#128](https://github.com/abonas/kubeclient/issues/128)

**Merged pull requests:**

- Revert "Add Component statuses" [\#137](https://github.com/abonas/kubeclient/pull/137) ([abonas](https://github.com/abonas))
- Flex 404 exception msg check to work with more rest-client versions [\#135](https://github.com/abonas/kubeclient/pull/135) ([abonas](https://github.com/abonas))
- Add Ruby 2.2 to travis matrix [\#134](https://github.com/abonas/kubeclient/pull/134) ([abonas](https://github.com/abonas))
- fix \#128 creation example in the readme [\#133](https://github.com/abonas/kubeclient/pull/133) ([abonas](https://github.com/abonas))
- allow WatchStream to handle streams of data that are not JSON [\#132](https://github.com/abonas/kubeclient/pull/132) ([jonmoter](https://github.com/jonmoter))
- rename open\_test\_json\_file to open\_test\_file [\#131](https://github.com/abonas/kubeclient/pull/131) ([jonmoter](https://github.com/jonmoter))
- refactor the Net::HTTP options logic into its own helper method [\#130](https://github.com/abonas/kubeclient/pull/130) ([jonmoter](https://github.com/jonmoter))
- add response to KubeException [\#129](https://github.com/abonas/kubeclient/pull/129) ([jonmoter](https://github.com/jonmoter))
- Add Component statuses [\#108](https://github.com/abonas/kubeclient/pull/108) ([dkorn](https://github.com/dkorn))

## [v0.6.0](https://github.com/abonas/kubeclient/tree/v0.6.0) (2015-09-21)
[Full Changelog](https://github.com/abonas/kubeclient/compare/v0.5.1...v0.6.0)

**Closed issues:**

- Parse Kubernetes config file to create clients [\#122](https://github.com/abonas/kubeclient/issues/122)
- Move kubeclient default version to kubernetes v1 [\#101](https://github.com/abonas/kubeclient/issues/101)

**Merged pull requests:**

- update default version of API to v1 instead of v1beta3 \[\#101\] [\#120](https://github.com/abonas/kubeclient/pull/120) ([jonmoter](https://github.com/jonmoter))
- check for missing item list returned due to k8b bug\[1\] [\#118](https://github.com/abonas/kubeclient/pull/118) ([moolitayer](https://github.com/moolitayer))
- move code that can be shared between clients to common [\#114](https://github.com/abonas/kubeclient/pull/114) ([moolitayer](https://github.com/moolitayer))
- Add k8s guestbook tests and get\_entities by namespace [\#105](https://github.com/abonas/kubeclient/pull/105) ([abonas](https://github.com/abonas))

## [v0.5.1](https://github.com/abonas/kubeclient/tree/v0.5.1) (2015-08-27)
[Full Changelog](https://github.com/abonas/kubeclient/compare/v0.5.0...v0.5.1)

## [v0.5.0](https://github.com/abonas/kubeclient/tree/v0.5.0) (2015-08-27)
[Full Changelog](https://github.com/abonas/kubeclient/compare/v0.4.0...v0.5.0)

**Merged pull requests:**

- proxy url: expect singular entity names & port changes [\#116](https://github.com/abonas/kubeclient/pull/116) ([moolitayer](https://github.com/moolitayer))
- Add proxy URL [\#115](https://github.com/abonas/kubeclient/pull/115) ([oschreib](https://github.com/oschreib))
- Add persistent volumes and persistent volume claims [\#113](https://github.com/abonas/kubeclient/pull/113) ([zakiva](https://github.com/zakiva))
- client: add compatibility with more\_core\_extensions [\#110](https://github.com/abonas/kubeclient/pull/110) ([simon3z](https://github.com/simon3z))

## [v0.4.0](https://github.com/abonas/kubeclient/tree/v0.4.0) (2015-08-23)
[Full Changelog](https://github.com/abonas/kubeclient/compare/v0.3.0...v0.4.0)

**Merged pull requests:**

- move validate\_auth\_options to common so it can be shared. [\#109](https://github.com/abonas/kubeclient/pull/109) ([moolitayer](https://github.com/moolitayer))
- Add resource quotas and limit ranges. [\#106](https://github.com/abonas/kubeclient/pull/106) ([moolitayer](https://github.com/moolitayer))
- increase max line length from 80 to 100 [\#104](https://github.com/abonas/kubeclient/pull/104) ([abonas](https://github.com/abonas))

## [v0.3.0](https://github.com/abonas/kubeclient/tree/v0.3.0) (2015-07-28)
[Full Changelog](https://github.com/abonas/kubeclient/compare/v0.2.0...v0.3.0)

**Closed issues:**

- Support Scaling ReplicationControllers [\#103](https://github.com/abonas/kubeclient/issues/103)
- gem release with changes from commit \#91 ? [\#99](https://github.com/abonas/kubeclient/issues/99)

**Merged pull requests:**

- Add Secrets [\#102](https://github.com/abonas/kubeclient/pull/102) ([iterion](https://github.com/iterion))

## [v0.2.0](https://github.com/abonas/kubeclient/tree/v0.2.0) (2015-07-14)
[Full Changelog](https://github.com/abonas/kubeclient/compare/v0.1.17...v0.2.0)

**Merged pull requests:**

- Allow bearer token file for auth [\#98](https://github.com/abonas/kubeclient/pull/98) ([jimmidyson](https://github.com/jimmidyson))
- Bugfix: update of a entity not working as the name is not read correctly [\#97](https://github.com/abonas/kubeclient/pull/97) ([simonswine](https://github.com/simonswine))
- Fixes \#93: Remove old API versions, add v1 [\#94](https://github.com/abonas/kubeclient/pull/94) ([jimmidyson](https://github.com/jimmidyson))
- Fixes \#91: Move SSL options, basic auth & bearer token to constructor [\#92](https://github.com/abonas/kubeclient/pull/92) ([jimmidyson](https://github.com/jimmidyson))

## [v0.1.17](https://github.com/abonas/kubeclient/tree/v0.1.17) (2015-06-07)
[Full Changelog](https://github.com/abonas/kubeclient/compare/v0.1.16...v0.1.17)

**Closed issues:**

- Drop API versions v1beta1/2 & add v1  [\#93](https://github.com/abonas/kubeclient/issues/93)
- Move ssl\_options & auth options into constructor [\#91](https://github.com/abonas/kubeclient/issues/91)
- Use service account token if available [\#90](https://github.com/abonas/kubeclient/issues/90)
- Using Bearer token impacts any RestClient instance [\#84](https://github.com/abonas/kubeclient/issues/84)

**Merged pull requests:**

- Update KubeException to inherit StandardError [\#95](https://github.com/abonas/kubeclient/pull/95) ([oschreib](https://github.com/oschreib))
- Send bearer token only on relevant instance [\#89](https://github.com/abonas/kubeclient/pull/89) ([oschreib](https://github.com/oschreib))
- update readme, fix section names [\#88](https://github.com/abonas/kubeclient/pull/88) ([abonas](https://github.com/abonas))

## [v0.1.16](https://github.com/abonas/kubeclient/tree/v0.1.16) (2015-05-19)
[Full Changelog](https://github.com/abonas/kubeclient/compare/v0.1.15...v0.1.16)

**Merged pull requests:**

- add assert\_requested to basic\_auth tests [\#87](https://github.com/abonas/kubeclient/pull/87) ([abonas](https://github.com/abonas))
- readme fix for basic\_auth documentation and example [\#86](https://github.com/abonas/kubeclient/pull/86) ([abonas](https://github.com/abonas))
- Add HTTP basic authentication support [\#83](https://github.com/abonas/kubeclient/pull/83) ([oschreib](https://github.com/oschreib))

## [v0.1.15](https://github.com/abonas/kubeclient/tree/v0.1.15) (2015-05-14)
[Full Changelog](https://github.com/abonas/kubeclient/compare/v0.1.14...v0.1.15)

**Closed issues:**

- Support bearer tokens for authentication ready for service accounts [\#79](https://github.com/abonas/kubeclient/issues/79)
- Wrong options for watch & SSL [\#77](https://github.com/abonas/kubeclient/issues/77)

**Merged pull requests:**

- Update readme [\#82](https://github.com/abonas/kubeclient/pull/82) ([jimmidyson](https://github.com/jimmidyson))
- Fixes \#79: Bearer token support [\#80](https://github.com/abonas/kubeclient/pull/80) ([jimmidyson](https://github.com/jimmidyson))
- Fixes \#77: Use cert & key for SSL opts as detailed at http://apidock.com/ruby/v1\_9\_3\_392/Net/HTTP/start/class\#docs\_body [\#78](https://github.com/abonas/kubeclient/pull/78) ([jimmidyson](https://github.com/jimmidyson))

## [v0.1.14](https://github.com/abonas/kubeclient/tree/v0.1.14) (2015-05-11)
[Full Changelog](https://github.com/abonas/kubeclient/compare/v0.1.13...v0.1.14)

**Merged pull requests:**

- move api valid checks to common [\#76](https://github.com/abonas/kubeclient/pull/76) ([abonas](https://github.com/abonas))
- client: improve api\_valid check with version [\#75](https://github.com/abonas/kubeclient/pull/75) ([simon3z](https://github.com/simon3z))

## [v0.1.13](https://github.com/abonas/kubeclient/tree/v0.1.13) (2015-05-05)
[Full Changelog](https://github.com/abonas/kubeclient/compare/v0.1.12...v0.1.13)

**Closed issues:**

- DELETE on v1beta3 must include namespace in the url  [\#61](https://github.com/abonas/kubeclient/issues/61)

**Merged pull requests:**

- Add assertRequest checks to tests [\#74](https://github.com/abonas/kubeclient/pull/74) ([abonas](https://github.com/abonas))
- Fix \#61 add namespace to url when delete an entity \(except node, namespa... [\#73](https://github.com/abonas/kubeclient/pull/73) ([abonas](https://github.com/abonas))
- remove camelized resource names [\#72](https://github.com/abonas/kubeclient/pull/72) ([abonas](https://github.com/abonas))

## [v0.1.12](https://github.com/abonas/kubeclient/tree/v0.1.12) (2015-04-28)
[Full Changelog](https://github.com/abonas/kubeclient/compare/v0.1.11...v0.1.12)

**Closed issues:**

- GET a single entity must include namespace in the url [\#51](https://github.com/abonas/kubeclient/issues/51)
- POST on v1beta3 must include namespace in the url [\#36](https://github.com/abonas/kubeclient/issues/36)

**Merged pull requests:**

- fix label param documentation in readme [\#71](https://github.com/abonas/kubeclient/pull/71) ([abonas](https://github.com/abonas))
- fix \#51 add namespace to url of GET single entity calls [\#70](https://github.com/abonas/kubeclient/pull/70) ([abonas](https://github.com/abonas))
- Fixed name of label selector parameter [\#69](https://github.com/abonas/kubeclient/pull/69) ([stephenjlevy](https://github.com/stephenjlevy))
- Fix SSL support for api validation [\#68](https://github.com/abonas/kubeclient/pull/68) ([simon3z](https://github.com/simon3z))
- Fix \#36 - add namespace to creation and update urls [\#67](https://github.com/abonas/kubeclient/pull/67) ([abonas](https://github.com/abonas))

## [v0.1.11](https://github.com/abonas/kubeclient/tree/v0.1.11) (2015-04-08)
[Full Changelog](https://github.com/abonas/kubeclient/compare/v0.1.10...v0.1.11)

**Merged pull requests:**

- bumpver0.1.11 [\#66](https://github.com/abonas/kubeclient/pull/66) ([abonas](https://github.com/abonas))
- limit recursive open struct version [\#65](https://github.com/abonas/kubeclient/pull/65) ([abonas](https://github.com/abonas))
- Added automatic inclusion of object kind and api version for create requ... [\#58](https://github.com/abonas/kubeclient/pull/58) ([stephenjlevy](https://github.com/stephenjlevy))

## [v0.1.10](https://github.com/abonas/kubeclient/tree/v0.1.10) (2015-04-07)
[Full Changelog](https://github.com/abonas/kubeclient/compare/v0.1.9...v0.1.10)

**Merged pull requests:**

- watches: ruby http client uses verify\_mode [\#64](https://github.com/abonas/kubeclient/pull/64) ([simon3z](https://github.com/simon3z))
- limit rubocop version [\#63](https://github.com/abonas/kubeclient/pull/63) ([abonas](https://github.com/abonas))
- fix new rubocop 0.30 offenses [\#62](https://github.com/abonas/kubeclient/pull/62) ([abonas](https://github.com/abonas))
- change service tests to multi ports [\#60](https://github.com/abonas/kubeclient/pull/60) ([abonas](https://github.com/abonas))
- rename id to name due to rename in k8s [\#59](https://github.com/abonas/kubeclient/pull/59) ([abonas](https://github.com/abonas))

## [v0.1.9](https://github.com/abonas/kubeclient/tree/v0.1.9) (2015-04-01)
[Full Changelog](https://github.com/abonas/kubeclient/compare/v0.1.8...v0.1.9)

**Merged pull requests:**

- fix version example in readme [\#57](https://github.com/abonas/kubeclient/pull/57) ([abonas](https://github.com/abonas))
- Adding a common client module and class. [\#56](https://github.com/abonas/kubeclient/pull/56) ([abonas](https://github.com/abonas))
- fix method name in readme [\#55](https://github.com/abonas/kubeclient/pull/55) ([abonas](https://github.com/abonas))

## [v0.1.8](https://github.com/abonas/kubeclient/tree/v0.1.8) (2015-03-26)
[Full Changelog](https://github.com/abonas/kubeclient/compare/v0.1.7...v0.1.8)

**Closed issues:**

- Labels need to be renamed to label-selector [\#44](https://github.com/abonas/kubeclient/issues/44)
- Add a "connection check" method on api root [\#40](https://github.com/abonas/kubeclient/issues/40)
- Add defaults when kubeclient is initialized [\#38](https://github.com/abonas/kubeclient/issues/38)
- 757: unexpected token at '404: Page Not Found' happens when having a 404 error  [\#35](https://github.com/abonas/kubeclient/issues/35)

**Merged pull requests:**

- Add Kubeclient\#api\_valid? [\#54](https://github.com/abonas/kubeclient/pull/54) ([Fryguy](https://github.com/Fryguy))
- rename exception method [\#53](https://github.com/abonas/kubeclient/pull/53) ([abonas](https://github.com/abonas))
- refactor to keep version separate from uri [\#52](https://github.com/abonas/kubeclient/pull/52) ([abonas](https://github.com/abonas))
- refactor rest\_client method [\#50](https://github.com/abonas/kubeclient/pull/50) ([abonas](https://github.com/abonas))
- remove v1beta1 mention leftovers [\#49](https://github.com/abonas/kubeclient/pull/49) ([abonas](https://github.com/abonas))
- Fix travis badge to show master status [\#48](https://github.com/abonas/kubeclient/pull/48) ([abonas](https://github.com/abonas))
- Add method to retrieve the api versions from server [\#47](https://github.com/abonas/kubeclient/pull/47) ([abonas](https://github.com/abonas))
- Fix \#44 rename label param field [\#46](https://github.com/abonas/kubeclient/pull/46) ([abonas](https://github.com/abonas))
- Remove support of v1beta1 [\#45](https://github.com/abonas/kubeclient/pull/45) ([abonas](https://github.com/abonas))
- Fix \#35 Handle exceptions with non jsonized message [\#43](https://github.com/abonas/kubeclient/pull/43) ([abonas](https://github.com/abonas))
- Fix \#38 add default path and version [\#42](https://github.com/abonas/kubeclient/pull/42) ([abonas](https://github.com/abonas))
- fix Rubocop issue introduced in pr 39 [\#41](https://github.com/abonas/kubeclient/pull/41) ([abonas](https://github.com/abonas))
- move dynamically defined classes under `Kubeclient` [\#39](https://github.com/abonas/kubeclient/pull/39) ([tenderlove](https://github.com/tenderlove))
- switch EntityList from an Array subclass to a delegate [\#37](https://github.com/abonas/kubeclient/pull/37) ([tenderlove](https://github.com/tenderlove))

## [v0.1.7](https://github.com/abonas/kubeclient/tree/v0.1.7) (2015-03-10)
[Full Changelog](https://github.com/abonas/kubeclient/compare/v0.1.6...v0.1.7)

**Merged pull requests:**

- add test for empty items list [\#34](https://github.com/abonas/kubeclient/pull/34) ([abonas](https://github.com/abonas))
- add test helper [\#32](https://github.com/abonas/kubeclient/pull/32) ([abonas](https://github.com/abonas))
- add minimal support for labels [\#26](https://github.com/abonas/kubeclient/pull/26) ([kazegusuri](https://github.com/kazegusuri))

## [v0.1.6](https://github.com/abonas/kubeclient/tree/v0.1.6) (2015-03-05)
[Full Changelog](https://github.com/abonas/kubeclient/compare/v0.1.5...v0.1.6)

**Merged pull requests:**

- lib: renaming watch to watch\_notice for consistency [\#31](https://github.com/abonas/kubeclient/pull/31) ([simon3z](https://github.com/simon3z))
- define entity class definitions dynamically [\#29](https://github.com/abonas/kubeclient/pull/29) ([abonas](https://github.com/abonas))

## [v0.1.5](https://github.com/abonas/kubeclient/tree/v0.1.5) (2015-03-04)
[Full Changelog](https://github.com/abonas/kubeclient/compare/v0.1.4...v0.1.5)

**Merged pull requests:**

- update readme [\#28](https://github.com/abonas/kubeclient/pull/28) ([abonas](https://github.com/abonas))
- add support for namespace entity [\#27](https://github.com/abonas/kubeclient/pull/27) ([abonas](https://github.com/abonas))
- Extract dynamically defined method content to real methods [\#15](https://github.com/abonas/kubeclient/pull/15) ([Fryguy](https://github.com/Fryguy))

## [v0.1.4](https://github.com/abonas/kubeclient/tree/v0.1.4) (2015-02-19)
[Full Changelog](https://github.com/abonas/kubeclient/compare/v0.1.3...v0.1.4)

**Merged pull requests:**

- release: kubeclient-0.1.4 [\#25](https://github.com/abonas/kubeclient/pull/25) ([simon3z](https://github.com/simon3z))
- client: prevent watches read\_timeout on inactivity [\#24](https://github.com/abonas/kubeclient/pull/24) ([simon3z](https://github.com/simon3z))
- client: add support for ssl connections [\#23](https://github.com/abonas/kubeclient/pull/23) ([simon3z](https://github.com/simon3z))
- client: support URI objects as api\_endpoint [\#22](https://github.com/abonas/kubeclient/pull/22) ([simon3z](https://github.com/simon3z))
- Add support to stop watching entities [\#21](https://github.com/abonas/kubeclient/pull/21) ([simon3z](https://github.com/simon3z))
- client: add support for kubernetes endpoints [\#16](https://github.com/abonas/kubeclient/pull/16) ([simon3z](https://github.com/simon3z))
- build: add travis continuous integration support [\#13](https://github.com/abonas/kubeclient/pull/13) ([simon3z](https://github.com/simon3z))

## [v0.1.3](https://github.com/abonas/kubeclient/tree/v0.1.3) (2015-02-15)
[Full Changelog](https://github.com/abonas/kubeclient/compare/v0.1.2...v0.1.3)

## [v0.1.2](https://github.com/abonas/kubeclient/tree/v0.1.2) (2015-02-15)
[Full Changelog](https://github.com/abonas/kubeclient/compare/v0.1.1...v0.1.2)

**Merged pull requests:**

- limit ruby version to 2 and up, increase gem version [\#14](https://github.com/abonas/kubeclient/pull/14) ([abonas](https://github.com/abonas))
- DRY up exception handling [\#12](https://github.com/abonas/kubeclient/pull/12) ([Fryguy](https://github.com/Fryguy))
- Add Travis support and badges [\#11](https://github.com/abonas/kubeclient/pull/11) ([Fryguy](https://github.com/Fryguy))
- client: autodetect entity list resourceVersion [\#10](https://github.com/abonas/kubeclient/pull/10) ([simon3z](https://github.com/simon3z))
- rake: add rubocop execution target [\#9](https://github.com/abonas/kubeclient/pull/9) ([simon3z](https://github.com/simon3z))
- Fix rubocop offenses [\#8](https://github.com/abonas/kubeclient/pull/8) ([simon3z](https://github.com/simon3z))
- Test fixes [\#7](https://github.com/abonas/kubeclient/pull/7) ([simon3z](https://github.com/simon3z))
- client: add event kubernetes entity [\#6](https://github.com/abonas/kubeclient/pull/6) ([simon3z](https://github.com/simon3z))
- add support for watching entities [\#5](https://github.com/abonas/kubeclient/pull/5) ([simon3z](https://github.com/simon3z))
- switch to functional style iteration [\#4](https://github.com/abonas/kubeclient/pull/4) ([tenderlove](https://github.com/tenderlove))
- remove explicit local variable assignment [\#3](https://github.com/abonas/kubeclient/pull/3) ([tenderlove](https://github.com/tenderlove))

## [v0.1.1](https://github.com/abonas/kubeclient/tree/v0.1.1) (2015-01-22)
[Full Changelog](https://github.com/abonas/kubeclient/compare/v0.1.0...v0.1.1)

## [v0.1.0](https://github.com/abonas/kubeclient/tree/v0.1.0) (2015-01-22)
[Full Changelog](https://github.com/abonas/kubeclient/compare/v0.0.9...v0.1.0)

## [v0.0.9](https://github.com/abonas/kubeclient/tree/v0.0.9) (2015-01-22)
[Full Changelog](https://github.com/abonas/kubeclient/compare/v0.0.8...v0.0.9)

## [v0.0.8](https://github.com/abonas/kubeclient/tree/v0.0.8) (2015-01-22)
[Full Changelog](https://github.com/abonas/kubeclient/compare/v0.0.7...v0.0.8)

## [v0.0.7](https://github.com/abonas/kubeclient/tree/v0.0.7) (2015-01-22)
[Full Changelog](https://github.com/abonas/kubeclient/compare/v0.0.6...v0.0.7)

**Merged pull requests:**

- use `send` instead of getting the method and calling it [\#2](https://github.com/abonas/kubeclient/pull/2) ([tenderlove](https://github.com/tenderlove))
- fix method visibility [\#1](https://github.com/abonas/kubeclient/pull/1) ([tenderlove](https://github.com/tenderlove))

## [v0.0.6](https://github.com/abonas/kubeclient/tree/v0.0.6) (2015-01-13)
[Full Changelog](https://github.com/abonas/kubeclient/compare/v0.0.5...v0.0.6)

## [v0.0.5](https://github.com/abonas/kubeclient/tree/v0.0.5) (2015-01-08)


\* *This Change Log was automatically generated by [github_changelog_generator](https://github.com/skywinder/Github-Changelog-Generator)*