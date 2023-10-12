# Hackers@UPC Legal documents

This page contains public legal documents related to Hackers@UPC contains the Privacy policy, cookies policy and this kind of documents.

## Create a new document

To add a new document, create a `.md` file inside [`/_documents`](/_documents) and use this template:

```md
---
layout: document
title: 'My Document Title Here'
categories: eventNameHere
---

# My Document Title Here

Content: bla, bla, bla...

## Example subtitle

Even more content: bla, bla, bla...
```

Your new document url is going to be:

https://<span></span>legal.hackersatupc.org/`categories`/`my_document_filename`

- The `categories` attribute is used to organize the documents and build its url.
- The `title` attribute is displayed in the document's HTML title, it can be different from the h1.

## Edit an existing document

Find your document in the [`/_documents/`](/_documents) folder and edit its contents.

## Deployautomatically

Once you make a push to master your changes will be deployed automaticaly by [GitHub Pages](https://pages.github.com/), usually it takes seconds.

## Develop

```bash
gem install jekyll
jekyll serve --watch
```
