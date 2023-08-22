# Webapp CMS

## What and why?

This project is used as a CMS for the rich content related parts of our webapp.

This came to existance when we needed a dynamic FAQ, with search, tags and videos.

It can be used mainly for the content:

- That contains mostly text and are generated by our non-technical people
- That embed loom videos

## Current usage

### FAQ folder

The faq folder relates to all content on the website and webapp [https://app.partofthepack.com/faq](FAQ).

## How?

Create pages in markdown. You can use all rich markdown features [https://stackedit.io/app#](cfr StackEdit).
In fact, you can even use StackEdit to create your pages and then copy paste it into github here.

This video here explains the best way to do this:
<!-- add loom video here -->
### Metadata

Every article should contain some metadata

- title: Mandatory title of the page
- subtitle: Optional subtitle
- type:
  - question: In the case of FAQ, all the questions are added to the FAQ pages
  - intro: It should only contain one, and that is the intro of the FAQ home screen
  - outro: It should only contain one, and that is the outro of the FAQ home screen
- tags: This can contain a list of tags that are used on the FAQ website to filter easily
