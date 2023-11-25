---
created: 2023-11-23 22:07
updated: 2023-11-24 20:41
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
FROM "1_lifeos/quarterly_notes" 
WHERE file.cday.year = this.file.cday.year
SORT Tags asc
```
