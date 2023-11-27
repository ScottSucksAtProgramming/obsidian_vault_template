---
tags:
  - type/note
  - source/self
aliases: 
summary: Documents this vaults folder structure. It includes details for the subfolders, their contents and rules for maintaining and expanding the folder structure.
created: 2023-11-24 20:02
updated: 2023-11-26 19:20
banner: "![[vault_folder_structure_banner.jpg]]"
template-type: Note
template-version: "1.14"
---
<!--  See "Template Help" below for using properties -->

# Vault Folder Structure

<!--  Main idea of my thoughts -->

> [!Note]
> `= this.summary`

<!-- Other content of my note  -->
# `0_meta`
```
0_meta
├── assets
│   └── banners  
├── dashboards 
└── templates
```

The `0_meta` folder contains files which helps maintain and use the vault. Images and note banners are contained within the `assets` and `banners` subfolders respectively. `dashboards` contains frequently visited notes which act as dashboards for content and life management within the vault. Note templates and snippets to be added into a note's content reside in the `templates` folder.

# `1_lifeOS`
```
0_lifeOS
├── daily_notes
├── monthly_notes
├── people_notes
├── project_notes
├── quarterly_notes
├── weekly_notes
└── yearly_notes
```

`1_lifeOS` contains notes and folders related to my personal life. Periodic notes are contained within their respective folders: `daily_notes`, `weekly_notes`, `monthly_notes`, `quarterly_notes`, and `yearly_notes`. Project notes are stored within `project_notes`, and `people_notes` contain notes about the different people I maintain relationships with.

# `2_zettelkasten`

```
2_zettelkasten
├── bibliographical_notes
│   ├── article_notes
│   ├── book_notes
│   ├── class_notes
│   ├── creator_notes
│   ├── movie_notes
│   ├── podcast_notes
│   ├── social_media_notes
│   └── video_notes
├── fleeting_notes
├── literature_notes
│   └── meeting_notes
├── permanent_notes
└── structural_notes
    ├── concept_maps
    ├── index_notes
    ├── maps_of_content
    └── summary_notes
```

This vault is used as a personal knowledge management repository using the [[Zettelkasten Method]]. All notes related to general knowledge are stored within this directory and it's subfolders. This directory can be directly moved to new vaults without disrupting the notes or links contained within. Notes containing details about a book, article or other information source are stored in `bibliographical_notes`. Information gained from external sources are not stored in that folder but instead reside in `literature_notes`. [[Fleeting Notes|Temporary or draft notes]] are saved within `fleeting_notes` and should be removed or converted into [[Permanent Notes]] which live within the `permanent_notes` folder. Notes which are used to organize other notes and information within the vault are kept in `structural_notes` and are further broken down by their type or purpose into [[Index Notes]], [[Maps of Content]], [[Summary Notes]], and [[Concept Maps]].

# Rules for the vault's structure

1. Folder names are written in snake case. Capitalization should be used sparingly and only when using a nemonic such as `1_life_OS` to denote Life Operating System.
2. Folders should be named for the process or type of item they contain within a large structural idea. These folders should rarely change. Tagging is used to otherwise categorize notes in a more flexible manner than folders allow.
3. This folder structure prefers a greater number of folders over increased depth of folders. Unless absolutely necessary this structure should not have more than two levels. Further organization can be created using Obsidian's tagging system and with the use of [[Structural Notes]].

---
# Back Matter

## Source
<!-- Always keep a link to the source- --> 
- [[How to Use This Vault]]

## Tasks
<!-- What remains to be done with this note? --> 
- 

## Questions
<!-- What remains for you to consider? --> 
- 

## Terms
<!-- Links to definition pages. -->
- 

## References
<!-- Links to pages not referenced in the content. -->
- [Johnny Decimal System](https://johnnydecimal.com/)
- 
