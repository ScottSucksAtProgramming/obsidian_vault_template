---
tags:
  - type/structure
  - structure/list
aliases: 
summary: Meetings are discussions with other people where information is exchanged and collected. Meeting notes are stored within the literature notes folder as they contain information collected from outside sources which may later be turned into permanent notes. The New Meeting button below will create a new note for a specific meeting. Meetings use the [[Meeting Note Template]].
visual: "![[image.jpg]]"
created: 2023-11-24 20:33
updated: 2023-11-27 19:06
template-type: Structure
template-version: "1.8"
banner: "![[meeting_moc_banner.jpg]]"
---
# Meetings
>[!Note]
>`= this.summary`

```button
name Create Meeting Note
type note(2_zettelkasten/literature_notes/meeting_notes/TKTK, split) template
action Meeting Note Template
templater true
color green
```
# Meeting Notes


```dataview
TABLE file.cday as Created, summary
FROM "2_zettelkasten/literature_notes/meeting_notes" and -#structure/moc
SORT file.cday DESC
```
<!-- Main STRUCTURE of my content -->


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
- 