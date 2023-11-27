---
created: 2023-11-23 22:07
updated: 2023-11-26 19:26
tags:
  - type/note
  - source/self
banner: "![[yearly_note_banner.jpg]]"
---
# {{date: YYYY}}

- <% tp.file.cursor() %>

---

### Quarterly Notes
```dataview
LIST
FROM "1_lifeOS/quarterly_notes" 
WHERE file.cday.year = this.file.cday.year
SORT Tags asc
```
