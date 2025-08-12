# Changelog

## [0.3.0](https://github.com/groq/openbench/compare/v0.2.0...v0.3.0) (2025-08-12)


### Features

* add --debug flag to eval-retry command ([b26afaa](https://github.com/groq/openbench/commit/b26afaad31986e184c2695c6384cb1736ac0dfcb))
* add 'openbench' as alternative CLI entry point ([#48](https://github.com/groq/openbench/issues/48)) ([68b3c5b](https://github.com/groq/openbench/commit/68b3c5b4f8b8927dd5c6c8f68e25f831e9a5a222))
* add Cerebras and SambaNova model providers ([1c61f59](https://github.com/groq/openbench/commit/1c61f597ddc801caf3f085fa29fd35c50fed7b37))
* add Nebius model provider ([#47](https://github.com/groq/openbench/issues/47)) ([ba2ec19](https://github.com/groq/openbench/commit/ba2ec19ee1ac522133ed4dcd9b102d64a69933ff))
* add Nous Research model provider ([#49](https://github.com/groq/openbench/issues/49)) ([32dd815](https://github.com/groq/openbench/commit/32dd815002f9996c82bae001fdfc9b0ac7e09a0d))


### Chores

* update version ([8b7bbe7](https://github.com/groq/openbench/commit/8b7bbe74f14f67b2877cec3a6b3ae5e3a861a79a))


### Refactor

* move task loading from registry to config and update imports ([de6eea2](https://github.com/groq/openbench/commit/de6eea298d25be81be72b3c4986e72dd783c39cb))

## [0.2.0](https://github.com/groq/openbench/compare/v0.1.1...v0.2.0) (2025-08-11)


### Features

* add DROP (simple-evals) ([#20](https://github.com/groq/openbench/issues/20)) ([f85bf19](https://github.com/groq/openbench/commit/f85bf194971f4a37b917d4d6ec6dfa31a1c3954c))
* add Humanity's Last Exam (HLE) benchmark ([#23](https://github.com/groq/openbench/issues/23)) ([6f10fb7](https://github.com/groq/openbench/commit/6f10fb71d6c8cabe8cddbb23bc0c979f8fb7234b))
* add MATH and MATH-500 benchmarks for mathematical problem solving ([#22](https://github.com/groq/openbench/issues/22)) ([9c6843b](https://github.com/groq/openbench/commit/9c6843babdfcbb85162cb88e71e3d2c71beeba5b))
* add MGSM ([#18](https://github.com/groq/openbench/issues/18)) ([bec1a7c](https://github.com/groq/openbench/commit/bec1a7c732912b235941e3cedfa1ff4f9092be0f))
* add openai MRCR benchmark for long context recall ([#24](https://github.com/groq/openbench/issues/24)) ([1b09ebd](https://github.com/groq/openbench/commit/1b09ebd13e765652ec1b6e8756599a28d9544224))
* HealthBench ([#16](https://github.com/groq/openbench/issues/16)) ([2caa47d](https://github.com/groq/openbench/commit/2caa47dad56faeaede219a41a0555d2887f782bc))


### Documentation

* update CLAUDE.md with pre-commit and dependency pinning requirements ([f33730e](https://github.com/groq/openbench/commit/f33730e570d55a2da171f0e44a0382bef749421e))


### Chores

* GitHub Terraform: Create/Update .github/workflows/stale.yaml [skip ci] ([1a00342](https://github.com/groq/openbench/commit/1a00342abde5d93dab3748157493a45dbf6a62b6))

## [0.1.1](https://github.com/groq/openbench/compare/v0.1.0...v0.1.1) (2025-07-31)


### Bug Fixes

* add missing __init__.py files and fix package discovery for PyPI ([#10](https://github.com/groq/openbench/issues/10)) ([29fcdf6](https://github.com/groq/openbench/commit/29fcdf6fefa48fcf480db1f84cf5845f7f7758ce))


### Documentation

* update README to streamline setup instructions for OpenBench, use pypi ([16e08a0](https://github.com/groq/openbench/commit/16e08a091b6fcc56422df21d1352bcc88481f175))

## 0.1.0 (2025-07-31)


### Features

* openbench ([3265bb0](https://github.com/groq/openbench/commit/3265bb07929f461a96d608d54fcdb144c66c0ac7))


### Chores

* **ci:** update release-please workflow to allow label management ([b70db16](https://github.com/groq/openbench/commit/b70db1665355be278af8a6d06f2a58aeedbe4a31))
* drop versions  for release ([58ce995](https://github.com/groq/openbench/commit/58ce9958b715c2f83fab509afdf046811b18c128))
* GitHub Terraform: Create/Update .github/workflows/stale.yaml [skip ci] ([555658a](https://github.com/groq/openbench/commit/555658af369b4e88eb92bf7f2afa2adcc4934835))
* update project metadata for version 0.1.0, add license, readme, and repository links ([9ea2102](https://github.com/groq/openbench/commit/9ea21029ebe3782d3d67b6aa075faf8862440fbf))
