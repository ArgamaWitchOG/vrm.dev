---
title: "Unity Version"
date: 2020-10-07T17:19:08+09:00
weight: 1
tags: ["unity"]
---

## UniVRM-0.80.0 ～

We have discontinued support for Unity-2018.4LTS and updated the development version to Unity-2019.4LTS.

| Unity Version    | Note                                                                        |
|------------------|-----------------------------------------------------------------------------|
| Unity-2019.4 LTS | Current UniVRM development version                                          |
| Unity-2020.4 LTS | Current version for UniVRM UPM testing                                      |
| Unity-2021       | Please report any issues to [github](https://github.com/vrm-c/UniVRM/issues)|

## UniVRM-0.56.0 ～ 0.79.0

Support `Unity-2018.4` and above. `Unity-2019.4 LTS` is recommended.

| Unity Version    | Compatibility | Scripting Runtime Version | UPM | Note |
|------------------|---------------|---------------------------|-----|------|
| Unity-2017       | ×             |                           |     |      |
| Unity-2018.1     | ×             |                           |     |      |
| Unity-2018.2     | ×             |                           |     |      |
| Unity-2018.3     | △            | .Net4.X equivalent        |     | C#7.3. Probably working. Not confirmed yet |
| Unity-2018.4 LTS | ◎            | .Net4.X equivalent        |     | Current UniVRM development version |
| Unity-2019.1     | ○             | .Net4.X equivalent        |     |      |
| Unity-2019.2     | ○             |                           |     | .Net3.5 is removed. There is no need to set  `Scripting Runtime Version` to .Net4.X equivalent |
| Unity-2019.3     | ○            |                            |     | Support UPM from 2019.3.4f1 |
| Unity-2019.4 LTS | ◎            |                           | ○    | Current version for UniVRM-0.XX UPM testing |
| Unity-2020       | ○            |                            | ○   | Fixed Prefab behaviors, etc. in `UniVRM-0.69.0` |

## ～ UniVRM-0.55

* Support `Unity-5.6` and above

