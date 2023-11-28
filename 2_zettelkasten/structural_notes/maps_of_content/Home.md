---
tags:
  - type/structure
  - structure/moc
aliases: 
summary: This is a Map of Content for my entire vault. It serves as a starting point for accessing the vault.
visual: "![[image.jpg]]"
created: 2023-11-24 20:33
updated: 2023-11-27 19:06
template-type: Structure
template-version: "1.8"
banner: "![[home_note_banner.jpg]]"
---

# [[Home]]
Welcome to the Home of this obsidian vault. Here you should find links to the most used notes within the vault.


<!-- Main STRUCTURE of my content -->
# Meta
The first division of this vault is for notes which help structure and manage the data within.


## [[How to Use This Vault]]
![[How to Use This Vault#How to Use This Vault]]
## [[Templates]]
![[Templates#Templates]]

---


# Life OS
This second division of this vault contains notes and information which are private, sensitive, or have to do with managing my life. 


## [[Periodic Notes]]
![[Periodic Notes#Periodic Notes]]

- [[Periodic Notes#Daily Notes|Daily Notes]]
- [[Periodic Notes#Weekly Notes|Weekly Notes]]
- [[Periodic Notes#Monthly Notes|Monthly Notes]]
- [[Periodic Notes#Quarterly Notes|Quarterly Notes]]
- [[Periodic Notes#Yearly Notes|Yearly Notes]]

## [[Projects]]
![[Projects#Projects]]

## [[People]]
![[People#People]]


---
# Zettelkasten
The third division of this vault is related to personal knowledge management. It maintains a slip-box style [[Zettelkasten Method|Zettelkasten]] system which keeps track of the areas of knowledge I am concerned with.
## [[Books]]
![[Books#Books]]

## [[Creators]]
![[Creators#Creators]]

## [[Meetings]]
![[Meetings#Meetings]]


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
- 

### Related Notes Not Listed in this Map of Content
```dataview
TABLE WITHOUT ID
    link(file.link, title) as Title,
	summary as Summary
FROM "2_zettelkasten/structural_notes"
WHERE !contains(this.file.outlinks, file.link)
sort file.name ASC
```