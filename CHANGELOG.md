# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [0.4.2](https://github.com/PaoloLaurenti/rabbitmq-stream-rust-client/compare/rabbitmq-stream-client-v0.4.1...rabbitmq-stream-client-v0.4.2) - 2023-12-26

### Added
- add workflow for release-plz ([#200](https://github.com/PaoloLaurenti/rabbitmq-stream-rust-client/pull/200))
- *(tests)* adds test with invalid virtual host ([#172](https://github.com/PaoloLaurenti/rabbitmq-stream-rust-client/pull/172))

### Fixed
- fix [#186](https://github.com/PaoloLaurenti/rabbitmq-stream-rust-client/pull/186) ([#189](https://github.com/PaoloLaurenti/rabbitmq-stream-rust-client/pull/189))
- restore coverage ([#169](https://github.com/PaoloLaurenti/rabbitmq-stream-rust-client/pull/169))
- *(tests)* fixes tests on environment with wrong credentials ([#168](https://github.com/PaoloLaurenti/rabbitmq-stream-rust-client/pull/168))
- fixes [#160](https://github.com/PaoloLaurenti/rabbitmq-stream-rust-client/pull/160) ([#161](https://github.com/PaoloLaurenti/rabbitmq-stream-rust-client/pull/161))
- Create new thread_rng rather than using cache ([#131](https://github.com/PaoloLaurenti/rabbitmq-stream-rust-client/pull/131))

### Other
- release ([#201](https://github.com/PaoloLaurenti/rabbitmq-stream-rust-client/pull/201))
- expose store_offset and query_offset in consumer ([#203](https://github.com/PaoloLaurenti/rabbitmq-stream-rust-client/pull/203))
- release-plz config
- Update ordered-float requirement from 3.0.0 to 4.1.0 ([#199](https://github.com/PaoloLaurenti/rabbitmq-stream-rust-client/pull/199))
- Bump docker/build-push-action from 4 to 5 ([#198](https://github.com/PaoloLaurenti/rabbitmq-stream-rust-client/pull/198))
- Bump actions/checkout from 3 to 4 ([#196](https://github.com/PaoloLaurenti/rabbitmq-stream-rust-client/pull/196))
- Bump docker/setup-buildx-action from 2 to 3 ([#197](https://github.com/PaoloLaurenti/rabbitmq-stream-rust-client/pull/197))
- update to 0.4.0
- update to 0.4.0
- Update README.md [skip ci]
- Update README.md
- Tls client certificate ([#191](https://github.com/PaoloLaurenti/rabbitmq-stream-rust-client/pull/191))
- Enable RabbitMQ TlS in github action ([#192](https://github.com/PaoloLaurenti/rabbitmq-stream-rust-client/pull/192))
- Bump actions/checkout from 2 to 4 ([#193](https://github.com/PaoloLaurenti/rabbitmq-stream-rust-client/pull/193))
- Add dependabot for github actions.
- Update num_enum requirement from 0.6.1 to 0.7.0 ([#190](https://github.com/PaoloLaurenti/rabbitmq-stream-rust-client/pull/190))
- bumped protocol to 0.3.0
- bumping version before release ([#184](https://github.com/PaoloLaurenti/rabbitmq-stream-rust-client/pull/184))
- tls support improvements, added trust to hostname and ca certificate ([#182](https://github.com/PaoloLaurenti/rabbitmq-stream-rust-client/pull/182))
- add close connections ([#181](https://github.com/PaoloLaurenti/rabbitmq-stream-rust-client/pull/181))
- update dependecies
- Add some test ([#178](https://github.com/PaoloLaurenti/rabbitmq-stream-rust-client/pull/178))
- add tests for producer ([#177](https://github.com/PaoloLaurenti/rabbitmq-stream-rust-client/pull/177))
- Test error conditions ([#175](https://github.com/PaoloLaurenti/rabbitmq-stream-rust-client/pull/175))
- Fix annotation get ([#174](https://github.com/PaoloLaurenti/rabbitmq-stream-rust-client/pull/174))
- bump to 0.2.0 ([#173](https://github.com/PaoloLaurenti/rabbitmq-stream-rust-client/pull/173))
- Add more tests for the Environment ([#171](https://github.com/PaoloLaurenti/rabbitmq-stream-rust-client/pull/171))
- Initial environment tests ([#167](https://github.com/PaoloLaurenti/rabbitmq-stream-rust-client/pull/167))
- Implements [#95](https://github.com/PaoloLaurenti/rabbitmq-stream-rust-client/pull/95) and fixes [#162](https://github.com/PaoloLaurenti/rabbitmq-stream-rust-client/pull/162) ([#163](https://github.com/PaoloLaurenti/rabbitmq-stream-rust-client/pull/163))
- tls_first_implementation ([#155](https://github.com/PaoloLaurenti/rabbitmq-stream-rust-client/pull/155))
- allows clippy::uninlined_format_args
- temporary disable coverage
- clippy fix
- replaces timestamp_millis with timestamp_millis_opt
- Update clap requirement from 3.0.0-rc.5 to 4.0.22 ([#150](https://github.com/PaoloLaurenti/rabbitmq-stream-rust-client/pull/150))
- *(CI)* fix CI on PRs ([#152](https://github.com/PaoloLaurenti/rabbitmq-stream-rust-client/pull/152))
- Replace local ThreadRng with Environment's rng (StdRng) ([#140](https://github.com/PaoloLaurenti/rabbitmq-stream-rust-client/pull/140))
- Implement some clippy pedantic recommendations. ([#134](https://github.com/PaoloLaurenti/rabbitmq-stream-rust-client/pull/134))
- Publish to crates.io on tag. ([#133](https://github.com/PaoloLaurenti/rabbitmq-stream-rust-client/pull/133))
- Fix cargo clippy linter warnings. ([#132](https://github.com/PaoloLaurenti/rabbitmq-stream-rust-client/pull/132))
- update uuid dep to version 1
- clippy fix
- Disable codeconv
- Update ordered-float requirement from 2.10.0 to 3.0.0 ([#123](https://github.com/PaoloLaurenti/rabbitmq-stream-rust-client/pull/123))
- Update tokio-util requirement from 0.6.7 to 0.7.3 ([#128](https://github.com/PaoloLaurenti/rabbitmq-stream-rust-client/pull/128))
- Update dashmap requirement from 4.0.2 to 5.3.4 ([#127](https://github.com/PaoloLaurenti/rabbitmq-stream-rust-client/pull/127))
- updated metadata
- AMQP 1.0 message format ([#120](https://github.com/PaoloLaurenti/rabbitmq-stream-rust-client/pull/120))
- Add .tarpaulin.toml file ([#113](https://github.com/PaoloLaurenti/rabbitmq-stream-rust-client/pull/113))
- Add tarpaulin ([#112](https://github.com/PaoloLaurenti/rabbitmq-stream-rust-client/pull/112))
- Message in ConfirmStatus ([#109](https://github.com/PaoloLaurenti/rabbitmq-stream-rust-client/pull/109))
- change repo ref
- Implement publish batching ([#104](https://github.com/PaoloLaurenti/rabbitmq-stream-rust-client/pull/104))
- Change repo link
- add cluster support ([#100](https://github.com/PaoloLaurenti/rabbitmq-stream-rust-client/pull/100))
- Update tracing-subscriber requirement from 0.2.0 to 0.3.1 ([#102](https://github.com/PaoloLaurenti/rabbitmq-stream-rust-client/pull/102))
- started handling close and errors ([#93](https://github.com/PaoloLaurenti/rabbitmq-stream-rust-client/pull/93))
- Add license, code-of-conduct, and notice files. ([#92](https://github.com/PaoloLaurenti/rabbitmq-stream-rust-client/pull/92))
- Add dependabot config to update dependencies automatically. ([#88](https://github.com/PaoloLaurenti/rabbitmq-stream-rust-client/pull/88))
- Correct master to main in github actions config. ([#89](https://github.com/PaoloLaurenti/rabbitmq-stream-rust-client/pull/89))
- Added query publisher if producer reference is used ([#86](https://github.com/PaoloLaurenti/rabbitmq-stream-rust-client/pull/86))
- Update Cargo.toml
- Update README.md
- Add consumer  ([#83](https://github.com/PaoloLaurenti/rabbitmq-stream-rust-client/pull/83))
- module refactor
- Add producer ([#82](https://github.com/PaoloLaurenti/rabbitmq-stream-rust-client/pull/82))
- add Environment API ([#81](https://github.com/PaoloLaurenti/rabbitmq-stream-rust-client/pull/81))
- add client publish ([#80](https://github.com/PaoloLaurenti/rabbitmq-stream-rust-client/pull/80))
- add codec ([#76](https://github.com/PaoloLaurenti/rabbitmq-stream-rust-client/pull/76))
- Client declare delete publisher ([#79](https://github.com/PaoloLaurenti/rabbitmq-stream-rust-client/pull/79))
- Client store offset ([#78](https://github.com/PaoloLaurenti/rabbitmq-stream-rust-client/pull/78))
- Client unsubscribe ([#77](https://github.com/PaoloLaurenti/rabbitmq-stream-rust-client/pull/77))
- add metadata API on Client ([#75](https://github.com/PaoloLaurenti/rabbitmq-stream-rust-client/pull/75))
- Request response kind ([#65](https://github.com/PaoloLaurenti/rabbitmq-stream-rust-client/pull/65))
- Add create/delete APIs ([#63](https://github.com/PaoloLaurenti/rabbitmq-stream-rust-client/pull/63))
- Add close command/command response ([#55](https://github.com/PaoloLaurenti/rabbitmq-stream-rust-client/pull/55))
- Add query publisher sequence command request/response ([#56](https://github.com/PaoloLaurenti/rabbitmq-stream-rust-client/pull/56))
- Add publishing error command ([#61](https://github.com/PaoloLaurenti/rabbitmq-stream-rust-client/pull/61))
- Add publish confirm command ([#57](https://github.com/PaoloLaurenti/rabbitmq-stream-rust-client/pull/57))
- Client subscribe ([#58](https://github.com/PaoloLaurenti/rabbitmq-stream-rust-client/pull/58))
- Add metadata ([#53](https://github.com/PaoloLaurenti/rabbitmq-stream-rust-client/pull/53))
- Add metadata_update ([#54](https://github.com/PaoloLaurenti/rabbitmq-stream-rust-client/pull/54))
- Add publish ([#59](https://github.com/PaoloLaurenti/rabbitmq-stream-rust-client/pull/59))
- Add heartbeat ([#52](https://github.com/PaoloLaurenti/rabbitmq-stream-rust-client/pull/52))
- Add Credit ([#51](https://github.com/PaoloLaurenti/rabbitmq-stream-rust-client/pull/51))
- Add unsubscribe ([#48](https://github.com/PaoloLaurenti/rabbitmq-stream-rust-client/pull/48))
- Add subscribe ([#47](https://github.com/PaoloLaurenti/rabbitmq-stream-rust-client/pull/47))
- Add Deliver ([#49](https://github.com/PaoloLaurenti/rabbitmq-stream-rust-client/pull/49))
- Network layer experimental ([#40](https://github.com/PaoloLaurenti/rabbitmq-stream-rust-client/pull/40))
- Query offset bis ([#44](https://github.com/PaoloLaurenti/rabbitmq-stream-rust-client/pull/44))
- Add delete publisher ([#43](https://github.com/PaoloLaurenti/rabbitmq-stream-rust-client/pull/43))
- Add declare publisher ([#41](https://github.com/PaoloLaurenti/rabbitmq-stream-rust-client/pull/41))
- Store offset ([#39](https://github.com/PaoloLaurenti/rabbitmq-stream-rust-client/pull/39))
- test refactor + more Encoder/Decoder types ([#38](https://github.com/PaoloLaurenti/rabbitmq-stream-rust-client/pull/38))
- Add command tune ([#36](https://github.com/PaoloLaurenti/rabbitmq-stream-rust-client/pull/36))
- SaslAuthenticate   ([#33](https://github.com/PaoloLaurenti/rabbitmq-stream-rust-client/pull/33))
- Add delete ([#19](https://github.com/PaoloLaurenti/rabbitmq-stream-rust-client/pull/19)) ([#35](https://github.com/PaoloLaurenti/rabbitmq-stream-rust-client/pull/35))
- Add sasl_handshake ([#34](https://github.com/PaoloLaurenti/rabbitmq-stream-rust-client/pull/34))
- Add peer properties  ([#7](https://github.com/PaoloLaurenti/rabbitmq-stream-rust-client/pull/7))
- First commands  ([#4](https://github.com/PaoloLaurenti/rabbitmq-stream-rust-client/pull/4))
- Add commands and response constants ([#3](https://github.com/PaoloLaurenti/rabbitmq-stream-rust-client/pull/3))
- Add Make file ([#2](https://github.com/PaoloLaurenti/rabbitmq-stream-rust-client/pull/2))
- base structure ([#1](https://github.com/PaoloLaurenti/rabbitmq-stream-rust-client/pull/1))
- first commit

## [0.4.1](https://github.com/rabbitmq/rabbitmq-stream-rust-client/compare/rabbitmq-stream-client-v0.4.0...rabbitmq-stream-client-v0.4.1) - 2023-10-25

### Added
- add workflow for release-plz ([#200](https://github.com/rabbitmq/rabbitmq-stream-rust-client/pull/200))

### Other
- expose store_offset and query_offset in consumer ([#203](https://github.com/rabbitmq/rabbitmq-stream-rust-client/pull/203))
- release-plz config
- Update ordered-float requirement from 3.0.0 to 4.1.0 ([#199](https://github.com/rabbitmq/rabbitmq-stream-rust-client/pull/199))
- Bump docker/build-push-action from 4 to 5 ([#198](https://github.com/rabbitmq/rabbitmq-stream-rust-client/pull/198))
- Bump actions/checkout from 3 to 4 ([#196](https://github.com/rabbitmq/rabbitmq-stream-rust-client/pull/196))
- Bump docker/setup-buildx-action from 2 to 3 ([#197](https://github.com/rabbitmq/rabbitmq-stream-rust-client/pull/197))
