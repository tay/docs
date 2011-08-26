
To add an article:

- make a directory in `topics` for your article: `mkdir topics/how-to-make-an-article` (use only letters and dashes)
- next write your article: `vim topics/how-to-make-an-article/article.md`
- if you have any reference javascript implentation, just place them next to the `article.md`
- create a metadata with this data: `vim topics/how-to-make-an-article/metadata.json`

```javascript
{
  "title":"What is npm?",
  "date": "Fri Aug 26 2011 03:08:50 GMT-0700 (PST)",
  "tags": ["npm", "modules"],
  "author": "nico",
  "difficulty": 1
}
```


Directory Structure
===================

    topics/
        article-name/ //url version
            metadata.json
            article.md //file with the real article
            assets/
                ...
        ...

Metadata Format
===============

```javascript
{
  "title":"What is npm?",
  "date": "Fri Aug 26 2011 03:08:50 GMT-0700 (PST)",
  "tags": ["npm", "modules"],
  "author": "nico",
  "difficulty": 1
}
```
