---
title: "{{ .TranslationBaseName | replaceRE "^[0-9]{14}-" "" | replaceRE "-" " " | title }}"
post_highlight: ""
author: MobaGenie
date: {{ .Date }}
PublishDate: {{ .Date }}
Lastmod: {{ .Date }}
slug: {{substr ( lower .File.BaseFileName  | replaceRE "^[0-9]{14}-" "" | replaceRE "," "") 0 80 }}
categories: 
- Profile 
- Player
- Biodata
tags: 
- "{{substr ( lower .File.BaseFileName  | replaceRE "^[0-9]{14}-" "" | replaceRE "," "") 0 80 }}"
- "{{ .TranslationBaseName | replaceRE "^[0-9]{14}-" "" | replaceRE "-" " " | title }}"
- Profile 
- Player
- Biodata
playername: "{{ .TranslationBaseName | replaceRE "^[0-9]{14}-" "" | replaceRE "-" " " | title }}"
cleanplayername: "{{substr ( lower .File.BaseFileName  | replaceRE "^[0-9]{14}-" "" | replaceRE "," "") 0 80 }}"
images: https://res.cloudinary.com/drlhixyyd/image/fetch/https://cdn2-build.mobagenie.my.id/p/images/banner/player/full/{{substr ( lower .File.BaseFileName  | replaceRE "^[0-9]{14}-" "" | replaceRE "," "") 0 80 }}.jpg
draft: false
layout: profile
type: profile
profileplayer: true
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

{{< profile/player/playerinfo name="{{ .TranslationBaseName | replaceRE "^[0-9]{14}-" "" | replaceRE "-" " " | title }}" cleanname="{{substr ( lower .File.BaseFileName  | replaceRE "^[0-9]{14}-" "" | replaceRE "," "") 0 80 }}" bio="" >}} {{</ profile/player/playerinfo >}}