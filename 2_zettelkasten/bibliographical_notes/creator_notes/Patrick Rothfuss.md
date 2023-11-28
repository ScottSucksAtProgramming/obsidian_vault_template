---
tags: type/person role/author
aliases: 
birth: 
death: 
bio_short: Author and internet celebrity most known for the King Killer Chronicles series
visual: https://upload.wikimedia.org/wikipedia/commons/7/7f/Patrick-rothfuss-2014-kyle-cassidy.jpg
created: 2023-11-26 19:32
updated: 2023-11-27 17:34
template-type: Creator
template-version: "1.11"
banner: "![[creator_banner.jpg]]"
---

# Patrick Rothfuss
<!-- Short biography of the AUTHOR -->
![image|150](https://upload.wikimedia.org/wikipedia/commons/7/7f/Patrick-rothfuss-2014-kyle-cassidy.jpg)



##  Bio

> [!Bio short]
> `= this.bio_short`


## Content
<!-- Only most important I‘ve read -->
### Articles
```dataview
TABLE
file.cday as "Created",
summary as "Summary"
FROM "2_zettelkasten/literature_notes/article_notes"
WHERE contains(file.outlinks, this.file.link)
SORT file.cday DESC
```

### Books
```dataview
TABLE WITHOUT ID
    link(file.link, title) as Title,
	"![|60](" + cover_url + ")" as Cover,
    summary AS Summary,
    join(list(publisher, publish_date)) as Publisher
FROM #type/book
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