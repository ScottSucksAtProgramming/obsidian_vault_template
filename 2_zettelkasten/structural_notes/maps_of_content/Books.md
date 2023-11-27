---
tags:
  - type/structure
  - structure/index
aliases:
  - read list
  - Read
  - Read List
summary: List of all books contained in the vault.
visual: "![[image.jpg]]"
created: 2023-11-24 20:33
updated: 2023-11-27 15:00
template-type: Structure
template-version: "1.8"
banner: "![[library_banner.jpg]]"
---

# List of Books

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