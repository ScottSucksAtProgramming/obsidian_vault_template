---
tags: type/person role/tk
aliases: 
birth: 0001-01-01
death: 
bio_short: Created everything. Used as a demo creator for the vault.
visual: "![[image.jpg]]"
created: 2023-11-26 19:32
updated: 2023-11-26 20:57
template-type: Creator
template-version: "1.11"
banner: "![[creator_banner.jpg]]"
---

# God

##  Bio
<!-- Short biography of the AUTHOR -->

> [!Bio short]
> `= this.bio_short`


## Content
<!-- Only most important I‘ve read -->
### Articles
```dataview
TABLE
file.cday AS "Created",
summary AS "Summary"
FROM "2_zettelkasten/literature_notes/article_notes"
WHERE contains(file.outlinks, this.file.link)
SORT file.cday DESC
```

### Books
```dataview
TABLE
file.cday AS "Created",
summary AS "Summary"
FROM "2_zettelkasten/literature_notes/book_notes"
WHERE contains(file.outlinks, this.file.link)
SORT file.cday DESC
```

### Classes
```dataview
TABLE
file.cday AS "Created",
summary AS "Summary"
FROM "2_zettelkasten/literature_notes/class_notes"
WHERE contains(file.outlinks, this.file.link)
SORT file.cday DESC
```

### Movies
```dataview
TABLE
file.cday AS "Created",
summary AS "Summary"
FROM "2_zettelkasten/literature_notes/movie_notes"
WHERE contains(file.outlinks, this.file.link)
SORT file.cday DESC
```

### Podcasts
```dataview
TABLE
file.cday AS "Created",
summary AS "Summary"
FROM "2_zettelkasten/literature_notes/pocasts_notes"
WHERE contains(file.outlinks, this.file.link)
SORT file.cday DESC
```

### Social Media Posts
```dataview
TABLE
file.cday AS "Created",
summary AS "Summary"
FROM "2_zettelkasten/literature_notes/social_media_notes"
WHERE contains(file.outlinks, this.file.link)
SORT file.cday DESC
```

### Videos
```dataview
TABLE
file.cday AS "Created",
summary AS "Summary"
FROM "2_zettelkasten/literature_notes/video_notes"
WHERE contains(file.outlinks, this.file.link)
SORT file.cday DESC
```
## Notes
<!-- The main content of my thoughts really -->
- 


## Quotes
<!-- Notable quotes with reference to their page or location -->
- 

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
- [[Creators]] - Map Of Content