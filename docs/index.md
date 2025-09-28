# GitHub Actions Versions

## actions/checkout

| Major | Latest Minor/Patch |
|-------|--------------------|
| v5 | v5.0.0 |

#### v5.0.0 Release Notes
## What's Changed
* Update actions checkout to use node 24 by @salmanmkc in https://github.com/actions/checkout/pull/2226
* Prepare v5.0.0 release by @salmanmkc in https://github.com/actions/checkout/pull/2238

## ⚠️ Minimum Compatible Runner Version

**v2.327.1**  
[Release Notes](https://github.com/actions/runner/releases/tag/v2.327.1)

Make sure your runner is updated to this version or newer to use this release.

**Full Changelog**: https://github.com/actions/checkout/compare/v4...v5.0.0

| v4 | v4.3.0 |

#### v4.3.0 Release Notes
## What's Changed
* docs: update README.md by @motss in https://github.com/actions/checkout/pull/1971
* Add internal repos for checking out multiple repositories by @mouismail in https://github.com/actions/checkout/pull/1977
* Documentation update - add recommended permissions to Readme by @benwells in https://github.com/actions/checkout/pull/2043
* Adjust positioning of user email note and permissions heading by @joshmgross in https://github.com/actions/checkout/pull/2044
* Update README.md by @nebuk89 in https://github.com/actions/checkout/pull/2194
* Update CODEOWNERS for actions by @TingluoHuang in https://github.com/actions/checkout/pull/2224
* Update package dependencies by @salmanmkc in https://github.com/actions/checkout/pull/2236
* Prepare release v4.3.0 by @salmanmkc in https://github.com/actions/checkout/pull/2237

## New Contributors
* @motss made their first contribution in https://github.com/actions/checkout/pull/1971
* @mouismail made their first contribution in https://github.com/actions/checkout/pull/1977
* @benwells made their first contribution in https://github.com/actions/checkout/pull/2043
* @nebuk89 made their first contribution in https://github.com/actions/checkout/pull/2194
* @salmanmkc made their first contribution in https://github.com/actions/checkout/pull/2236

**Full Changelog**: https://github.com/actions/checkout/compare/v4...v4.3.0


## actions/setup-java

| Major | Latest Minor/Patch |
|-------|--------------------|
| v5 | v5.0.0 |

#### v5.0.0 Release Notes
## What's Changed

### Breaking Changes
* Upgrade to node 24 by @salmanmkc in https://github.com/actions/setup-java/pull/888

Make sure your runner is updated to this version or newer to use this release. v2.327.1 [Release Notes](https://github.com/actions/runner/releases/tag/v2.327.1)

### Dependency Upgrades
* Upgrade Publish Immutable Action by @HarithaVattikuti in https://github.com/actions/setup-java/pull/798
* Upgrade eslint-plugin-jest from 27.9.0 to 28.11.0 by @dependabot[bot] in https://github.com/actions/setup-java/pull/730
* Upgrade undici from 5.28.5 to 5.29.0 by @dependabot[bot] in https://github.com/actions/setup-java/pull/833
* Upgrade form-data to bring in fix for critical vulnerability by @gowridurgad in https://github.com/actions/setup-java/pull/887
* Upgrade actions/checkout from 4 to 5 by @dependabot[bot] in https://github.com/actions/setup-java/pull/896

### Bug Fixes
* Prevent default installation of JetBrains pre-releases by @priyagupta108 in https://github.com/actions/setup-java/pull/859
* Improve Error Handling for Setup-Java Action to Help Debug Intermittent Failures by @gowridurgad in https://github.com/actions/setup-java/pull/848

## New Contributors
* @gowridurgad made their first contribution in https://github.com/actions/setup-java/pull/848
* @salmanmkc made their first contribution in https://github.com/actions/setup-java/pull/888

**Full Changelog**: https://github.com/actions/setup-java/compare/v4...v5.0.0

| v4 | v4.7.1 |

#### v4.7.1 Release Notes
## What's Changed

### Documentation changes
* Add Documentation to Recommend Using GraalVM JDK 17 Version to 17.0.12 to Align with GFTC License Terms by @aparnajyothi-y in https://github.com/actions/setup-java/pull/704
* Remove duplicated GraalVM section in documentation by @Marcono1234 in https://github.com/actions/setup-java/pull/716

### Dependency updates:
* Upgrade @action/cache from 4.0.0 to 4.0.2 by @aparnajyothi-y in https://github.com/actions/setup-java/pull/766
* Upgrade @actions/glob from 0.4.0 to 0.5.0 by @dependabot in https://github.com/actions/setup-java/pull/744
* Upgrade ts-jest from 29.1.2 to 29.2.5 by @dependabot in https://github.com/actions/setup-java/pull/743
* Upgrade @action/cache to 4.0.3 by @aparnajyothi-y in https://github.com/actions/setup-java/pull/773

**Full Changelog**: https://github.com/actions/setup-java/compare/v4...v4.7.1


## actions/setup-python

| Major | Latest Minor/Patch |
|-------|--------------------|
| v6 | v6.0.0 |

#### v6.0.0 Release Notes
## What's Changed
### Breaking Changes
* Upgrade to node 24 by @salmanmkc in https://github.com/actions/setup-python/pull/1164

Make sure your runner is on version v2.327.1 or later to ensure compatibility with this release. [See Release Notes](https://github.com/actions/runner/releases/tag/v2.327.1)
### Enhancements:
* Add support for `pip-version`  by @priyagupta108 in https://github.com/actions/setup-python/pull/1129
* Enhance reading from .python-version by @krystof-k in https://github.com/actions/setup-python/pull/787
* Add version parsing from Pipfile by @aradkdj in https://github.com/actions/setup-python/pull/1067
### Bug fixes:
* Clarify pythonLocation behaviour for PyPy and GraalPy in environment variables by @aparnajyothi-y in https://github.com/actions/setup-python/pull/1183
* Change missing cache directory error to warning  by @aparnajyothi-y in https://github.com/actions/setup-python/pull/1182
* Add Architecture-Specific PATH Management for Python with --user Flag on Windows by @aparnajyothi-y in https://github.com/actions/setup-python/pull/1122
* Include python version in PyPy python-version output by @cdce8p in https://github.com/actions/setup-python/pull/1110
* Update docs: clarification on pip authentication with setup-python by @priya-kinthali in https://github.com/actions/setup-python/pull/1156
### Dependency updates:
* Upgrade idna from 2.9 to 3.7 in /__tests__/data by @dependabot[bot] in https://github.com/actions/setup-python/pull/843
* Upgrade form-data to fix critical vulnerabilities #182 & #183 by @aparnajyothi-y in https://github.com/actions/setup-python/pull/1163
* Upgrade setuptools to 78.1.1 to fix path traversal vulnerability in PackageIndex.download by @aparnajyothi-y in https://github.com/actions/setup-python/pull/1165
* Upgrade actions/checkout from 4 to 5 by @dependabot[bot] in https://github.com/actions/setup-python/pull/1181
* Upgrade @actions/tool-cache from 2.0.1 to 2.0.2 by @dependabot[bot] in https://github.com/actions/setup-python/pull/1095

## New Contributors
* @krystof-k made their first contribution in https://github.com/actions/setup-python/pull/787
* @cdce8p made their first contribution in https://github.com/actions/setup-python/pull/1110
* @aradkdj made their first contribution in https://github.com/actions/setup-python/pull/1067

**Full Changelog**: https://github.com/actions/setup-python/compare/v5...v6.0.0

| v5 | v5.6.0 |

#### v5.6.0 Release Notes
## What's Changed
* Workflow updates related to Ubuntu 20.04 by @aparnajyothi-y in https://github.com/actions/setup-python/pull/1065
* Fix for Candidate Not Iterable Error by @aparnajyothi-y in https://github.com/actions/setup-python/pull/1082
* Upgrade semver and @types/semver by @dependabot in https://github.com/actions/setup-python/pull/1091
* Upgrade prettier from 2.8.8 to 3.5.3 by @dependabot in https://github.com/actions/setup-python/pull/1046
* Upgrade ts-jest from 29.1.2 to 29.3.2 by @dependabot in https://github.com/actions/setup-python/pull/1081


**Full Changelog**: https://github.com/actions/setup-python/compare/v5...v5.6.0


## actions/setup-dotnet

| Major | Latest Minor/Patch |
|-------|--------------------|
| v5 | v5.0.0 |

#### v5.0.0 Release Notes
## What's Changed

### Breaking Changes
* Upgrade to Node.js 24 and modernize async usage by @salmanmkc in https://github.com/actions/setup-dotnet/pull/654

Make sure your runner is updated to this version or newer to use this release. v2.327.1 [Release Notes](https://github.com/actions/runner/releases/tag/v2.327.1)

### Dependency Updates
* Upgrade @action/cache from 4.0.2 to 4.0.3 by @aparnajyothi-y in https://github.com/actions/setup-dotnet/pull/622
* Upgrade husky from 8.0.3 to 9.1.7 by @dependabot[bot] in https://github.com/actions/setup-dotnet/pull/591
* Upgrade @actions/glob from 0.4.0 to 0.5.0 by @dependabot[bot] in https://github.com/actions/setup-dotnet/pull/594
* Upgrade eslint-config-prettier from 9.1.0 to 10.1.5 by @dependabot[bot] in https://github.com/actions/setup-dotnet/pull/639
* Upgrade undici from 5.28.5 to 5.29.0 by @dependabot[bot] in https://github.com/actions/setup-dotnet/pull/641
* Upgrade form-data to bring in fix for critical vulnerability by @gowridurgad in https://github.com/actions/setup-dotnet/pull/652
* Upgrade actions/checkout from 4 to 5 by @dependabot[bot] in https://github.com/actions/setup-dotnet/pull/662


### Bug Fixes
* Remove Support for older .NET Versions and Update installers scripts by @gowridurgad in https://github.com/actions/setup-dotnet/pull/647

## New Contributors
* @gowridurgad made their first contribution in https://github.com/actions/setup-dotnet/pull/647
* @salmanmkc made their first contribution in https://github.com/actions/setup-dotnet/pull/654

**Full Changelog**: https://github.com/actions/setup-dotnet/compare/v4...v5.0.0

| v4 | v4.3.1 |

#### v4.3.1 Release Notes
## What's Changed
* `v4` - Remove `azureedge.net` fallback logic and update install scripts by @zaataylor in https://github.com/actions/setup-dotnet/pull/572
As outlined in[ Critical .NET Install Links Are Changing](https://devblogs.microsoft.com/dotnet/critical-dotnet-install-links-are-changing/#call-to-action), remove the storage account fallback logic added for v4 in https://github.com/actions/setup-dotnet/pull/566 and update the install scripts accordingly.
**Related issue**: https://github.com/dotnet/install-scripts/issues/559
* upgrade @actions/cache to 4.0.2 by @HarithaVattikuti in https://github.com/actions/setup-dotnet/pull/615


**Full Changelog**: https://github.com/actions/setup-dotnet/compare/v4...v4.3.1


## actions/setup-node

| Major | Latest Minor/Patch |
|-------|--------------------|
| v5 | v5.0.0 |

#### v5.0.0 Release Notes
## What's Changed

### Breaking Changes
* Enhance caching in setup-node with automatic package manager detection by @priya-kinthali in https://github.com/actions/setup-node/pull/1348

This update, introduces automatic caching when a valid `packageManager` field is present in your `package.json`. This aims to improve workflow performance and make dependency management more seamless. 
To disable this automatic caching, set `package-manager-cache: false`
```yaml
steps:
- uses: actions/checkout@v5
- uses: actions/setup-node@v5
  with:
    package-manager-cache: false
```
* Upgrade action to use node24 by @salmanmkc in https://github.com/actions/setup-node/pull/1325

Make sure your runner is on version v2.327.1 or later to ensure compatibility with this release. [See Release Notes](https://github.com/actions/runner/releases/tag/v2.327.1)


### Dependency Upgrades
* Upgrade @octokit/request-error and @actions/github by @dependabot[bot] in https://github.com/actions/setup-node/pull/1227
* Upgrade uuid from 9.0.1 to 11.1.0 by @dependabot[bot] in https://github.com/actions/setup-node/pull/1273
* Upgrade undici from 5.28.5 to 5.29.0 by @dependabot[bot] in https://github.com/actions/setup-node/pull/1295
* Upgrade form-data to bring in fix for critical vulnerability by @gowridurgad in https://github.com/actions/setup-node/pull/1332
* Upgrade actions/checkout from 4 to 5 by @dependabot[bot] in https://github.com/actions/setup-node/pull/1345

## New Contributors
* @priya-kinthali made their first contribution in https://github.com/actions/setup-node/pull/1348
* @salmanmkc made their first contribution in https://github.com/actions/setup-node/pull/1325

**Full Changelog**: https://github.com/actions/setup-node/compare/v4...v5.0.0

| v4 | v4.4.0 |

#### v4.4.0 Release Notes
## What's Changed
### Bug fixes:
* Make eslint-compact matcher compatible with Stylelint by @FloEdelmann in https://github.com/actions/setup-node/pull/98
* Add support for indented eslint output by @fregante in https://github.com/actions/setup-node/pull/1245
### Enhancement:
* Support private mirrors by @marco-ippolito in https://github.com/actions/setup-node/pull/1240
### Dependency update:
* Upgrade @action/cache from 4.0.2 to 4.0.3 by @aparnajyothi-y in https://github.com/actions/setup-node/pull/1262

## New Contributors
* @FloEdelmann made their first contribution in https://github.com/actions/setup-node/pull/98
* @fregante made their first contribution in https://github.com/actions/setup-node/pull/1245
* @marco-ippolito made their first contribution in https://github.com/actions/setup-node/pull/1240

**Full Changelog**: https://github.com/actions/setup-node/compare/v4...v4.4.0


## actions/upload-artifact

| Major | Latest Minor/Patch |
|-------|--------------------|
| v4 | v4.6.2 |

#### v4.6.2 Release Notes
## What's Changed
* Update to use artifact 2.3.2 package & prepare for new upload-artifact release by @salmanmkc in https://github.com/actions/upload-artifact/pull/685

## New Contributors
* @salmanmkc made their first contribution in https://github.com/actions/upload-artifact/pull/685

**Full Changelog**: https://github.com/actions/upload-artifact/compare/v4...v4.6.2

| v3 | v3.2.1 |

#### v3.2.1 Release Notes
## What's Changed

This fixes the `include-hidden-files` input introduced in https://github.com/actions/upload-artifact/releases/tag/v3.2.0

* Ensure hidden files input is used by @joshmgross in https://github.com/actions/upload-artifact/pull/609


**Full Changelog**: https://github.com/actions/upload-artifact/compare/v3.2.0...v3.2.1


## actions/download-artifact

| Major | Latest Minor/Patch |
|-------|--------------------|
| v5 | v5.0.0 |

#### v5.0.0 Release Notes
## What's Changed
* Update README.md by @nebuk89 in https://github.com/actions/download-artifact/pull/407
* BREAKING fix: inconsistent path behavior for single artifact downloads by ID by @GrantBirki in https://github.com/actions/download-artifact/pull/416

## v5.0.0

### 🚨 Breaking Change

This release fixes an inconsistency in path behavior for single artifact downloads by ID. **If you're downloading single artifacts by ID, the output path may change.**

#### What Changed

Previously, **single artifact downloads** behaved differently depending on how you specified the artifact:

- **By name**: `name: my-artifact` → extracted to `path/` (direct)
- **By ID**: `artifact-ids: 12345` → extracted to `path/my-artifact/` (nested)

Now both methods are consistent:

- **By name**: `name: my-artifact` → extracted to `path/` (unchanged)
- **By ID**: `artifact-ids: 12345` → extracted to `path/` (fixed - now direct)

#### Migration Guide

##### ✅ No Action Needed If:

- You download artifacts by **name**
- You download **multiple** artifacts by ID
- You already use `merge-multiple: true` as a workaround

##### ⚠️ Action Required If:

You download **single artifacts by ID** and your workflows expect the nested directory structure.

**Before v5 (nested structure):**

```yaml
- uses: actions/download-artifact@v4
  with:
    artifact-ids: 12345
    path: dist
# Files were in: dist/my-artifact/
```

> Where `my-artifact` is the name of the artifact you previously uploaded

**To maintain old behavior (if needed):**

```yaml
- uses: actions/download-artifact@v5
  with:
    artifact-ids: 12345
    path: dist/my-artifact  # Explicitly specify the nested path
```

## New Contributors
* @nebuk89 made their first contribution in https://github.com/actions/download-artifact/pull/407

**Full Changelog**: https://github.com/actions/download-artifact/compare/v4...v5.0.0

| v4 | v4.3.0 |

#### v4.3.0 Release Notes
## What's Changed
* feat: implement new `artifact-ids` input by @GrantBirki in https://github.com/actions/download-artifact/pull/401
* Fix workflow example for downloading by artifact ID by @joshmgross in https://github.com/actions/download-artifact/pull/402
* Prep for v4.3.0 release by @robherley in https://github.com/actions/download-artifact/pull/404

## New Contributors
* @GrantBirki made their first contribution in https://github.com/actions/download-artifact/pull/401

**Full Changelog**: https://github.com/actions/download-artifact/compare/v4.2.1...v4.3.0


## actions/toolkit

| Major | Latest Minor/Patch |
|-------|--------------------|
| No releases found | |

## actions/github-script

| Major | Latest Minor/Patch |
|-------|--------------------|
| v8 | v8 |

#### v8 Release Notes
## What's Changed
* Update Node.js version support to 24.x by @salmanmkc in https://github.com/actions/github-script/pull/637
* README for updating actions/github-script from v7 to v8 by @sneha-krip in https://github.com/actions/github-script/pull/653

## ⚠️ Minimum Compatible Runner Version

**v2.327.1**  
[Release Notes](https://github.com/actions/runner/releases/tag/v2.327.1)

Make sure your runner is updated to this version or newer to use this release.
## New Contributors
* @salmanmkc made their first contribution in https://github.com/actions/github-script/pull/637
* @sneha-krip made their first contribution in https://github.com/actions/github-script/pull/653

**Full Changelog**: https://github.com/actions/github-script/compare/v7.1.0...v8.0.0

| v7 | v7.1.0 |

#### v7.1.0 Release Notes
## What's Changed
* Upgrade husky to v9 by @benelan in https://github.com/actions/github-script/pull/482
* Add workflow file for publishing releases to immutable action package by @Jcambass in https://github.com/actions/github-script/pull/485
* Upgrade IA Publish by @Jcambass in https://github.com/actions/github-script/pull/486
* Fix workflow status badges by @joshmgross in https://github.com/actions/github-script/pull/497
* Update usage of `actions/upload-artifact` by @joshmgross in https://github.com/actions/github-script/pull/512
* Clear up package name confusion by @joshmgross in https://github.com/actions/github-script/pull/514
* Update dependencies with `npm audit fix` by @joshmgross in https://github.com/actions/github-script/pull/515
* Specify that the used script is JavaScript by @timotk in https://github.com/actions/github-script/pull/478
* chore: Add Dependabot for NPM and Actions by @nschonni in https://github.com/actions/github-script/pull/472
* Define `permissions` in workflows and update actions by @joshmgross in https://github.com/actions/github-script/pull/531
* chore: Add Dependabot for .github/actions/install-dependencies by @nschonni in https://github.com/actions/github-script/pull/532
* chore: Remove .vscode settings by @nschonni in https://github.com/actions/github-script/pull/533
* ci: Use github/setup-licensed by @nschonni in https://github.com/actions/github-script/pull/473
* make octokit instance available as octokit on top of github, to make it easier to seamlessly copy examples from GitHub rest api or octokit documentations by @iamstarkov in https://github.com/actions/github-script/pull/508
* Remove `octokit` README updates for v7 by @joshmgross in https://github.com/actions/github-script/pull/557
* docs: add "exec" usage examples by @neilime in https://github.com/actions/github-script/pull/546
* Bump ruby/setup-ruby from 1.213.0 to 1.222.0 by @dependabot[bot] in https://github.com/actions/github-script/pull/563
* Bump ruby/setup-ruby from 1.222.0 to 1.229.0 by @dependabot[bot] in https://github.com/actions/github-script/pull/575
* Clearly document passing inputs to the `script` by @joshmgross in https://github.com/actions/github-script/pull/603
* Update README.md by @nebuk89 in https://github.com/actions/github-script/pull/610

## New Contributors
* @benelan made their first contribution in https://github.com/actions/github-script/pull/482
* @Jcambass made their first contribution in https://github.com/actions/github-script/pull/485
* @timotk made their first contribution in https://github.com/actions/github-script/pull/478
* @iamstarkov made their first contribution in https://github.com/actions/github-script/pull/508
* @neilime made their first contribution in https://github.com/actions/github-script/pull/546
* @nebuk89 made their first contribution in https://github.com/actions/github-script/pull/610

**Full Changelog**: https://github.com/actions/github-script/compare/v7...v7.1.0


## actions/stale

| Major | Latest Minor/Patch |
|-------|--------------------|
| v10 | v10.0.0 |

#### v10.0.0 Release Notes
## What's Changed

### Breaking Changes
* Upgrade to node 24 by @salmanmkc in https://github.com/actions/stale/pull/1279
Make sure your runner is on version v2.327.1 or later to ensure compatibility with this release. [Release Notes](https://github.com/actions/runner/releases/tag/v2.327.1)

### Enhancement
- Introducing sort-by option by @suyashgaonkar in https://github.com/actions/stale/pull/1254

### Dependency Upgrades
* Upgrade actions/publish-immutable-action from 0.0.3 to 0.0.4 by @dependabot[bot] in https://github.com/actions/stale/pull/1186
* Upgrade undici from 5.28.4 to 5.28.5 by @dependabot[bot] in https://github.com/actions/stale/pull/1201
* Upgrade @action/cache from 4.0.0 to 4.0.2 by @aparnajyothi-y in https://github.com/actions/stale/pull/1226
* Upgrade @action/cache from 4.0.2 to 4.0.3 by @suyashgaonkar in https://github.com/actions/stale/pull/1233
* Upgrade undici from 5.28.5 to 5.29.0 by @dependabot[bot] in https://github.com/actions/stale/pull/1251
* Upgrade form-data to bring in fix for critical vulnerability by @gowridurgad in https://github.com/actions/stale/pull/1277


### Documentation changes

- Changelog update for recent releases by @suyashgaonkar in https://github.com/actions/stale/pull/1224
- Permissions update in Readme by @ghadimir in https://github.com/actions/stale/pull/1248

## New Contributors
* @suyashgaonkar made their first contribution in https://github.com/actions/stale/pull/1224
* @GhadimiR made their first contribution in https://github.com/actions/stale/pull/1248
* @gowridurgad made their first contribution in https://github.com/actions/stale/pull/1277
* @salmanmkc made their first contribution in https://github.com/actions/stale/pull/1279

**Full Changelog**: https://github.com/actions/stale/compare/v9...v10.0.0

| v9 | v9.1.0 |

#### v9.1.0 Release Notes
## What's Changed
* Documentation update by @Marukome0743 in https://github.com/actions/stale/pull/1116
* Add workflow file for publishing releases to immutable action package by @Jcambass in https://github.com/actions/stale/pull/1179
* Update undici from 5.28.2 to 5.28.4 by @dependabot in https://github.com/actions/stale/pull/1150
* Update actions/checkout from 3 to 4 by @dependabot in https://github.com/actions/stale/pull/1091
* Update actions/publish-action from 0.2.2 to 0.3.0 by @dependabot in https://github.com/actions/stale/pull/1147
* Update ts-jest from 29.1.1 to 29.2.5 by @dependabot in https://github.com/actions/stale/pull/1175
* Update @actions/core from 1.10.1 to 1.11.1 by @dependabot in https://github.com/actions/stale/pull/1191
* Update @types/jest from 29.5.11 to 29.5.14 by @dependabot in https://github.com/actions/stale/pull/1193
* Update @actions/cache from 3.2.2 to 4.0.0 by @dependabot in https://github.com/actions/stale/pull/1194

## New Contributors
* @Marukome0743 made their first contribution in https://github.com/actions/stale/pull/1116
* @Jcambass made their first contribution in https://github.com/actions/stale/pull/1179

**Full Changelog**: https://github.com/actions/stale/compare/v9...v9.1.0


