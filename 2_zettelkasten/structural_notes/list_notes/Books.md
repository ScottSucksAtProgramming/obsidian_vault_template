---
tags:
  - type/structure
  - structure/list
aliases:
  - read list
  - Read
  - Read List
summary: This list contains books that are mentioned throughout this vault or used as a source for other notes.
visual: "![[image.jpg]]"
created: 2023-11-24 20:33
updated: 2023-11-27 19:01
template-type: Structure
template-version: "1.8"
banner: "![[library_banner.jpg]]"
---

# Books
>[!Note]
>`= this.summary`

```button
name Create Book
type note(2_zettelkasten/bibliographical_notes/book_notes/TKTK, split) template
action Book Template
templater true
color green
```

# All Books

<!-- Main STRUCTURE of my content -->
```dataview
TABLE WITHOUT ID
	status as Status,
	"![|60](" + cover_url + ")" as Cover,
	link(file.link, title) as Title,
	author as Author,
	join(list(publisher, publish_date)) as Publisher
FROM #type/book 
WHERE !contains(file.path, "0_meta/templates")
SORT status DESC, file.ctime ASC
```

# Unread Books

```dataview
TABLE WITHOUT ID
	status as Status,
	"![|60](" + cover_url + ")" as Cover,
	link(file.link, title) as Title,
	author as Author,
	join(list(publisher, publish_date)) as Publisher
FROM #type/book 
WHERE !contains(file.path, "0_meta/templates")
WHERE status = "unread"
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
- [[Books (Unread)|Unread Books]]