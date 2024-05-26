---
Name: []
tags:
  - Player
Gender: 
residence: 
fc-date: 2160-1-1
fc-category: Birthday
fc-calendar: Hjol
species:
  - "[[../../Races/Timaeth]]"
statblock: inline
image: "![[Person.jpg]]"
Charactersheet: 
---
> [!infobox]
> ![[Person.jpg]]
> # `= this.file.name`
> | Gender | `= this.Gender` |
> | ---- | ---- |
> | Birthday | `$= String(dv.current()["fc-date"])` |
> | Age | `$= FantasyCalendarAPI.getCalendars()[0].current.year - String(dv.current()["fc-date"]).slice(0,4);` years old|
> | Residence | `= this.residence` |
# `= this.Name[0]`
*Short Discription*
# Personality
# History
# Connections



%%[object Object]%%
<%tp.config.target_file tp%>