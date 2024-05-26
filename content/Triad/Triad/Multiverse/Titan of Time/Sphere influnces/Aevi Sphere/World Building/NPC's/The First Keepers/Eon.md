---
Name:
  - Eon
tags:
  - NPC
title: []
residence: "[[.md|Eon]]"
fc-date: 0001-01- 01
fc-calendar: Hjol
species:
  - Star
statblock: inline
image: "![[Person.jpg]]"
---
> [!infobox]
> ![[Person.jpg]]
> # `= this.file.name`
> | Titles | `= this.title` |
> | ---- | ---- |
> | Birthday | `$= String(dv.current()["fc-date"])` |
> | Age | `$= FantasyCalendarAPI.getCalendars()[0].current.year - String(dv.current()["fc-date"]).slice(0,4);` years old|
> | Residence | `= this.residence` |
# `= this.Name[0]`
*Short descriptor of character*
# Personality
# History
# Connections