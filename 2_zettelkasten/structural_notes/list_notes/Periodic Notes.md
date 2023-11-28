---
tags:
  - type/structure
  - structure/list
aliases: 
summary: Periodic notes are used for planning and documenting my life over time. [[Periodic Notes#Daily Notes|Daily Notes]] are the most common entry into the vault.
visual: "![[image.jpg]]"
created: 2023-11-24 20:33
updated: 2023-11-27 18:58
template-type: Structure
template-version: "1.8"
banner: 
---

# Periodic Notes
>[!Note]
>`= this.summary`

<!-- Main STRUCTURE of my content -->
# Yearly Notes
```dataview
LIST
FROM "1_lifeOS/yearly_notes" 
WHERE !contains(file.path, "0_meta/templates")
SORT status DESC, file.ctime ASC
```


# Quarterly Notes
```dataview
LIST
FROM "1_lifeOS/quarterly_notes" 
WHERE !contains(file.path, "0_meta/templates")
SORT status DESC, file.ctime ASC
```

# Monthly Notes
```dataview
LIST
FROM "1_lifeOS/monthly_notes" 
WHERE !contains(file.path, "0_meta/templates")
SORT status DESC, file.ctime ASC
```

# Weekly Notes
```dataview
LIST
FROM "1_lifeOS/weekly_notes" 
WHERE !contains(file.path, "0_meta/templates")
SORT status DESC, file.ctime ASC
```

# Daily Notes
```dataview
LIST
FROM "1_lifeOS/daily_notes" 
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
-

### Templates Not Listed in this Map of Content
```dataview
LIST
FROM "1_lifeOS/daily_notes" or "1_lifeOS/weekly_notes" or "1_lifeOS/monthly_notes" or "1_lifeOS/quarterly_notes" or "1_lifeOS/yearly_notes"
WHERE !contains(this.file.outlinks, file.link)
sort file.name ASC
```