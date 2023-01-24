# [3.0.0](https://github.com/CUexter/next-template/compare/v2.0.1...v3.0.0) (2023-01-24)


* feat(jest)!: added jest test ([32809ff](https://github.com/CUexter/next-template/commit/32809ffd1de9488367fe0813b1c71840b03ae362))


### BREAKING CHANGES

* jest now doesn't pass with no tests

## [2.0.1](https://github.com/CUexter/next-template/compare/v2.0.0...v2.0.1) (2023-01-24)

### Bug Fixes

- jest should ignore playwright tests ([18bedd5](https://github.com/CUexter/next-template/commit/18bedd593f54ecc401f5861090015e55617706b7))

# [2.0.0](https://github.com/CUexter/next-template/compare/v1.3.0...v2.0.0) (2023-01-24)

- feat(git)!: remove auto push hook ([fbe108e](https://github.com/CUexter/next-template/commit/fbe108e02572bee652362b822ed342ad3a78fdca))

### Features

- added tailwind ([4e6eba3](https://github.com/CUexter/next-template/commit/4e6eba3510e739a2284b0a52fcc8b48547892ec7))

### BREAKING CHANGES

- auto push sucks anyway

# [1.3.0](https://github.com/CUexter/next-template/compare/v1.2.1...v1.3.0) (2023-01-24)

### Bug Fixes

- change permission to write-all temporarily ([b434a3e](https://github.com/CUexter/next-template/commit/b434a3ec2647572067175079b2dd38c07aa9e740))
- e2e run mutliple times ([8e10a9d](https://github.com/CUexter/next-template/commit/8e10a9df1aca6b1fc93173aa8b560acd598b524f))
- let playwright to pass with no test ([316d45a](https://github.com/CUexter/next-template/commit/316d45ad346621ee80f1bfc1acd4a01b0083e820))
- release download artifacts from build workflow ([55ef6a3](https://github.com/CUexter/next-template/commit/55ef6a33e7aa1785829134b5ba8b0259453706b2))
- searching artifact when releasing ([8d622e0](https://github.com/CUexter/next-template/commit/8d622e02041dd691d7d5c36079b638c3d0919241))
- workflow is run multiple times ([d2d2a63](https://github.com/CUexter/next-template/commit/d2d2a63c8a56eed3b81435bc6be128fdc854b19a))

### Features

- adding build files to release ([18b81d8](https://github.com/CUexter/next-template/commit/18b81d8a8f312445fec3f1b951f479c6855d2f93))

## [1.2.1](https://github.com/CUexter/next-template/compare/v1.2.0...v1.2.1) (2023-01-23)

### Bug Fixes

- typo in test.yml ([f0ed238](https://github.com/CUexter/next-template/commit/f0ed238423cb574f654c437baa1e4e3abc2aaac6))

# [1.2.0](https://github.com/CUexter/next-template/compare/v1.1.2...v1.2.0) (2023-01-23)

### Bug Fixes

- commitlint not logged in githooks ([66c710a](https://github.com/CUexter/next-template/commit/66c710a08991404c208246e596c72d9af07c540a))

### Features

- adding e2e testing ([a86d297](https://github.com/CUexter/next-template/commit/a86d2977800a5456d73f59580b33e688c6e233f0))
- auto push after git commit ([1a2f50b](https://github.com/CUexter/next-template/commit/1a2f50bd38833dcdc77a8495de9721b6a6064634))
- **build:** automated build ([f264f2b](https://github.com/CUexter/next-template/commit/f264f2b59abfddc830541d95c157dd00b314a648))
- **githooks:** push log in husky ([4fcb36e](https://github.com/CUexter/next-template/commit/4fcb36ebe738db95917b6d9fb6d1d7b8e8987fe1))
- logging husky output ([ab3b83e](https://github.com/CUexter/next-template/commit/ab3b83eb55bcd036ff4488b568501e83a83dbc0d))
- release now trigger after test ([764c25f](https://github.com/CUexter/next-template/commit/764c25f2b9326de4988830ae735a18e5fde986eb))

## [1.1.2](https://github.com/CUexter/next-template/compare/v1.1.1...v1.1.2) (2023-01-23)

### Bug Fixes

- correct permission for semantic-release ([bde6282](https://github.com/CUexter/next-template/commit/bde628206602d252fb2af35270b6e7f0032f4a46))
- **githooks:** broken commit-msg ([d8faa41](https://github.com/CUexter/next-template/commit/d8faa41fc2d2f411f9ea2fed8403a3edd5b7aed4))

## [1.1.1](https://github.com/CUexter/next-template/compare/v1.1.0...v1.1.1) (2023-01-23)

### Bug Fixes

- adding metadata read permission for release action ([67ef9a5](https://github.com/CUexter/next-template/commit/67ef9a54b9bdc5b562ec95fa2f564707b0c6c24f))
- give all permission to release action ([39ca43d](https://github.com/CUexter/next-template/commit/39ca43decaae81f706cf7aaabb83de582fe99eeb))

# [1.1.0](https://github.com/CUexter/next-template/compare/v1.0.0...v1.1.0) (2023-01-23)

### Bug Fixes

- installing all semantic-release-plugin ([755308e](https://github.com/CUexter/next-template/commit/755308e1a15e1d23959194e025530eefcb9af4fd))
- skip githook when ci ([50adcb5](https://github.com/CUexter/next-template/commit/50adcb50ef280273d7b9daf1375ab8041d4bc14b))
- typo in .releaserc.json ([f1db164](https://github.com/CUexter/next-template/commit/f1db16493d6e15e9b3bfde6c1b7751f8134996e4))

### Features

- added tests ([39edc1e](https://github.com/CUexter/next-template/commit/39edc1ecd20bd57737d57835a9c55e8e9e74b9fd))
- **git:** add changelog generation to repo ([5e0fd51](https://github.com/CUexter/next-template/commit/5e0fd51dcb26161bd9b929b86622bd3a8553643f))
