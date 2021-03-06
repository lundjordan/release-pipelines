# devedition 60.0b2

### Date of go-to-build: 2018-03-05

## Preflight tasks (pre go-to-build)
- [ ] 1. due:2018-03-05 - [bug 1443104](https://bugzil.la/1443104): Make sure all bouncer related issues are fixed in-tree and hacks removed the bouncerscript side.
- [x] 2. due:2018-03-08 - [bug 1433459](https://bugzil.la/1433459): Bouncer alias fix that Johan pushed https://bugzilla.mozilla.org/show_bug.cgi?id=1433459#c43 needs to get to beta before GTB

## Build 1  

### Graphs
* [promote](https://tools.taskcluster.net/push-inspector/#/JFxl2VVYQpiUeQBZ3mw8dQ) JFxl2VVYQpiUeQBZ3mw8dQ
* [push](https://tools.taskcluster.net/push-inspector/#/QWY7RPePQJuC-lxa521DjQ) QWY7RPePQJuC-lxa521DjQ
* [ship](https://tools.taskcluster.net/push-inspector/#/duqIu4i_TJWIOWLXdg2AEg) duqIu4i_TJWIOWLXdg2AEg


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [x] 2.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#push-artifacts-to-releases-directory)  - pushed to mirrors/releases
- [x] 3.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#ship-the-release)  - publish release tasks
- [x] 4.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#obtain-sign-offs-for-changes)  - signoff in Balrog

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| bhearsum  | 1 | [bug none](https://bugzil.la/none)        | update verify config failed because we were missing tags on mozilla-beta after we changed the watersheds in https://hg.mozilla.org/releases/mozilla-beta/rev/23c473f89743 | True | False |
| mihaitabara  | 2 | [bug 1444131](https://bugzil.la/1444131)        | boucner check fails for apparently whitespace typo in provisioning partials | True | False |

