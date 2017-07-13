---
date: '2013-07-24T00:00:00Z'
description: What Hugo short codes are and how they work
related:
- title: "“Hugo Short Code Reference”"
  url: https://gohugo.io/extras/shortcodes/
tags: ''
title: Hugo Short Codes
menu:
  developing-with-hugo:
    weight: 7

---
You can extend the functionality of markdown in Hugo with short codes. Short codes are special templates that are called when a short code is used inside the content body.

They can be used to add custom markup, format text, generate HTML elements, or pull in data from external sources.

## Using Short Codes in Forestry
Forestry provides no interface for using short codes in the editor, but does support using Hugo short codes.

Users must enter the short codes in the format Hugo requires them in the content file.

For example, using Hugo’s built-in figure short code, a user must enter the following into the content body:

```
{{</* figure src="/example.jpg" title="Example Image" */>}}
```

## Built-in Short Codes
Hugo ships with a collection of built-in short codes for modifying the output of your content body.

For a full list of these short codes and how to use them, see the references below.

## Custom Short Codes
Hugo also allows you to build your own short codes. See the Hugo short code documentation in the references below.
