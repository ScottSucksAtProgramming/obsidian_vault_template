---
tags:
  - type/structure
  - structure/moc
aliases: 
summary: Map of content for all the templates used within this Vault
visual: "![[image.jpg]]"
created: 2023-11-24 20:33
updated: 2023-11-27 16:17
template-type: Structure
template-version: "1.8"
banner: 
---

# Templates

<!-- Main STRUCTURE of my content -->
# Generic Note Templates
- [[_Note Template]] - For notes which are not otherwise specialized.
- [[_Question Template]] - For questions related to notes.

# Periodic Note Templates
- [[Daily Note Template]]
- [[Weekly Note Template]]
- [[Monthly Note Template]]
- [[Quarterly Note Template]]
- [[Yearly Note Template]]

# Life OS Note Templates
- [[Person Template]]- Used as bibliographical reference for people I maintain relationships with in my life. Created with the `Create new person` command using the [[QuickAdd Plugin]].
- [[Project Template]]

# Zettelkasten Note Templates
- [[Book Template]] - Used as bibliographical reference for books. Created with the `Create new book note` command using the [[Book Search Plugin]].
- [[Creator Template]] - Used as bibliographical reference for creators, authors, artists, etc. Created with the `Create new creator` command using the [[QuickAdd Plugin]].
- [[Meeting Note Template]] - Used to record information about meetings I attend. Created with the `Create meeting` command using the [[QuickAdd Plugin]].
- [[Structure Template]]
- [[Prompt Template]] - For notes containing AI prompts. Created with the `Create prompt` command using the [[QuickAdd Plugin]].
- [[Quote Template]] - Created with the `Create quote` command using the [[QuickAdd Plugin]].
- [[Recipe Template]] - Created with the `Create recipe` command using the [[QuickAdd Plugin]].
- [[Term Template]] - For terms and definitions. Created with the `Create term` command using the [[QuickAdd Plugin]].
- [[Tool Template]] - For notes related to different tools (software, physical items, etc) which I use. Created with the `Create tool` command using the [[QuickAdd Plugin]].
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

### Templates Not Listed in this Map of Content
```dataview
LIST
FROM "0_meta/templates"
WHERE !contains(this.file.outlinks, file.link)
sort file.name ASC
```