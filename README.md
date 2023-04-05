<div align="center">
  <h1>airoots archive</h1>
  <p>
    Repository used to store a digitized collection of articles from the airoots blog.
  </p>
</div>

# Introduction

This project involves digitizing a collection of articles written by [Rahul Srivastava](https://www.urbz.net/rahul) and [Mattias Echanove](https://www.urbz.net/matias) for airoots / ɛəruːts /, a blog on adventitious roots, urban forests & villages, natural cities, lost tribes, new nomads, and everything in between.


# Table of Contents
* Digitizing An Article

# Digitizing an Article

Due to the incompatibility of most archive formats with web platforms, this section provides a quick guide on converting the current archive into structured markdown files.

### Naming Convention:

Each article will have its own markdown file and should be named according to the date of publication and its title.

The current naming convention has two main features:

- `DD-MM-YYYY` indicates the date of publication.
- `article-title` refers to the title of the article.

These features are combined as follows: 

`DD-MM-YYYY_article-title.md`

Here's an example: `28-06-2015_the-slum-explosion-anxiety.md`

### Creating a Markdown File:

Similar to the naming convention, all the articles must follow a standardized structure.

The header of each `.md` file contains the title, publication date, and associated blog, formatted as follows:

```
---
organization: 'airoots.org'
title: 'Article Name'
published: 'DD-MM-YYYY'
---
```

The text of each article is then added to the body of its respective `.md` file in the following manner:

```
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Scelerisque fermentum dui faucibus in.

Euismod quis viverra nibh cras pulvinar mattis. Arcu felis bibendum ut tristique. Ac tortor vitae purus faucibus ornare. Molestie at elementum eu facilisis sed odio.
```
Together, they would look something like this:

```
---
organization: 'airoots.org'
title: 'Article Name'
published: 'DD-MM-YYYY'
---

Euismod quis viverra nibh cras pulvinar mattis...

Arcu felis bibendum ut tristique...
```

Hyperlinks can be added to text by replacing the hyperlinked text with the following code:

`[text to hyperlink](link to source)`

For a complete example, refer to `sampleArticle.md`. Additionally, a digitized article is available for reference in `/articles`.


### Extra Resources:

If you're still feeling confused about markdown files, these resources might help.

- [Github's Guide on Basic Writing and Formatting Syntax](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
