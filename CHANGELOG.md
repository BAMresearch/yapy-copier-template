# CHANGELOG

<!-- version list -->

## v1.1.15 (2026-02-17)

### Bug Fixes

- **pypi**: Move `pytest_notebook` dependency from `pyproject.toml` to `tox.ini`
  ([`afb9461`](https://github.com/BAMresearch/yapy-copier-template/commit/afb9461f927d74f6fc43ca3599f27b7ad2535e1f))


## v1.1.14 (2026-02-16)

### Bug Fixes

- **Documentation**: Bump package versions required for generating docs
  ([`0ad0fa2`](https://github.com/BAMresearch/yapy-copier-template/commit/0ad0fa239ce5a1646ca30a8fc7b69d9efcfc469b))

- **Documentation**: Mermaid extension and broader markdown support
  ([`cfcc0b4`](https://github.com/BAMresearch/yapy-copier-template/commit/cfcc0b4349e98868dc5f79fa0ead34113a8a2687))

- **Documentation**: Typo
  ([`18d7a48`](https://github.com/BAMresearch/yapy-copier-template/commit/18d7a48460734c79bdc9a38b1061743e54be52a1))

- **GitHub Workflows**: Do not check out main branch by default
  ([`e6e919f`](https://github.com/BAMresearch/yapy-copier-template/commit/e6e919f4fcdc3dea20e9f83577d449906d271618))

- **GitHub Workflows**: Prevent empty 'with:'
  ([`4601ded`](https://github.com/BAMresearch/yapy-copier-template/commit/4601ded3d0091d0aab992cb014aa214797a34f95))

- **GitHub Workflows**: Remove unneeded checkout in publish step
  ([`4ccadd0`](https://github.com/BAMresearch/yapy-copier-template/commit/4ccadd0440f5f14e12b8bd3a7266cc604ac7c4de))

- **GitHub Workflows**: Run for other branches (PRs) as well
  ([`9052d82`](https://github.com/BAMresearch/yapy-copier-template/commit/9052d82729977e6700673b70164ecebc472aad40))

- **GitHub Workflows**: Use actions/setup-python@v6
  ([`b8495bf`](https://github.com/BAMresearch/yapy-copier-template/commit/b8495bf476ce874933107a20218f247e71e1c708))

- **pre-commit**: Version bump
  ([`e86d747`](https://github.com/BAMresearch/yapy-copier-template/commit/e86d7475d0cfdcbc6f48b82e5eb22498a32f7c34))

- **Project**: Include all toplevel markdown file in manifest
  ([`f3ad228`](https://github.com/BAMresearch/yapy-copier-template/commit/f3ad228919eef8a6ef8ca53e6aaab269b2d26af4))

- **Project**: Use pyproject.toml *optional-dependencies* for requirements
  ([`641e190`](https://github.com/BAMresearch/yapy-copier-template/commit/641e1909460f06e01a2484530c91e8b98bf6f2d5))

- **Project**: Use pyproject.toml *optional-dependencies* for requirements, pt.2
  ([`2b684ab`](https://github.com/BAMresearch/yapy-copier-template/commit/2b684ab7d5256e6301ecebd5715f2665b606d142))

### Code Style

- **Documentation**: Shorten long line
  ([`4140fb3`](https://github.com/BAMresearch/yapy-copier-template/commit/4140fb32f877a27d3f71ef8e9d6ca213a2ce8b75))


## v1.1.13 (2026-02-05)

### Bug Fixes

- **pyproject**: Allow version numbers leading zero, updated config statement
  ([`600ff92`](https://github.com/BAMresearch/yapy-copier-template/commit/600ff924b382214aaa72979156e3e036850afa5e))


## v1.1.12 (2025-12-04)

### Bug Fixes

- **GitHub Workflows**: Bump actions/checkout from 5 to 6
  ([`72d0cde`](https://github.com/BAMresearch/yapy-copier-template/commit/72d0cdee38ba179635795ae71f6bb597c05d839e))

- **GitHub Workflows**: Bump actions/download-artifact from 4 to 6
  ([`a7f7369`](https://github.com/BAMresearch/yapy-copier-template/commit/a7f73692688941a2796d8073398dfec3f6610a65))

- **GitHub Workflows**: Bump actions/upload-artifact from 4 to 5
  ([`bd598e8`](https://github.com/BAMresearch/yapy-copier-template/commit/bd598e876e52f37e32c5a24c73b4609235d63d8f))


## v1.1.11 (2025-09-05)

### Bug Fixes

- **GitHub Workflows**: Explicit PyPI URL only for custom or tests repo
  ([`abd7f9a`](https://github.com/BAMresearch/yapy-copier-template/commit/abd7f9a2373dd681a4f03fa569c6969a3787ad1c))


## v1.1.10 (2025-08-19)

### Bug Fixes

- **GitHub Workflows**: Bumps actions/checkout from 4 to 5
  ([`f81ee50`](https://github.com/BAMresearch/yapy-copier-template/commit/f81ee50596fd86dfb45d8f8f448ff2311eae2794))

- **VCS**: Let git ignore temp files from Kate editor
  ([`d499322`](https://github.com/BAMresearch/yapy-copier-template/commit/d4993226e01003e1bb34b4cb230a67c56cf23707))


## v1.1.9 (2025-08-15)

### Bug Fixes

- **GitHub Workflows**: Moved checks early before tests, instead of docs
  ([`5c501fc`](https://github.com/BAMresearch/yapy-copier-template/commit/5c501fc9d2a95e3af8221514e8902f687658c2b3))


## v1.1.8 (2025-08-13)

### Bug Fixes

- **GitHub Workflows**: Publish with verbosity for details on errors
  ([`5999991`](https://github.com/BAMresearch/yapy-copier-template/commit/5999991cb701a45b13e22ac66b327c9e067b4089))


## v1.1.7 (2025-08-13)

### Bug Fixes

- **GitHub Workflows**: Publish needs explicit pypi url to switch to test.pypi.org as well
  ([`38b4ae7`](https://github.com/BAMresearch/yapy-copier-template/commit/38b4ae7a828fe23e93a17b16eacbee02578663d0))

- **GitHub Workflows**: Pypi url needs /legacy/ suffix
  ([`f88156e`](https://github.com/BAMresearch/yapy-copier-template/commit/f88156e9a1cddef9d664e02be9899a8efbf916c9))

- **GitHub Workflows**: Update package DB before installing required system packages on linux
  ([`34ca575`](https://github.com/BAMresearch/yapy-copier-template/commit/34ca575da01eaa430e17fc43b206fcb580fd80a4))

### Documentation

- **Readme**: Notes on publishing documentation and built packages
  ([`b37798c`](https://github.com/BAMresearch/yapy-copier-template/commit/b37798c80b4b00d9d57c3ec0f025f4d8aa40515e))


## v1.1.6 (2025-07-25)

### Bug Fixes

- **Changelog**: Bold commit scope at front of each item
  ([`fd799fa`](https://github.com/BAMresearch/yapy-copier-template/commit/fd799facfdd0917fbf7d09ee438a47ab7cc046f5))

- **Changelog**: Sort changes chronologically in each category
  ([`173ed43`](https://github.com/BAMresearch/yapy-copier-template/commit/173ed438c95d1d0da983f3fd1e53d301deed2996))

### Code Style

- **Changelog**: Template formatted more readable
  ([`9ea3b09`](https://github.com/BAMresearch/yapy-copier-template/commit/9ea3b09f589c7a753569a979fa083e7af7ceb481))


## v1.1.5 (2025-07-25)

### Bug Fixes

- **readme**: Notes getting the next version number, note on packages to install
  ([`3428861`](https://github.com/BAMresearch/yapy-copier-template/commit/34288612197423e025aa77198008ef306bf3c6cd))


## v1.1.4 (2025-07-24)

### Bug Fixes

- **Packaging**: Manifest update
  ([`556b12a`](https://github.com/BAMresearch/yapy-copier-template/commit/556b12aa05015710176f105ace07ba0e7ef0bc5a))


## v1.1.3 (2025-07-24)

### Bug Fixes

- **GitHub Workflows**: Remove unused/obsolete package dependencies
  ([`2281545`](https://github.com/BAMresearch/yapy-copier-template/commit/22815451a073ddbfc6efbf9d4208678c388424c8))

- **readme**: Notes on running tests and updating the project config
  ([`d72046b`](https://github.com/BAMresearch/yapy-copier-template/commit/d72046b6468fdde0c5b377a69b6ba165c7df603c))

- **Tests**: Ipykernel is needed for notebook testing
  ([`ceba3b8`](https://github.com/BAMresearch/yapy-copier-template/commit/ceba3b8ec0e9566f0e2668448a15aae38b8e00a1))

- **Tests**: Move dependencies to tests/requirements file, remove package dependencies which go to
  pyproject.toml
  ([`9098966`](https://github.com/BAMresearch/yapy-copier-template/commit/9098966dbc7b0d490a37d8d3d21dcda587b8ecf9))


## v1.1.2 (2025-07-23)

### Bug Fixes

- **changelog**: Rename section of commits without scope to *Unknown Scope* instead of just
  *Unknown*
  ([`c99148a`](https://github.com/BAMresearch/yapy-copier-template/commit/c99148ac826e8b5dd9167bdb0bd5d66394e7081d))


## v1.1.1 (2025-07-23)

### Bug Fixes

- **changelog**: Rename section of commits without scope to *Unknown Scope* instead of just
  *Unknown*
  ([`2ab61a1`](https://github.com/BAMresearch/yapy-copier-template/commit/2ab61a1d3fbdfed049b8d9b000eb2f2b5f68a8c6))


## v1.1.0 (2025-07-23)

### Bug Fixes

- **readme**: Put project name and version number in the title, move project description after the
  badges
  ([`356d834`](https://github.com/BAMresearch/yapy-copier-template/commit/356d834b64a9865d9635b293a5d8f896bc60fa9f))

### Enh

- **changelog**: Rename section of commits without scope to *Unknown Scope* instead of just
  *Unknown*
  ([`0950019`](https://github.com/BAMresearch/yapy-copier-template/commit/095001940061d247ddc60948a2fa8ff216304138))


## v1.0.2 (2025-07-23)

### Bug Fixes

- **GitHub Workflows**: Fix regexp for version update in readme
  ([`f021e31`](https://github.com/BAMresearch/yapy-copier-template/commit/f021e31207e878cc3d0576b43730ba538bde376f))

- **GitHub Workflows**: Fix regexp for version update in readme
  ([`2b4bed6`](https://github.com/BAMresearch/yapy-copier-template/commit/2b4bed6e73b45087d5b8934cc34ab7d83048932e))


## v1.0.1 (2025-07-23)

### Bug Fixes

- **docs**: Filetype of readme in pyproject.toml needed
  ([`40acc49`](https://github.com/BAMresearch/yapy-copier-template/commit/40acc49e1af806d1ebf7d698a5649fcd3f9f545b))

- **GitHub Workflows**: Comment on history depth for semantic-release
  ([`7e0b5be`](https://github.com/BAMresearch/yapy-copier-template/commit/7e0b5be8a27a8c49b95b7ed496f78cf022dcf844))

### Continuous Integration

- **Versioning**: Semantic release setup and github action workflow
  ([`406d38b`](https://github.com/BAMresearch/yapy-copier-template/commit/406d38b76f0f00bfb015502fc18ed0dc547fef11))

### Documentation

- **changelog**: Remove duplicate entries
  ([`a6b7371`](https://github.com/BAMresearch/yapy-copier-template/commit/a6b737115db1e8335e1f127ae523fcbe8df91dc1))


## v1.0.0 (2025-07-23)

- Initial Release

### Bug Fixes

- **config**: Figuring out excluded files and locations
  ([`090fa17`](https://github.com/BAMresearch/yapy-copier-template/commit/090fa1792b9c66892a85a88dc33641117e0357b4))

- **config**: Files added, placed at the right location now
  ([`588fe5c`](https://github.com/BAMresearch/yapy-copier-template/commit/588fe5c113a0c4b4f69962cd46aec2db00c55d8b))

- **config**: Ignore folders with answers for testing
  ([`dbd347f`](https://github.com/BAMresearch/yapy-copier-template/commit/dbd347feeff01a0dc2489521e818cdef33fbff84))

- **copyright_to**: Autogenerated, the current year
  ([`66f9431`](https://github.com/BAMresearch/yapy-copier-template/commit/66f943112f2d62e09f13a22e7991f38626aa51a0))

- **docs**: Remove README.rst
  ([`7c567d6`](https://github.com/BAMresearch/yapy-copier-template/commit/7c567d61523f8d3db5d9f12dab27adc2ea6e4c2e))

- **GitHub Workflows**: Checkout() macro: string quoting and whitespace handling
  ([`dd19afd`](https://github.com/BAMresearch/yapy-copier-template/commit/dd19afdd0e9bc8dd929552775f169e6cc43bc723))

- **GitHub Workflows**: Coverage report path
  ([`8e6ccc4`](https://github.com/BAMresearch/yapy-copier-template/commit/8e6ccc42dec2543cdd6df18c53f44b63f7129b00))

- **GitHub Workflows**: Fix coverage calc, processing and publishing with docs
  ([`7c8cc8d`](https://github.com/BAMresearch/yapy-copier-template/commit/7c8cc8dbcbbf0cc78abc5d2e4853cb66b8f6667d))

- **GitHub Workflows**: Move publish job for macros to be known, jinja/github syntax fix
  ([`a2217d9`](https://github.com/BAMresearch/yapy-copier-template/commit/a2217d9a7a4370e64690901a5c812704314044c9))

- **GitHub Workflows**: Move publishing job to toplevel file for PyPIs Trusted Publisher to work
  ([`9c6029b`](https://github.com/BAMresearch/yapy-copier-template/commit/9c6029bc5be783606a5aaaae66de7fa1de848320))

- **GitHub Workflows**: Remove ci/update.py
  ([`77712ed`](https://github.com/BAMresearch/yapy-copier-template/commit/77712eddc01d83b18bdd5e80de1afcd5ed30b24e))

- **GitHub Workflows**: Revert config regression for coverage calc
  ([`cc8ce84`](https://github.com/BAMresearch/yapy-copier-template/commit/cc8ce8433a04ecab958ea53cb42a7487972cfbd6))

- **GitHub Workflows**: Whitespace and comment
  ([`1ea3226`](https://github.com/BAMresearch/yapy-copier-template/commit/1ea3226549ddb07f83f7ee0a47a2ae1db1de19a4))

- **help**: More specific help text, remove obsolete comment
  ([`ed62344`](https://github.com/BAMresearch/yapy-copier-template/commit/ed623443a42c58f7bb1654e9b88f444c726ed35e))

- **pyproject**: Supported python versions are known from answers
  ([`fa927d8`](https://github.com/BAMresearch/yapy-copier-template/commit/fa927d8dfe868fd90b2d1fae5a7bc28911c076a1))

- **questionaire**: Remove testing/debug output
  ([`fa1aa60`](https://github.com/BAMresearch/yapy-copier-template/commit/fa1aa604f64c8ec1d22bea0c6805b609b05b400d))

- **release_date**: Determine actual date in questionaire already, instead of when filling in values
  ([`75ddd2f`](https://github.com/BAMresearch/yapy-copier-template/commit/75ddd2faac1706d627756fbe019261d524bd9cb7))

- **release_date**: Rename to initial_release_date, not used for existing projects
  ([`94b11e3`](https://github.com/BAMresearch/yapy-copier-template/commit/94b11e3552fc2014acc2efa6acbde3c644ed2451))

- **semantic-release**: Replace .cookiecutterrc by .copier-answers.yml
  ([`84b6eed`](https://github.com/BAMresearch/yapy-copier-template/commit/84b6eed67fd5c24a119696c58fd7d0e88e51385f))

- **tasks**: Show the current working/destination dir
  ([`1f9f471`](https://github.com/BAMresearch/yapy-copier-template/commit/1f9f47187e3a2c728deb5e8ea579cc76aaed7332))

- **tasks**: Show the current working/destination dir
  ([`860a86d`](https://github.com/BAMresearch/yapy-copier-template/commit/860a86d4532a1e1659cfb71d146635e1b0f2e876))

- **tasks**: Testing/debugging tasks&migration excecution
  ([`4c7a974`](https://github.com/BAMresearch/yapy-copier-template/commit/4c7a974bd9fd20a7b28c6f3b919930e8bfd0bdfa))

- **tasks**: Testing/debugging tasks&migration excecution
  ([`7ab562a`](https://github.com/BAMresearch/yapy-copier-template/commit/7ab562adc6d9e03474ae0d61309ed907f7868e8d))

- **tasks**: Testing/debugging tasks&migration excecution
  ([`91d9b81`](https://github.com/BAMresearch/yapy-copier-template/commit/91d9b8117fab822fa7d437c1968c0c67f4c5c46e))

- **tasks**: Update
  ([`a256dd0`](https://github.com/BAMresearch/yapy-copier-template/commit/a256dd09dd66059e5510d142a808dd72ba7fa914))

- **tasks**: Update
  ([`d481c2d`](https://github.com/BAMresearch/yapy-copier-template/commit/d481c2d4b051b0f0361fb930e7e7424c92141ddc))

- **tasks**: Update
  ([`df4a779`](https://github.com/BAMresearch/yapy-copier-template/commit/df4a77975be12332df2f5cf0a29227f900d6c0fb))

- **templates**: Updates from comparison with current jupyter-analysis-tools
  ([`b6b3736`](https://github.com/BAMresearch/yapy-copier-template/commit/b6b373691e831492a0a526312abaf061b9617de6))

- **tox**: Linkcheck only if there is a git repo after generating documentation
  ([`c1e5d09`](https://github.com/BAMresearch/yapy-copier-template/commit/c1e5d09754dc57f79e4507a9ee3760cf06d16313))

### Documentation

- **readme**: Created
  ([`3c402ee`](https://github.com/BAMresearch/yapy-copier-template/commit/3c402ee8e0a86279356c8f7f1a862db7b0f3ec1c))

### Features

- **docs**: Readme in markdown format for combining with changelog on PyPI
  ([`2939709`](https://github.com/BAMresearch/yapy-copier-template/commit/293970965ef71aa7d8e9bb45f7c6c17715f7a5f0))

- **general**: Initial converted questionaire from yapy-cookiecutter, with more input validation
  ([`30bb3e5`](https://github.com/BAMresearch/yapy-copier-template/commit/30bb3e5be3ae26608b0ae49406b7172b385fd437))

- **python_versions**: Get supported/tested python versions from questionaire
  ([`b10bf77`](https://github.com/BAMresearch/yapy-copier-template/commit/b10bf776918c2c6c4af6fb9d0b9f44f13e2340ec))

- **tasks**: Run a check with tox after rendering, finds manifest issues etc.
  ([`0234222`](https://github.com/BAMresearch/yapy-copier-template/commit/023422290ac3a69fa25404286cb23ae48dadedb0))

### Refactoring

- **GitHub Workflows**: Render workflows by copier directly
  ([`e2ad0ce`](https://github.com/BAMresearch/yapy-copier-template/commit/e2ad0ce56c27bfcbf0fb76830972da13f444c251))

- **tasks**: Remove unused/disabled tasks, using migration script instead
  ([`ca933b2`](https://github.com/BAMresearch/yapy-copier-template/commit/ca933b227bd431b1f8e87f9f8cbd1cd4fbf375e0))
