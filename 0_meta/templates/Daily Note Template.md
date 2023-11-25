---
created: 2023-11-23 22:07
updated: 2023-11-24 20:40
tags:
  - type/note
  - source/self
banner: "![[daily_note_banner.jpg]]"
---
# <% moment(tp.file.title,'YYYY-MM-DD').format("dddd, MMMM DD, YYYY") %>

<< [[<% fileDate = moment(tp.file.title, 'YYYY-MM-DD-dddd').subtract(1, 'd').format('YYYY-MM-DD-dddd') %>|Yesterday]] | [[<% fileDate = moment(tp.file.title, 'YYYY-MM-DD-dddd').add(1, 'd').format('YYYY-MM-DD-dddd') %>|Tomorrow]] >>

- <% tp.file.cursor() %>

---

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
