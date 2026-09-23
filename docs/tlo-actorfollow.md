---
tags:
  - tlo
---
# `ActorFollow`

<!--tlo-desc-start-->
This plugin allows you to follow a player movement more precisely using MQ actors.
<!--tlo-desc-end-->

## Associated DataTypes
<!--tlo-datatypes-start-->
## [`ActorFollow`](datatype-actorfollow.md)
{% include-markdown "projects/mqactorfollow/datatype-actorfollow.md" start="<!--dt-desc-start-->" end="<!--dt-desc-end-->" trailing-newlines=false %} {{ readMore('projects/mqactorfollow/datatype-actorfollow.md') }}
:    <h3>Members</h3>
    {% include-markdown "projects/mqactorfollow/datatype-actorfollow.md" start="<!--dt-members-start-->" end="<!--dt-members-end-->" %}
    {% include-markdown "projects/mqactorfollow/datatype-actorfollow.md" start="<!--dt-linkrefs-start-->" end="<!--dt-linkrefs-end-->" %}
    <!--tlo-datatypes-end-->

## Examples
<!--tlo-examples-start-->
```txt
${ActorFollow.IsActive} - Plugin Loaded and ready
${ActorFollow.Status} - Status 0 = off , 1 = on , 2 = paused
${ActorFollow.WaypointsCount} - Total Number of current waypoints
${ActorFollow.IsFollowing} - BOOL Is following spawn
${ActorFollow.IsPaused} - BOOL Is paused
```
<!--tlo-examples-end-->
