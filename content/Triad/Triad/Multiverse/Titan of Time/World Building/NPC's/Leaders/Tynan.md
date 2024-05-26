---
Name:
  - Tynan
tags:
  - NPC
title: 
residence: "[[../../../Aevi Sphere/Places/Aevi Sphere.md|Aevi]]"
fc-date: 0000-00-00
fc-category: Birthday
fc-calendar: Hjol
species:
  - "[[Species]]"
statblock: inline
image: "![[Person.jpg]]"
---
> [!infobox]
> ![[Person.jpg]]
> # `= this.file.name`
> | Titles | `= this.title` |
> | ---- | ---- |
> | Birthday | `$= String(dv.current()["fc-date"])` |
> | Full name | `= this.Name[1]`|
> | Age | `$= FantasyCalendarAPI.getCalendars()[0].current.year - String(dv.current()["fc-date"]).slice(0,4);` years old|
> | Residence | `= this.residence` |
# `= this.Name[1]`
*Short descriptor of character*
# Personality
# History
# Connections
<% tp.config.target_file %>