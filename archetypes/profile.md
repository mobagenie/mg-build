---
title: "Profile {{ .TranslationBaseName | replaceRE "^[0-9]{14}-" "" | replaceRE "-" " " | title }}"
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
aka: ""
images: https://res.cloudinary.com/drlhixyyd/image/fetch/https://cdn2-build.mobagenie.my.id/p/images/banner/player/full/{{substr ( lower .File.BaseFileName  | replaceRE "^[0-9]{14}-" "" | replaceRE "," "") 0 80 }}.jpg
draft: false
layout: profile
type: profile
profileplayer: true
proplayer: false
team: 
exteam: "" 
achievement: ""
allachievement: ""
age: ""
birthplace: ""
nationality: ""
ytvideoid: ""
ign: ""
yt: ""
fb: ""
ig: ""
tw: ""
shortbio: ""
---

{{< profile/player/playerinfo >}} {{</ profile/player/playerinfo >}}

{{< profile/player/playerbio >}}

{{< profile/player/playerbiocontent 

bioid = "1" 

biotitle = "#1" 

biocontent = ""

>}}

{{</ profile/player/playerbio >}}
 
{{< profile/player/playersocmed >}}

{{< profile/player/playersocmedcontent socmed="yt" >}} 
{{< profile/player/playersocmedcontent socmed="fb" >}} 
{{< profile/player/playersocmedcontent socmed="ig" >}} 
{{< profile/player/playersocmedcontent socmed="tw" >}} 

{{</ profile/player/playersocmed >}}

{{< profile/player/playerlatestvideo >}}

{{< profile/player/playerlatestbuild >}}