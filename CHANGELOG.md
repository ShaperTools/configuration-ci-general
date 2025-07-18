# Change Log

All notable changes to this project will be documented in this file. See [standard-version](https://github.com/conventional-changelog/standard-version) for commit guidelines.

<a name="0.8.0"></a>
# [0.8.0](https://github.com/shapertools/configuration-ci-general/compare/v0.7.6...v0.8.0) (2025-07-14)


### Bug Fixes

* Refactor terraform commands ([98365fe](https://github.com/shapertools/configuration-ci-general/commit/98365fe))
* Update package json ([6829017](https://github.com/shapertools/configuration-ci-general/commit/6829017))


### Features

* **terraform:** Fix failing pipelines due to outdated images ([c7936a8](https://github.com/shapertools/configuration-ci-general/commit/c7936a8))



<a name="0.7.6"></a>
## [0.7.6](https://github.com/shapertools/configuration-ci-general/compare/v0.7.5...v0.7.6) (2025-06-25)


### Bug Fixes

* Add condition to configure profile ([e5d574a](https://github.com/shapertools/configuration-ci-general/commit/e5d574a))
* Reuse credentials variables in configure aws profile ([5ad2b3f](https://github.com/shapertools/configuration-ci-general/commit/5ad2b3f))



<a name="0.7.5"></a>
## [0.7.5](https://github.com/shapertools/configuration-ci-general/compare/v0.7.4...v0.7.5) (2024-09-17)


### Bug Fixes

* Just use LTS rather than a random archaic node version ([35e1e1f](https://github.com/shapertools/configuration-ci-general/commit/35e1e1f))
* Switch away from deprecated images ([2f714f8](https://github.com/shapertools/configuration-ci-general/commit/2f714f8))



<a name="0.7.4"></a>
## [0.7.4](https://github.com/shapertools/configuration-ci-general/compare/v0.7.3...v0.7.4) (2024-09-17)


### Bug Fixes

* Stop execution after halting during check-isolated-deployment-label ([4817247](https://github.com/shapertools/configuration-ci-general/commit/4817247))



<a name="0.7.3"></a>
## [0.7.3](https://github.com/shapertools/configuration-ci-general/compare/v0.7.2...v0.7.3) (2024-08-23)


### Bug Fixes

* Cleanup PR Deployments Job ([149891a](https://github.com/shapertools/configuration-ci-general/commit/149891a))



<a name="0.7.2"></a>
## [0.7.2](https://github.com/shapertools/configuration-ci-general/compare/v0.7.1...v0.7.2) (2024-08-22)


### Bug Fixes

* Remove age check for isolated envs ([83f75a3](https://github.com/shapertools/configuration-ci-general/commit/83f75a3))



<a name="0.7.1"></a>
## [0.7.1](https://github.com/shapertools/configuration-ci-general/compare/v0.7.0...v0.7.1) (2024-08-20)


### Bug Fixes

* Cleanup PR and commit deployments older than 14 days ([6243087](https://github.com/shapertools/configuration-ci-general/commit/6243087))



<a name="0.7.0"></a>
## [0.7.0](https://github.com/shapertools/configuration-ci-general/compare/v0.5.7...v0.7.0) (2024-06-24)


### Bug Fixes

* Remove trailing `.` from parameter use in `configure-aws-profile` command ([a596ebd](https://github.com/shapertools/configuration-ci-general/commit/a596ebd))



<a name="0.5.7"></a>
## [0.5.7](https://github.com/shapertools/configuration-ci-general/compare/v0.5.6...v0.5.7) (2024-03-11)


### Bug Fixes

* Setting remote docker version to default ([540456b](https://github.com/shapertools/configuration-ci-general/commit/540456b))



<a name="0.5.6"></a>
## [0.5.6](https://github.com/shapertools/configuration-ci-general/compare/v0.5.5...v0.5.6) (2023-09-01)


### Bug Fixes

* Install AWS CLI in terraform apply job ([1a2177e](https://github.com/shapertools/configuration-ci-general/commit/1a2177e))



<a name="0.5.5"></a>
## [0.5.5](https://github.com/shapertools/configuration-ci-general/compare/v0.5.4...v0.5.5) (2023-08-23)


### Bug Fixes

* Install aws-cli in cleanup jobs ([0b7ee42](https://github.com/shapertools/configuration-ci-general/commit/0b7ee42))



<a name="0.5.4"></a>
# [0.5.4](https://github.com/shapertools/configuration-ci-general/compare/v0.5.3...v0.5.4) (2023-08-23)


### Bug Fixes

* Remove get-eks-token command ([b75c7eb](https://github.com/shapertools/configuration-ci-general/commit/b75c7eb))



<a name="0.5.3"></a>
## [0.5.3](https://github.com/shapertools/configuration-ci-general/compare/v0.5.2...v0.5.3) (2023-08-21)


### Bug Fixes

* Allow specifying directory when installing yarn dependencies ([1eaae55](https://github.com/shapertools/configuration-ci-general/commit/1eaae55))



<a name="0.5.2"></a>
## [0.5.2](https://github.com/shapertools/configuration-ci-general/compare/v0.5.1...v0.5.2) (2023-07-20)


### Bug Fixes

* Allow backend config when destroying deployments ([deed670](https://github.com/shapertools/configuration-ci-general/commit/deed670))



<a name="0.5.1"></a>
## [0.5.1](https://github.com/shapertools/configuration-ci-general/compare/v0.5.0...v0.5.1) (2023-06-26)


### Bug Fixes

* Add terraform-plan-comment command ([0ee3bec](https://github.com/shapertools/configuration-ci-general/commit/0ee3bec))



<a name="0.5.0"></a>
# [0.5.0](https://github.com/shapertools/configuration-ci-general/compare/v0.4.3...v0.5.0) (2023-06-16)


### Features

* Allow passing a backend-config file to terraform plan/apply ([a33c009](https://github.com/shapertools/configuration-ci-general/commit/a33c009))



<a name="0.4.3"></a>
## [0.4.3](https://github.com/shapertools/configuration-ci-general/compare/v0.4.1...v0.4.3) (2023-03-29)


### Bug Fixes

* Also fix ssh key fingerprint ([fc1502c](https://github.com/shapertools/configuration-ci-general/commit/fc1502c))
* Try using dev orb for main circle config ([a7ffab4](https://github.com/shapertools/configuration-ci-general/commit/a7ffab4))
* Update to exact match pr name on cleanup ([7c53c30](https://github.com/shapertools/configuration-ci-general/commit/7c53c30))



<a name="0.4.2"></a>
## [0.4.2](https://github.com/shapertools/configuration-ci-general/compare/v0.4.1...v0.4.2) (2023-03-29)


### Bug Fixes

* Updating github RSA public key ([1c47ed2](https://github.com/shapertools/configuration-ci-general/commit/1c47ed2))
* Update to exact match pr name on cleanup ([7c53c30](https://github.com/shapertools/configuration-ci-general/commit/7c53c30))



<a name="0.4.1"></a>
## [0.4.1](https://github.com/shapertools/configuration-ci-general/compare/v0.4.0...v0.4.1) (2022-04-22)


### Bug Fixes

* Remove braces in region parameter ([8779ea1](https://github.com/shapertools/configuration-ci-general/commit/8779ea1))



<a name="0.4.0"></a>
# [0.4.0](https://github.com/shapertools/configuration-ci-general/compare/v0.3.12...v0.4.0) (2022-04-22)


### Features

* Add region parameter to configure-aws-profile command ([8f6fe12](https://github.com/shapertools/configuration-ci-general/commit/8f6fe12))



<a name="0.3.12"></a>
## [0.3.12](https://github.com/shapertools/configuration-ci-general/compare/v0.3.10...v0.3.12) (2022-01-21)

Bump to make the CI flows work?

<a name="0.3.11"></a>
## [0.3.11](https://github.com/shapertools/configuration-ci-general/compare/v0.3.10...v0.3.11) (2022-01-21)

* Makes yarn install optional

<a name="0.3.10"></a>
## [0.3.10](https://github.com/shapertools/configuration-ci-general/compare/v0.3.9...v0.3.10) (2022-01-04)



<a name="0.3.9"></a>
## [0.3.9](https://github.com/shapertools/configuration-ci-general/compare/v0.3.8...v0.3.9) (2021-11-18)


### Bug Fixes

* Sets timeout to 20 mins ([f91d7d6](https://github.com/shapertools/configuration-ci-general/commit/f91d7d6))



<a name="0.3.8"></a>
## [0.3.8](https://github.com/shapertools/configuration-ci-general/compare/v0.3.7...v0.3.8) (2021-11-18)


### Bug Fixes

* Expose executor to build-image ([955aa1a](https://github.com/shapertools/configuration-ci-general/commit/955aa1a))



<a name="0.3.7"></a>
## [0.3.7](https://github.com/shapertools/configuration-ci-general/compare/v0.3.6...v0.3.7) (2021-11-17)


### Bug Fixes

* Expose the executor to jobs ([1ebab5f](https://github.com/shapertools/configuration-ci-general/commit/1ebab5f))



<a name="0.3.6"></a>
## [0.3.6](https://github.com/shapertools/configuration-ci-general/compare/v0.3.5...v0.3.6) (2021-11-15)


### Bug Fixes

* Increase the resource class ([414a64b](https://github.com/shapertools/configuration-ci-general/commit/414a64b))



<a name="0.3.5"></a>
## [0.3.5](https://github.com/shapertools/configuration-ci-general/compare/v0.3.4...v0.3.5) (2021-10-11)


### Bug Fixes

* Just use a new step for yarn stuff ([b24d796](https://github.com/shapertools/configuration-ci-general/commit/b24d796))
* Specify a modern (but compatible with circle) version of docker ([4676cdd](https://github.com/shapertools/configuration-ci-general/commit/4676cdd))



<a name="0.3.4"></a>
## [0.3.4](https://github.com/shapertools/configuration-ci-general/compare/v0.3.3...v0.3.4) (2021-10-11)


### Bug Fixes

* Specify a modern version of docker by default ([60e4a33](https://github.com/shapertools/configuration-ci-general/commit/60e4a33))



<a name="0.3.3"></a>
## [0.3.3](https://github.com/shapertools/configuration-ci-general/compare/v0.3.2...v0.3.3) (2021-10-11)


### Bug Fixes

* Try this node image (since it's buster) ([b52b049](https://github.com/shapertools/configuration-ci-general/commit/b52b049))



<a name="0.3.2"></a>
## [0.3.2](https://github.com/shapertools/configuration-ci-general/compare/v0.3.1...v0.3.2) (2021-10-11)


### Bug Fixes

* Fix node version so yarn can use worker_threads ([99065ef](https://github.com/shapertools/configuration-ci-general/commit/99065ef))



<a name="0.3.1"></a>
## [0.3.1](https://github.com/shapertools/configuration-ci-general/compare/v0.3.0...v0.3.1) (2021-10-09)


### Bug Fixes

* Fix yarn install (img should already have it) ([e272fd5](https://github.com/shapertools/configuration-ci-general/commit/e272fd5))



<a name="0.3.0"></a>
# [0.3.0](https://github.com/shapertools/configuration-ci-general/compare/v0.1.4...v0.3.0) (2021-10-09)


### Features

* Support yarn ([1c7214a](https://github.com/shapertools/configuration-ci-general/commit/1c7214a))



<a name="0.2.0"></a>
# [0.2.0](https://github.com/shapertools/configuration-ci-general/compare/v0.1.4...v0.2.0) (2021-10-08)


### Features

* Support yarn ([1c7214a](https://github.com/shapertools/configuration-ci-general/commit/1c7214a))



<a name="0.1.4"></a>
## [0.1.4](https://github.com/shapertools/configuration-ci-general/compare/v0.1.3...v0.1.4) (2021-08-17)


### Bug Fixes

* Fix debian versioning issue for node install ([a5977a7](https://github.com/shapertools/configuration-ci-general/commit/a5977a7))



<a name="0.1.3"></a>
## [0.1.3](https://github.com/shapertools/configuration-ci-general/compare/v0.1.0...v0.1.3) (2021-08-16)


### Bug Fixes

* Also fix old orb ([5d5ec5f](https://github.com/shapertools/configuration-ci-general/commit/5d5ec5f))
* Also fix these ([2a12732](https://github.com/shapertools/configuration-ci-general/commit/2a12732))
* Fix debian versioning issue ([5bbb849](https://github.com/shapertools/configuration-ci-general/commit/5bbb849))



<a name="0.1.2"></a>
## [0.1.2](https://github.com/shapertools/configuration-ci-general/compare/v0.1.0...v0.1.2) (2021-08-16)


### Bug Fixes

* Also fix old orb ([5d5ec5f](https://github.com/shapertools/configuration-ci-general/commit/5d5ec5f))
* Also fix these ([2a12732](https://github.com/shapertools/configuration-ci-general/commit/2a12732))
* Fix debian versioning issue ([5bbb849](https://github.com/shapertools/configuration-ci-general/commit/5bbb849))



<a name="0.1.1"></a>
## [0.1.1](https://github.com/shapertools/configuration-ci-general/compare/v0.1.0...v0.1.1) (2021-08-16)


### Bug Fixes

* Also fix old orb ([5d5ec5f](https://github.com/shapertools/configuration-ci-general/commit/5d5ec5f))
* Also fix these ([2a12732](https://github.com/shapertools/configuration-ci-general/commit/2a12732))
* Fix debian versioning issue ([5bbb849](https://github.com/shapertools/configuration-ci-general/commit/5bbb849))



<a name="0.1.0"></a>
# [0.1.0](https://github.com/shapertools/configuration-ci-general/compare/v1.31.0...v0.1.0) (2021-01-07)


### Bug Fixes

* Change commit message check for merge method ([7576355](https://github.com/shapertools/configuration-ci-general/commit/7576355))
* Revert versionTag retrieval from release commit subject ([2698c8f](https://github.com/shapertools/configuration-ci-general/commit/2698c8f))


### Features

* Get test job compatible with docker-compose ([3a78a25](https://github.com/shapertools/configuration-ci-general/commit/3a78a25))
* Initial commit ([d7fc912](https://github.com/shapertools/configuration-ci-general/commit/d7fc912))
