# firefox 63.0b12

### Date of go-to-build: 2018-10-04

## Preflight tasks (pre go-to-build)
- none

## Build 2  

### Graphs
* [promote](https://tools.taskcluster.net/push-inspector/#/X4r-IGwTSAucognWGrRwHw) X4r-IGwTSAucognWGrRwHw
* [push](https://tools.taskcluster.net/push-inspector/#/YOF9mLY1Tq2ecHuiJovB0Q) YOF9mLY1Tq2ecHuiJovB0Q
* [ship](https://tools.taskcluster.net/push-inspector/#/OYnBiPXcRW6K_GLw-YIr6w) OYnBiPXcRW6K_GLw-YIr6w
```
export PROMOTE_TASK_ID=X4r-IGwTSAucognWGrRwHw
export PUSH_TASK_ID=YOF9mLY1Tq2ecHuiJovB0Q
export SHIP_TASK_ID=OYnBiPXcRW6K_GLw-YIr6w
```


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [x] 2.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#push-artifacts-to-releases-directory)  - pushed to mirrors/releases
- [x] 3.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#ship-the-release)  - schedule the release for shipping
- [x] 4.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#obtain-sign-offs-for-changes)  - signoff in Balrog

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| asasaki  | 1 | [bug 1496480](https://bugzil.la/1496480)        | thunderbird fix broke firefox update verify config | True | False |
| asasaki  | 2 | [bug none](https://bugzil.la/none)        | snap push failed | True | False |

## Build 1  :bomb: _aborted release. starting new build num_ :bomb: 

### Graphs
* [promote](https://tools.taskcluster.net/push-inspector/#/F9bphS8MT-eHPnPShOEGUg) F9bphS8MT-eHPnPShOEGUg
* [push](https://tools.taskcluster.net/push-inspector/#/O96Ai7RuTdqHD7Gwn4r5fA) O96Ai7RuTdqHD7Gwn4r5fA
```
export PROMOTE_TASK_ID=F9bphS8MT-eHPnPShOEGUg
export PUSH_TASK_ID=O96Ai7RuTdqHD7Gwn4r5fA
```


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [ ] 2.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#push-artifacts-to-releases-directory)  - pushed to mirrors/releases
- [ ] 3.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#ship-the-release)  - schedule the release for shipping
- [ ] 4.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#obtain-sign-offs-for-changes)  - signoff in Balrog

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| asasaki  | 1 | [bug 1496480](https://bugzil.la/1496480)        | thunderbird fix broke firefox update verify config | False | True |

