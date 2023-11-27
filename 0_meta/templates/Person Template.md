---
tags: type/person role/tk
aliases: 
birth: 
death: 
company: 
location: 
title: 
email: 
website: 
visual: "![[image.jpg|250]]"
created: 2023-11-26 19:32
updated: 2023-11-27 15:24
template-type: Person
template-version: "1.0"
banner: "![[person_banner.jpg]]"
---

# <% tp.file.title %>
<% await tp.file.move("/1_lifeOS/people_notes/" + tp.file.title) %>
<% tp.frontmatter.visual %>
- 


## Meetings
```dataview
TABLE
file.cday AS "Created",
summary AS "Summary"
FROM "2_zettelkasten/literature_notes/meeting_notes"
WHERE contains(file.outlinks, this.file.link)
SORT file.cday DESC
```


---
# Back Matter
## Source
<!-- Always keep a link to the source- --> 
- 

## Tasks
<!-- What remains to be done with this note? --> 
- 

## Questions
<!-- What remains for you to consider? -->
- 

## References 
<!-- Links to pages not referenced in the content -->
- [[People]] - Map Of Content