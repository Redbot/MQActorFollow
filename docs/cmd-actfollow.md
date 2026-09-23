---
tags:
  - command
---

# /actfollow

## Syntax

<!--cmd-syntax-start-->
```eqcommand
/actfollow {<pc name> | <spawn id>}
/actfollow {pause | resume | off}
/actfollow ui
```
<!--cmd-syntax-end-->

## Description

<!--cmd-desc-start-->
This plugin allows you to follow a player movement more precisely using MQ actors. Both the follower and the player being followed must run the plugin.
<!--cmd-desc-end-->

## Options

``<pc name>``
:   follow by pc name

    !!! example "`/actfollow JohnDoe`"

``<spawn id>``
:   follow by pc spawn id

    !!! example "`/actfollow 123`"

``pause``
:   Paused following.

``resume``
:   Resumed following.

``off``
:   Stop following.

``ui``
:   toggles ui
