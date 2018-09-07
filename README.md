## Create a post

1. go to https://github.com/research-technologies/research-technologies.github.io
2. make sure you are logged in and have edit rights for the reposoitory
3. go to the _posts folder
4. Click 'Create new file', the filename must begin with the date in the form `2018-06-20` (this is the date posted, it doesn't have to be today) and must end with `.markdown`. Keep the title short and sweet, separate words with dashes, eg. `2018-06-20-ref2020-plugin.markdown`

### Format of the post

#### Header

The file must have a header section like so:

```
---
layout: post
title:  "EPrints – New REF2021 Plugin"
date:   2018-06-20 12:45:00 +0100
categories: eprints plugins
---
```

The date must be the same date as used in the filename.
You can add any categories. Use a 'general' category for the first, and a more specific one for the second (optional). The second will be nested within the first.

Examples:
* eprints plugins - will create eprints/plugins folders
* samvera
* digital-preservation
* repositories

#### Body

The post text is written in markdown. This [markdown cheatsheet](https://www.markdownguide.org/cheat-sheet/) is helpful.

Common syntax:

```
**bold text**
*italicized text*

Numbered List:
1. First item
2. Second item
3. Third item

Bullet List:
- First item
- Second item
- Third item

Link:
[title](https://www.example.com)

```

### Files

Upload any files (eg. conference presentations etc.) into `assets/docs` using the 'upload files' option. 

Link within the post like so:

```
[Finding your way to a digital solution: identifying paths and option](https://research-technologies.github.io/assets/docs/HullCityofCultureWorkshop.pdf)
```

Upload images into `assets/images`

**NB:** Don't use spaces in filenames

## Commit the post

* Add a brief commit title, eg. 'new post on eprints ref plugin'
* Optionally add a longer description (not usually needed for posts)
* Click 'Commit new file'

## Edit a post

To edit an existing post, click on the pencil icon in the top right. Make your changes and commit as normal.

## Delete a post

To remove a post, click on the trash can icon in the top right. Commit as normal. The post will be archived in the commit history.

