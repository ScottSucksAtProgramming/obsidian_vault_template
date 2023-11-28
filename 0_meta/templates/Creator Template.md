---
tags: type/person role/tk
aliases: 
birth: 
death: 
summary: +++ Short Bio here +++
visual: "![[image.jpg]]"
created: 2023-11-26 19:32
updated: 2023-11-27 18:41
template-type: Creator
template-version: "1.11"
banner: "![[creator_banner.jpg]]"
---

# <% tp.file.title %>
<% await tp.file.move("/2_zettelkasten/bibliographical_notes/creator_notes/" + tp.file.title) %>
![image|150](<% tp.frontmatter.visual %>)
##  Bio
<!-- Short biography of the AUTHOR -->

> [!Short Bio]
> `= this.summary`


## Content
<!-- Only most important I‘ve read -->
### Articles
```dataview
TABLE WITHOUT ID
    link(file.link, title) as Title,
    file.cday AS "Created",
    summary AS "Summary"
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
FROM "#type/book"
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