# devedition 62.0b15

### Date of go-to-build: 2018-08-06

## Preflight tasks (pre go-to-build)
- none

## Build 1  

### Graphs
* [promote](https://tools.taskcluster.net/push-inspector/#/T3Km501wTbq0MnPmmI630A) T3Km501wTbq0MnPmmI630A
* [push](https://tools.taskcluster.net/push-inspector/#/XB4X39E0QZKte3FBEy25Og) XB4X39E0QZKte3FBEy25Og
* [ship](https://tools.taskcluster.net/push-inspector/#/SAn2ZlPyQ4iuVsvVTWty1Q) SAn2ZlPyQ4iuVsvVTWty1Q
```
export PROMOTE_TASK_ID=T3Km501wTbq0MnPmmI630A
export PUSH_TASK_ID=XB4X39E0QZKte3FBEy25Og
export SHIP_TASK_ID=SAn2ZlPyQ4iuVsvVTWty1Q
```


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [x] 2.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#push-artifacts-to-releases-directory)  - pushed to mirrors/releases
- [x] 3.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#ship-the-release)  - schedule the release for shipping
- [x] 4.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#obtain-sign-offs-for-changes)  - signoff in Balrog

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| nthomas  | 1 | [bug none](https://bugzil.la/none)        | [bouncer check](https://tools.taskcluster.net/groups/XB4X39E0QZKte3FBEy25Og/tasks/J_Xahf0xT9mffTlNmNGQPw/runs/0) 404's from CDN for 5 update urls, gone after a rerun | True | True |

