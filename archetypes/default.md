---
title: "{{ .TranslationBaseName | replaceRE "^[0-9]{14}-" "" | replaceRE "-" " " | title }}"
post_highlight: ""
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
draft: false
type: post
---

{{< HeroInfo HeroName"" View"" Role"" BP"" DM"" Ticket"" Player"" CleanPlayerName"" WR"" League"" Match"" HeroTier"" TierLabel"" LaneImg"" LaneLabel"" >}} {{< /HeroInfo >}}
 
{{< OffensiveBuild build1""  build2"" build3"" build4"" build5"" build6"" >}} {{</ OffensiveBuild >}}  

{{< BalancedBuild build1""  build2"" build3"" build4"" build5"" build6"" >}} {{</ BalancedBuild >}}  

{{< RecommendedSpells SpellName1"" SpellImg1"" SpellName2"" SpellImg2"" >}} {{</ RecommendedSpells >}}   

{{< RecommendedEmblems EmblemName1"" EmblemImg1"" EmblemName2"" EmblemImg2"" >}} {{</ RecommendedEmblems >}}   

{{< ChampionSkills SkillDesc1"" SkillImg1""  SkillDesc2"" SkillImg2""  SkillDesc3"" SkillImg3""  SkillDesc4"" SkillImg4""  >}} {{</ ChampionSkills >}}
	

{{< ChampionAttributes >}}

	{{< ChampionAttributes/Config img"" Attrib"" AttribVal""  >}} 
	{{</ ChampionAttributes/Config >}}
	{{< ChampionAttributes/Config img"" Attrib"" AttribVal""  >}} 
	{{</ ChampionAttributes/Config >}}
	{{< ChampionAttributes/Config img"" Attrib"" AttribVal""  >}} 
	{{</ ChampionAttributes/Config >}}
	{{< ChampionAttributes/Config img"" Attrib"" AttribVal""  >}} 
	{{</ ChampionAttributes/Config >}}
	{{< ChampionAttributes/Config img"" Attrib"" AttribVal""  >}} 
	{{</ ChampionAttributes/Config >}}
	{{< ChampionAttributes/Config img"" Attrib"" AttribVal""  >}} 
	{{</ ChampionAttributes/Config >}}
	{{< ChampionAttributes/Config img"" Attrib"" AttribVal""  >}} 
	{{</ ChampionAttributes/Config >}}
	{{< ChampionAttributes/Config img"" Attrib"" AttribVal""  >}} 
	{{</ ChampionAttributes/Config >}}
	{{< ChampionAttributes/Config img"" Attrib"" AttribVal""  >}} 
	{{</ ChampionAttributes/Config >}}
	{{< ChampionAttributes/Config img"" Attrib"" AttribVal""  >}} 
	{{</ ChampionAttributes/Config >}}
	
	
{{</ ChampionAttributes >}}


{{< FightingAbility >}}

	{{< FightingAbility/Config  Percentage""Label"" >}} 
	{{</ FightingAbility/Config >}}		
	{{< FightingAbility/Config  Percentage""Label"" >}} 
	{{</ FightingAbility/Config >}}
	{{< FightingAbility/Config  Percentage""Label"" >}} 
	{{</ FightingAbility/Config >}}
	
{{< FightingAbility >}}

{{< GetStory Story"" >}}  {{</ GetStory >}}

{{< StrongAgainst >}}

	{{< StrongAgainst/Config href"" HeroName"">}} {{</ StrongAgainst/Config >}}
	{{< StrongAgainst/Config href"" HeroName"">}} {{</ StrongAgainst/Config >}}
	{{< StrongAgainst/Config href"" HeroName"">}} {{</ StrongAgainst/Config >}}
	{{< StrongAgainst/Config href"" HeroName"">}} {{</ StrongAgainst/Config >}}
	{{< StrongAgainst/Config href"" HeroName"">}} {{</ StrongAgainst/Config >}}
	
{{</ StrongAgainst >}}

{{< WeakAgainst >}}

	{{< WeakAgainst/Config href"" HeroName"">}} {{</ WeakAgainst/Config >}}
	{{< WeakAgainst/Config href"" HeroName"">}} {{</ WeakAgainst/Config >}}
	{{< WeakAgainst/Config href"" HeroName"">}} {{</ WeakAgainst/Config >}}
	{{< WeakAgainst/Config href"" HeroName"">}} {{</ WeakAgainst/Config >}}
	{{< WeakAgainst/Config href"" HeroName"">}} {{</ WeakAgainst/Config >}}
	
{{</ WeakAgainst >}}


