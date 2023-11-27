---
created: 2023-11-23 22:07
updated: 2023-11-26 19:26
tags:
  - type/note
  - source/self
banner: "![[weekly_note_banner.jpg]]"
---
# {{date: gggg [Week] ww}}

- <% tp.file.cursor() %>

---

### Daily Notes
```dataview
LIST
FROM "1_lifeOS/daily_notes" 
WHERE file.cday > date("<% tp.date.weekday("YYYY-MM-DD", 0) %>") and file.cday < date("<% tp.date.weekday("YYYY-MM-DD", 7) %>")
SORT Tags asc
```
