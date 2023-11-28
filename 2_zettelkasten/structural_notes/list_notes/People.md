---
tags:
  - type/structure
  - structure/moc
aliases: 
summary: People who's relationships are important to me are given notes which maintain important information about them. This Map of Content collects all the people and lists them. The Create Person below will create a new note for a specific person. A person uses the [[Person Template]].
visual: "![[image.jpg]]"
created: 2023-11-24 20:33
updated: 2023-11-27 19:00
template-type: Structure
template-version: "1.8"
banner: "![[people_banner.jpg]]"
---
# People
>[!Note]
>`= this.summary`

```button
name Create Person
type note(1_lifeOS/people_notes/TKTK, split) template
action Person Template
templater true
color green
```
# People Notes

## Family
- [[Kostolni, Scott|Scott Kostolni]]
- [[Brandt, Kristina|Tina Brandt]]

## Friends

## [[Wantagh-Levittown VAC]]

## [[Stony Brook EMS]]

## Family Friends
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

### Templates Not Listed in this Map of Content
```dataview
LIST
FROM "1_lifeOS/people_notes"
WHERE !contains(this.file.outlinks, file.link)
sort file.name ASC
```