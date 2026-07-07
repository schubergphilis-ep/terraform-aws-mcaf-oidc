# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

---

## [0.8.1](https://github.com/schubergphilis-ep/terraform-aws-mcaf-oidc/compare/v0.8.0...v0.8.1) (2026-07-07)


### 🐛 Fixes

* migrate MCAF module sources ([#2](https://github.com/schubergphilis-ep/terraform-aws-mcaf-oidc/issues/2)) ([5cde1d1](https://github.com/schubergphilis-ep/terraform-aws-mcaf-oidc/commit/5cde1d1fbc7f00794567b5a1b7a84063dd22c12e))

## [0.8.0](https://github.com/schubergphilis-ep/terraform-aws-mcaf-oidc/compare/v0.7.0...v0.8.0) (2026-06-26)


### 🐛 Fixes

* correct environment sub claim and add immutable repositories ([#13](https://github.com/schubergphilis/terraform-aws-mcaf-oidc/pull/13)) ([66dff69](https://github.com/schubergphilis-ep/terraform-aws-mcaf-oidc/commit/66dff6901125d78ba335207540f01b1cfd3d8015))

## [0.7.0](https://github.com/schubergphilis-ep/terraform-aws-mcaf-oidc/compare/v0.6.0...v0.7.0) (2025-06-20)


### 🚀 Features

* add option to iam_roles variable to specify the max_session_duration ([#12](https://github.com/schubergphilis/terraform-aws-mcaf-oidc/pull/12)) ([8b9069b](https://github.com/schubergphilis-ep/terraform-aws-mcaf-oidc/commit/8b9069b7c6c4f1b7a10800439671eab63ac64422))

## [0.6.0](https://github.com/schubergphilis-ep/terraform-aws-mcaf-oidc/compare/v0.5.2...v0.6.0) (2025-04-24)


### 🚀 Features

* add an additional allow_all subject filter to the github oidc module ([#11](https://github.com/schubergphilis/terraform-aws-mcaf-oidc/pull/11)) ([8868c82](https://github.com/schubergphilis-ep/terraform-aws-mcaf-oidc/commit/8868c829b0660ed426ee84b8049a54c7090729fc))

## [0.5.2](https://github.com/schubergphilis-ep/terraform-aws-mcaf-oidc/compare/v0.5.1...v0.5.2) (2025-04-14)


### 🐛 Fixes

* bug: Correct optional setting for thumbprint_url ([#10](https://github.com/schubergphilis/terraform-aws-mcaf-oidc/pull/10)) ([ff33cd7](https://github.com/schubergphilis-ep/terraform-aws-mcaf-oidc/commit/ff33cd7248adf7ee171d6f156605a76f3d0c59df))

## [0.5.1](https://github.com/schubergphilis-ep/terraform-aws-mcaf-oidc/compare/v0.5.0...v0.5.1) (2025-04-14)


### 🐛 Fixes

* bug: Correction to audience logic condition ([#9](https://github.com/schubergphilis/terraform-aws-mcaf-oidc/pull/9)) ([4339916](https://github.com/schubergphilis-ep/terraform-aws-mcaf-oidc/commit/4339916d65671e87978dfb44f9da5ba05a85d49c))

## [0.5.0](https://github.com/schubergphilis-ep/terraform-aws-mcaf-oidc/compare/v0.4.1...v0.5.0) (2025-04-11)


### 🐛 Fixes

* client_ids and thumbprint_url are only needed when the oidc provider is created ([#7](https://github.com/schubergphilis/terraform-aws-mcaf-oidc/pull/7)) ([568ede4](https://github.com/schubergphilis-ep/terraform-aws-mcaf-oidc/commit/568ede4c53ad7a6768f27250d71176b97071192e))
* client_ids and thumbprint_url are only needed when the oidc provider is created ([#7](https://github.com/schubergphilis/terraform-aws-mcaf-oidc/pull/7)) ([568ede4](https://github.com/schubergphilis-ep/terraform-aws-mcaf-oidc/commit/568ede4c53ad7a6768f27250d71176b97071192e))

## [0.4.1](https://github.com/schubergphilis-ep/terraform-aws-mcaf-oidc/compare/v0.4.0...v0.4.1) (2025-04-11)


### 🐛 Fixes

* bug: remove unused name in the oidc_provider variable ([#6](https://github.com/schubergphilis/terraform-aws-mcaf-oidc/pull/6)) ([fd3158b](https://github.com/schubergphilis-ep/terraform-aws-mcaf-oidc/commit/fd3158b02be7147d03d551c507aa8ac0022ad8f3))

## [0.4.0](https://github.com/schubergphilis-ep/terraform-aws-mcaf-oidc/compare/v0.3.1...v0.4.0) (2025-04-04)


### 🚀 Features

* Dynamic condition sub/aud ([#5](https://github.com/schubergphilis/terraform-aws-mcaf-oidc/pull/5)) ([d9245e4](https://github.com/schubergphilis-ep/terraform-aws-mcaf-oidc/commit/d9245e4e5a7ab09fd9855506ca8805e01b2ca313))

## [0.3.1](https://github.com/schubergphilis-ep/terraform-aws-mcaf-oidc/compare/v0.3.0...v0.3.1) (2025-03-14)


### 🐛 Fixes

* solve isse with github url malformed during certificat retrieval ([#4](https://github.com/schubergphilis/terraform-aws-mcaf-oidc/pull/4)) ([58bb583](https://github.com/schubergphilis-ep/terraform-aws-mcaf-oidc/commit/58bb583e3529524a28725df0d0877a29203cb882))

## [0.3.0](https://github.com/schubergphilis-ep/terraform-aws-mcaf-oidc/compare/v0.2.0...v0.3.0) (2025-03-11)


### 🚀 Features

* add support for multiple subject_filters ([#3](https://github.com/schubergphilis/terraform-aws-mcaf-oidc/pull/3)) ([50e4c26](https://github.com/schubergphilis-ep/terraform-aws-mcaf-oidc/commit/50e4c2630e49a4a8deb1dbe4c1b43f12faf23fe3))

## [0.2.0](https://github.com/schubergphilis-ep/terraform-aws-mcaf-oidc/compare/v0.1.0...v0.2.0) (2025-03-11)


### 🚀 Features

* simplify gitlab module ([#2](https://github.com/schubergphilis/terraform-aws-mcaf-oidc/pull/2)) ([7813a42](https://github.com/schubergphilis-ep/terraform-aws-mcaf-oidc/commit/7813a42c3e6eafae93d2622166e8b806c1a493bd))

## 0.1.0 (2025-03-03)


### 🚀 Features

* initial commit ([#1](https://github.com/schubergphilis/terraform-aws-mcaf-oidc/pull/1)) ([09c17af](https://github.com/schubergphilis-ep/terraform-aws-mcaf-oidc/commit/09c17afa939dc7264eeeb9d7f0512674c59be696))
