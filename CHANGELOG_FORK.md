# Changelog (Fork)

## [1.3.0] - 2026-08-14

* [5c7034e](https://github.com/mattykay/k3s-ansible/commit/5c7034e69575a9b66a70783b4ca720aa063d1b64) - Merge remote-tracking branch 'upstream/main' (2026-08-14)
* [8a2d1e2](https://github.com/mattykay/k3s-ansible/commit/8a2d1e2e2db4e9131ace54213cc57da32e9cacab) - Add agent logs on failure (#556) (2026-08-13)
* [445cecb](https://github.com/mattykay/k3s-ansible/commit/445cecb4231792d4cb5facc1b76a40b423c8851b) - Wrap api_endpoint with ansible.utils.ipwrap for IPv6 compatibility (#550) (2026-08-13)
* [cb38fd9](https://github.com/mattykay/k3s-ansible/commit/cb38fd92e38514fbda445fea9b08cf6b5f76d533) - feat: add firewall variable (#552) (2026-08-13)
* [5f98ca7](https://github.com/mattykay/k3s-ansible/commit/5f98ca7a23a3e5ff5574f8fff3cd4531076e32eb) - Increase wait time for upgrades in testing (#554) (2026-08-13)

## [1.2.15] - 2026-08-11

* [493c93a](https://github.com/mattykay/k3s-ansible/commit/493c93a496ec2e893f56c7a2570ee7ec84f1406e) - Merge remote-tracking branch 'upstream/main' (2026-08-11)
* [35b8377](https://github.com/mattykay/k3s-ansible/commit/35b8377f74befeda237279d09d17dcc4d0c781ac) - fix(roles): fix check mode on clean install (#547) (2026-08-11)
* [9cdd1dd](https://github.com/mattykay/k3s-ansible/commit/9cdd1dd47ce2356afd5dd66ccc76f5e860f8cfb8) - fix: read hostname from ansible_facts in the TLS SAN condition (#548) (2026-08-10)

## [1.2.14] - 2026-07-15

* [fe2a125](https://github.com/mattykay/k3s-ansible/commit/fe2a125503b43268cd3700e29552c283d1654dcf) - Merge remote-tracking branch 'upstream/main' (2026-07-15)
* [e5ec2f0](https://github.com/mattykay/k3s-ansible/commit/e5ec2f07b462e484c5b66eb5b142c0d7dfc72be9) - fix: apply k3s version bumps declaratively through site.yml (#544) (2026-07-15)
* [6688377](https://github.com/mattykay/k3s-ansible/commit/66883771ba96ef0b3bb4c24fbc43ae17d8361053) - Bump actions/setup-python from 6.2.0 to 6.3.0 in the action-deps group (#545) (2026-07-14)

## [1.2.13] - 2026-07-07

* [0761739](https://github.com/mattykay/k3s-ansible/commit/076173957cdb3835879e321c8b31d9d60594aefa) - Merge remote-tracking branch 'upstream/main' (2026-07-07)
* [6f87b64](https://github.com/mattykay/k3s-ansible/commit/6f87b64f1d2293248189620fe3f584ef0c146d6a) - fix: use failed_when instead of ignore_errors for version detection (#543) (2026-07-06)
* [33b0ca9](https://github.com/mattykay/k3s-ansible/commit/33b0ca9fa0c234314beda63b932f61e79f5a8d76) - fix(raspberrypi): run detection commands in check mode (#542) (2026-07-06)

## [1.2.12] - 2026-06-23

* [fe3074c](https://github.com/mattykay/k3s-ansible/commit/fe3074c7726291fedd3a595fb2eb0ccb404c4f5a) - Merge remote-tracking branch 'upstream/main' (2026-06-23)
* [de30fcd](https://github.com/mattykay/k3s-ansible/commit/de30fcd06ccf256f4cd0abb120e527908ebe89ba) - Bump the action-deps group across 1 directory with 3 updates (#539) (2026-06-22)

## [1.2.11] - 2026-06-19

* [23b6d3a](https://github.com/mattykay/k3s-ansible/commit/23b6d3a4ac234c12a7d35b7d1779814dda87c90b) - Merge remote-tracking branch 'upstream/main' (2026-06-19)
* [e8af759](https://github.com/mattykay/k3s-ansible/commit/e8af759240c6c4069560e05a1f99681c17a3e89a) - Remove N/A label (2026-06-18)
* [278b6bb](https://github.com/mattykay/k3s-ansible/commit/278b6bbbfe81e8f02d1c50e81681c35a390d2432) - Add dependabot bumps for GHA versions (2026-06-18)

## [1.2.10] - 2026-06-09

* [c839d15](https://github.com/mattykay/k3s-ansible/commit/c839d15e67140eabf753b6953741f6d08da3d533) - docs(changelog): link fork commit references (2026-05-29)
* [4cb2dbc](https://github.com/mattykay/k3s-ansible/commit/4cb2dbc13a149d09975acd3c9bd3e2783b8b1ef7) - Merge branch 'main' of github.com:mattykay/k3s-ansible (2026-05-29)
* [a9a7db4](https://github.com/mattykay/k3s-ansible/commit/a9a7db49b4e6f52080c0caeef205ddb110790c2d) - fix(ci): harden autopilot release retries and tag handling (2026-05-29)
* [da9ab71](https://github.com/mattykay/k3s-ansible/commit/da9ab715598e673a12a0b5bde4e06e6ad261cf59) - fix(ci): detect upstream sync changes before release workflow steps (2026-05-29)

## [1.2.9] - 2026-05-29

* [8fafce9](https://github.com/mattykay/k3s-ansible/commit/8fafce9) - Merge remote-tracking branch 'upstream/main' (2026-05-29)
* [a05f5b5](https://github.com/mattykay/k3s-ansible/commit/a05f5b5) - Invert directives when importing ref. playbook (#524) (2026-05-27)
* [611ca0b](https://github.com/mattykay/k3s-ansible/commit/611ca0b) - Fix existing token retrieval for k3s server (#534) (2026-05-27)
* [d1aab4d](https://github.com/mattykay/k3s-ansible/commit/d1aab4d) - Feature/oracle linux11 (#532) (2026-05-27)
* [0457b3b](https://github.com/mattykay/k3s-ansible/commit/0457b3b) - fix(ci): harden autopilot workflow supply chain (2026-05-17)
* [2624577](https://github.com/mattykay/k3s-ansible/commit/2624577) - Merge pull request #525 from cwayne18/pin-actions-to-sha (2026-03-27)
* [4acc4c7](https://github.com/mattykay/k3s-ansible/commit/4acc4c7) - Pin GH Actions to commit sha (2026-03-27)

## [1.2.8] - 2026-03-15

* [45ce65d](https://github.com/mattykay/k3s-ansible/commit/45ce65d) - Merge branch 'main' of github.com:mattykay/k3s-ansible (2026-03-15)
* [55d665d](https://github.com/mattykay/k3s-ansible/commit/55d665d) - fix: added logic to handle merge conflict on galaxy.yml (2026-03-15)

## [1.2.7] - 2026-03-07

* [905f7d0](https://github.com/mattykay/k3s-ansible/commit/905f7d0) - fix(galaxy): updated homepage/repo metadata to redirect to this repo, leaving other issues/docs as upstream. (2026-03-07)
* [7417f1d](https://github.com/mattykay/k3s-ansible/commit/7417f1d) - Merge branch 'main' of github.com:mattykay/k3s-ansible (2026-03-07)
* [f9d02fe](https://github.com/mattykay/k3s-ansible/commit/f9d02fe) - feat(CHANGELOG_FORK): added changelog generation. (2026-03-07)
* [58cd3bb](https://github.com/mattykay/k3s-ansible/commit/58cd3bb) - docs(README_FORK): fixed typo. (2026-03-07)
