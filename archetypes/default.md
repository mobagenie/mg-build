---
title: "{{ .TranslationBaseName | replaceRE "^[0-9]{14}-" "" | replaceRE "-" " " | title }}"
post_highlight: "Player:  † WR: % Match:   Tier:  Tier Lane:  Lane"
author: MobaGenie
date: {{ .Date }}
PublishDate: {{ .Date }}
Lastmod: {{ .Date }}
slug: {{substr ( lower .File.BaseFileName  | replaceRE "^[0-9]{14}-" "" | replaceRE "," "") 0 80 }}
filename: ""
categories: 
- Build 
- Mobile Legends
tags: 
- ""
- ""
playername: ""
cleanplayername: "{{substr ( lower .File.BaseFileName  | replaceRE "^[0-9]{14}-" "" | replaceRE "," "") 0 80 }}"
heroname: ""
images: ../p/images/buildk/.png
Player="" 
WR="" 
League="" 
Match="" 
draft: false
type: post
proplayer: false
team: 
ytvideoid: 
ign: 
yt: 
fb: 
ig: 
tw: 
bio: 
---

{{< HeroInfo HeroName="" Role="" BP="" DM="" Ticket="" HeroTier="" TierLabel="" LaneImg="" LaneLabel="" >}} {{< /HeroInfo >}}
 
{{< OffensiveBuild build1=""  build2="" build3="" build4="" build5="" build6="" >}} {{</ OffensiveBuild >}}  

{{< BalancedBuild build1=""  build2="" build3="" build4="" build5="" build6="" >}} {{</ BalancedBuild >}}  


