---
tags:
  - plugin
resource_link: "https://www.redguides.com/community/resources/mqactorfollow.3343/"
support_link: "https://www.redguides.com/community/threads/mqactorfollow.97292/"
repository: "https://github.com/peonMQ/MQActorFollow"
authors: "ProjectEon"
tagline: "This plugin allows you to follow a player movement more precisely using MQ actors."
acknowledgements: "Inspiration from MQ2NetAdvPath and MQ2AdvPath as well as MQ2Nav"
---

# MQActorFollow

<!--desc-start-->
This plugin allows you to follow a player movement more precisely using MQ actors. Both the follower and the player being followed must run the plugin.
<!--desc-end-->

## Getting Started

```txt
/plugin MQActorFollow
```

### Commands

<a href="cmd-actfollow/">
{% 
  include-markdown "projects/mqactorfollow/cmd-actfollow.md" 
  start="<!--cmd-syntax-start-->" 
  end="<!--cmd-syntax-end-->" 
%}
</a>
:    {% include-markdown "projects/mqactorfollow/cmd-actfollow.md" 
        start="<!--cmd-desc-start-->" 
        end="<!--cmd-desc-end-->" 
        trailing-newlines=false 
     %} {{ readMore('projects/mqactorfollow/cmd-actfollow.md') }}

### TLO

#### [ActorFollow](tlo-actorfollow.md)
{% include-markdown "projects/mqactorfollow/tlo-actorfollow.md" start="<!--tlo-desc-start-->" end="<!--tlo-desc-end-->" trailing-newlines=false %} {{ readMore('projects/mqactorfollow/tlo-actorfollow.md') }}

{% include-markdown "projects/mqactorfollow/datatype-actorfollow.md" start="<!--dt-members-start-->" end="<!--dt-members-end-->" %}
{% include-markdown "projects/mqactorfollow/datatype-actorfollow.md" start="<!--dt-linkrefs-start-->" end="<!--dt-linkrefs-end-->" %}

## Authors

* **ProjectEon** - *Initial work*

## Acknowledgments

* Inspiration from MQ2NetAdvPath and MQ2AdvPath as well as MQ2Nav
