---
tags:
  - type/structure
  - structure/moc
aliases: 
summary: Projects are have a set goal and defined end-point. Project notes are stored within the project notes folder and serve as a planning, thinking and reference document for each project. The Create Project button below will create a new note for a specific project. Projects use the [[Project Template]].
visual: "![[image.jpg]]"
created: 2023-11-26 20:40
updated: 2023-11-27 18:58
template-type: Structure
template-version: "1.8"
banner: "![[projects_banner.jpg]]"
---
# Projects
>[!Note]
>`= this.summary`

```button
name Create Project
type note(1_lifeOS/project_notes/TKTK, split) template
action Project Template
templater true
color green
```
# Project Notes

## All Projects
<!-- Main STRUCTURE of my content -->

```dataview
TABLE WITHOUT ID
	status as Status,
	link(file.link, title) as Title,
	summary as Summary,
	jd_code as "JD Code",
	start_date as "Start Date"
FROM "1_lifeOS/project_notes" and -#structure/moc
WHERE !contains(file.path, "0_meta/templates")
SORT status DESC, file.ctime ASC
```

## Active Projects
```dataview
TABLE WITHOUT ID
	jd_code as "JD Code",
	link(file.link, title) as Title,
	summary as Summary,
	start_date as "Start Date"
FROM "1_lifeOS/project_notes" and -#structure/moc
WHERE !contains(file.path, "0_meta/templates") and status = "in_progress"
SORT jd_code asc
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