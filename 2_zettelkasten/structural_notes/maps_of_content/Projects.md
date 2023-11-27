---
tags:
  - type/structure
  - structure/moc
aliases: 
summary: Map of content for all projects within my obsidian vault.
visual: "![[image.jpg]]"
created: 2023-11-26 20:40
updated: 2023-11-27 16:40
template-type: Structure
template-version: "1.8"
banner: "![[projects_banner.jpg]]"
---
# Projects


Projects are have a set goal and defined end-point. Project notes are stored within the project notes folder and serve as a planning, thinking and reference document for each project.. 

The Create Project button below will create a new note for a specific project. Projects use the [[Project Template]].

```button
name Create Project
type note(1_lifeOS/project_notes/TKTK, split) template
action Project Template
templater true
color green
```
## Project Notes
<!-- Main STRUCTURE of my content -->

```dataview
TABLE WITHOUT ID
	status as Status,
	link(file.link, title) as Title,
	summary as Summary,
	start_date as "Start Date"
FROM "1_lifeOS/project_notes" and -#structure/moc
WHERE !contains(file.path, "0_meta/templates")
SORT status DESC, file.ctime ASC
```
---
# Back Matter
## Source
<!-- Always keep a link to the source. --> 
- 

## Tasks
<!-- What remains to be done with this note? --> 
- 

## Questions
<!-- What remains for you to consider? --> 
- 

## Terms
<!-- Links to definition pages -->
- 

## References
<!-- Links to pages not referenced in the content -->