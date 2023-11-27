---
created: 2023-11-23 22:07
updated: 2023-11-27 15:42
tags:
  - type/note
  - source/self
banner: "![[daily_note_banner.jpg]]"
---
# <% moment(tp.file.title,'YYYY-MM-DD').format("dddd, MMMM DD, YYYY") %>

<< [[<% fileDate = moment(tp.file.title, 'YYYY-MM-DD').subtract(1, 'd').format('YYYY-MM-DD') %>|Yesterday]] | [[<% fileDate = moment(tp.file.title, 'YYYY-MM-DD').add(1, 'd').format('YYYY-MM-DD') %>|Tomorrow]] >>

- <% tp.file.cursor() %>


### Notes created today
```dataview
LIST
FROM "" 
WHERE file.cday = date("<%tp.date.now('YYYY-MM-DD')%>") 
SORT Tags asc
```

### Notes last touched today
```dataview
List FROM "" 
WHERE file.mday = date("<%tp.date.now('YYYY-MM-DD')%>") 
SORT file.mtime asc
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
- **Weekly Note:** [[<% tp.date.now("gggg-w ([Week] w)") %>]]
