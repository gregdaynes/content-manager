Content Manager
---------------


Ideas

+ CRM/Site agnostic
+ + using mapping, determine how to generate content

+ Image uploader/manager
+ + crop, rotate, resize, creative control
+ 1:1 Joomla article fields
+ mongo/sql/markdown storage

+ site mapping system
+ + get categories
+ + get tags

+ create article
+ + pick site
+ + + get tags/categories
+ + write article
+ + upload images
+ + insert images into article
+ + pick additional sites + tags, cats
+ + publish
+ + + create articles on sites
+ + + return article ids for each site, store with document

+ Un-publish article
+ + using id stored in document
+ + all sites
+ + or individual

+ Update article
+ + using id stored in document
+ + all sites
+ + or individual

+ Newsletter Control?
+ + How?

## Table of Contents

1. Content Manager
    1. Create Articles
    2. Update Articles
    3. Publish/un-publish articles
2. Mapping Content
3. Newsletter Manager
4. Image Manager

## Content Manager 

###  Creating Content

Should be simple, wysiwyg, ability to add images, follow markdown format, allow for all markdown related things, including tables

creating content, use categories/tags from each site, using some sort of GUI like

```
Sites:  
    [siteA]: [categories, cate…] [tags, tags, tag…]
		[siteB]: [category, cate…] [tags, tag, tags…]
		(add another site)
```

#### UI

```
Sites
---
Fields
---
Content
---
Images
```
