# firefox 52.7.2esr

### Date of go-to-build: 2018-03-15

## Preflight tasks (pre go-to-build)
- none

## Build 1  

### Graphs
* [promote](https://tools.taskcluster.net/push-inspector/#/JF41dvVxTy2q4RjgpBlU4A) JF41dvVxTy2q4RjgpBlU4A
* [push](https://tools.taskcluster.net/push-inspector/#/IxtbNIB4Qom-JGGMD4AezA) IxtbNIB4Qom-JGGMD4AezA


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [x] 2.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/historic_relpro.md#2-push-to-releases-dir-mirrors)  - pushed to mirrors/releases
- [x] 3.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/historic_relpro.md#4-publish-release)  - schedule the release for shipping
- [x] 4.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/historic_relpro.md#3-signoffs)  - signoff in Balrog

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| asasaki  | 1 | [bug none](https://bugzil.la/none)        | [funsize] Publish to Balrog linux chunk 1 for 52.7.1esr timeout | True | False |
| nthomas  | 2 | [bug none](https://bugzil.la/none)        | update verify failures for it on esr-localtest from the 52.7.1 special casing, Changed the rule to affect 'esr' instead of 'esr*' and rerun | True | False |

