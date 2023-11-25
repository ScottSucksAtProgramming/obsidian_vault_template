---
created: 2023-11-23 22:07
updated: 2023-11-24 20:41
tags:
  - type/note
  - source/self
banner: "![[quarterly_note_banner.jpg]]"
---
# {{date: [Quarter] Q YYYY}}

- <% tp.file.cursor() %>

---

### Monthly Notes
```dataview
LIST
FROM "1_lifeos/monthly_notes" 
WHERE file.cday.quarter = this.file.cday.quarter
SORT Tags asc
```