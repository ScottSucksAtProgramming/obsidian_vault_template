---
created: 2023-11-23 22:07
updated: 2023-11-24 20:41
tags:
  - type/note
  - source/self
banner: "![[monthly_note_banner.jpg]]"
---
# {{date: MMMM gggg}}

- <% tp.file.cursor() %>

---

### Weekly Notes
```dataview
LIST
FROM "1_lifeos/weekly_notes" 
WHERE file.cday.month = this.file.cday.month
SORT Tags asc
```
